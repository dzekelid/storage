---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Upload a single file to frontend storage.
  description: If file is an image, generate a thumbnail and store dimensions in metadata.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts/{contactId}/document:
    get:
      summary: Get a single storage object from contact documents
      description: Get a single storage object from contact documents.
      operationId: getRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-get
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key of the object to get from contact documents
      responses:
        200:
          description: OK
      tags:
      - Single
      - Storage
      - Object
      - From
      - Contact
      - Documents
  /rest/items/{id}/variations/{variationId}/stock/storageLocations:
    get:
      summary: List stock of a variation per storage locations
      description: Lists stock of a variation per storage location. The ID of the
        item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationStockStoragelocations
      x-api-path-slug: restitemsidvariationsvariationidstockstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Variation
      - Per
      - Storage
      - Locations
  /rest/stockmanagement/warehouses/{warehouseId}/management/racks/{rackId}/shelves/{shelfId}/storageLocations:
    get:
      summary: List storage locations
      description: Lists storage locations. The id of the warehouse, the id of the
        rack and the id of the shelf must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: query
        name: itemsPerPage
        description: Number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Storage
      - Locations
    post:
      summary: Create a storage location
      description: Creates a storage location. The id of the warehouse, the id of
        the rack and the id of the shelf must be specified.
      operationId: postRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
      parameters:
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/management/racks/{rackId}/shelves/{shelfId}/storageLocations/{storageLocationId}:
    get:
      summary: Get a storage location
      description: Gets a storage location. The id of the warehouse, the id of the
        rack, the id of the shelf and the id of the storage location must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocationsStoragelocat
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: storageLocationId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/management/storageLocations:
    get:
      summary: List storage locations
      description: Lists storage locations that belong to a warehouse. The id of the
        warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: query
        name: itemsPerPage
        description: Number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Storage
      - Locations
  /rest/stockmanagement/warehouses/{warehouseId}/management/storageLocations/{storageLocationId}:
    get:
      summary: Get a storage location
      description: Gets a storage location. The id of the storage location and the
        id of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementStoragelocationsStoragelocation
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: storageLocationId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/stock/storageLocations:
    get:
      summary: List stock of a warehouse per storage location
      description: Lists stock of a warehouse for each variation and storage location.
        The stock will only be listed if the stock is positive. Negative stock will
        not be listed. The ID of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseStockStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: query
        name: storageLocationId
        description: Filter that restricts the search result to stock of a storage
          location
      - in: query
        name: updatedAtFrom
        description: Filter that restricts the search result to stock that were last
          updated on the specified date
      - in: query
        name: updatedAtTo
        description: Filter that restricts the search result to stock that were last
          updated within a specified period of time
      - in: query
        name: variationId
        description: Filter that restricts the search result to stock with a variation
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: Load additional relations for a StockStorageLocation
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Warehouse
      - Per
      - Storage
      - Location
  /rest/storage/frontend/file:
    delete:
      summary: Remove a single object from frontend storage.
      description: Remove a single object from frontend storage..
      operationId: deleteRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-delete
      parameters:
      - in: query
        name: key
        description: The key of the object to delete
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Single
      - Object
      - From
      - Frontend
      - Storage
    get:
      summary: Get file information for a single object in frontend storage. Append
        public cloudfront url to retrieved object.
      description: Get file information for a single object in frontend storage. append
        public cloudfront url to retrieved object..
      operationId: getRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-get
      parameters:
      - in: query
        name: key
        description: The key of the object to get information about
      responses:
        200:
          description: OK
      tags:
      - File
      - Informationa
      - Single
      - Object
      - In
      - Frontend
      - Storage
      - ""
      - Append
      - Public
      - Cloudfront
      - Url
      - To
      - Retrieved
      - Object
    post:
      summary: Upload a single file to frontend storage.
      description: If file is an image, generate a thumbnail and store dimensions
        in metadata.
      operationId: postRestStorageFrontendFile
      x-api-path-slug: reststoragefrontendfile-post
      parameters:
      - in: query
        name: key
        description: The key for the uploaded object
      - in: query
        name: maxAge
        description: Number of seconds until the content of the file expires
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Single
      - File
      - To
      - Frontend
      - Storage
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---