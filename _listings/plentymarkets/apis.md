---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Storage
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Get a single storage object from contact documents
  x-api-slug: restaccountscontactscontactiddocument-get
  description: Get a single storage object from contact documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restaccountscontactscontactiddocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restaccountscontactscontactiddocument-get-openapi.md
- name: plentymarkets REST-API - List stock of a variation per storage locations
  x-api-slug: restitemsidvariationsvariationidstockstoragelocations-get
  description: Lists stock of a variation per storage location. The ID of the item
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get
  description: Lists storage locations. The id of the warehouse, the id of the rack
    and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get
  description: Lists storage locations that belong to a warehouse. The id of the warehouse
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Remove a single object from frontend storage.
  x-api-slug: reststoragefrontendfile-delete
  description: Remove a single object from frontend storage..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-delete-openapi.md
- name: plentymarkets REST-API - Get file information for a single object in frontend
    storage. Append public cloudfront url to retrieved object.
  x-api-slug: reststoragefrontendfile-get
  description: Get file information for a single object in frontend storage. append
    public cloudfront url to retrieved object..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-get-openapi.md
- name: plentymarkets REST-API - Upload a single file to frontend storage.
  x-api-slug: reststoragefrontendfile-post
  description: If file is an image, generate a thumbnail and store dimensions in metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfile-post-openapi.md
- name: plentymarkets REST-API - Get assigend metadata for a single storage object
  x-api-slug: reststoragefrontendfilemetadata-get
  description: Get assigend metadata for a single storage object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfilemetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfilemetadata-get-openapi.md
- name: plentymarkets REST-API - Update metadata of an storage object
  x-api-slug: reststoragefrontendfilemetadata-post
  description: Update metadata of an storage object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfilemetadata-post-openapi.md
- name: plentymarkets REST-API - Delete files from frontend storage.
  x-api-slug: reststoragefrontendfiles-delete
  description: Deletes a list of files from frontend storage. A list of storage keys
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfiles-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfiles-delete-openapi.md
- name: plentymarkets REST-API - List files from frontend storage. Append public cloudfront
    url to each retrieved object.
  x-api-slug: reststoragefrontendfiles-get
  description: List files from frontend storage. append public cloudfront url to each
    retrieved object..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/reststoragefrontendfiles-get-openapi.md
- name: plentymarkets REST-API - Edit the purpose and status for a group of storage
    locations
  x-api-slug: restwarehouseslocationsgroup-put
  description: Edits the purpose and status for a group of storage locations by passing
    the group storage location ID (can be sent as mass assignment)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---