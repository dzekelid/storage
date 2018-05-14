---
name: Azure Storage
description: Azure Storage offers non-relational data storage including Blob Storage,
  Table Storage, Queue Storage, and Files.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Storage
- Stack Network
- Microsoft
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-storage/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Storage API
  description: Azure Storage offers non-relational data storage including Blob Storage,
    Table Storage, Queue Storage, and Files
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Storage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-storage/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-storage-storageaccounts-accountname-listservicesas-post.md
- name: Azure Storage API Storage Accounts Update
  description: The update operation can be used to update the SKU, encryption, access
    tier, or tags for a storage account. It can also be used to map the account to
    a custom domain. Only one custom domain is supported per storage account; the
    replacement/change of custom domain is not supported. In order to replace an old
    custom domain, the old value must be cleared/unregistered before a new value can
    be set. The update of multiple properties is supported. This call does not change
    the storage keys for the account. If you want to change the storage account keys,
    use the regenerate keys operation. The location and name of the storage account
    cannot be changed after creation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: http:://management.azure.com//
  tags: Storage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-storage/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-storage-storageaccounts-accountname-patch.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/storage/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/storage/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/storage/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/storage/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/storage/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/storage/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/storage/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/storage/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---