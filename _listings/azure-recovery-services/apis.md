---
name: Azure Recovery Services
x-slug: azure-recovery-services
description: Learn how to use Site Recovery for business continuity and disaster recovery
  strategy for private clouds. Tutorials and other documentation show you how to plan,
  deploy, and manage the orchestration of replicating on-premises physical servers
  and virtual machines to the cloud or to a secondary datacenter.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Storage
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-recovery-services/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Recovery Service API Backup Storage Configs Get
  x-api-slug: azure-recovery-service-api
  description: Fetches resource storage config.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
  humanURL: https://azure.microsoft.com/en-us/services/site-recovery/
  baseURL: ://management.azure.com////Subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.RecoveryServices/vaults/{vaultName}/backupstorageconfig/vaultstorageconfig
  tags: Backup Storage Configs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-recovery-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnamebackupstorageconfigvaultstorageconfig-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-recovery-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnamebackupstorageconfigvaultstorageconfig-get-openapi.md
- name: Azure Recovery Service API Backup Storage Configs Update
  x-api-slug: azure-recovery-service-api
  description: Updates vault storage model type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
  humanURL: https://azure.microsoft.com/en-us/services/site-recovery/
  baseURL: ://management.azure.com////Subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.RecoveryServices/vaults/{vaultName}/backupstorageconfig/vaultstorageconfig
  tags: Backup Storage Configs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-recovery-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnamebackupstorageconfigvaultstorageconfig-patch-openapi.md
- name: Azure Recovery Service API
  x-api-slug: azure-recovery-service-api
  description: Learn how to use Site Recovery for business continuity and disaster
    recovery strategy for private clouds. Tutorials and other documentation show you
    how to plan, deploy, and manage the orchestration of replicating on-premises physical
    servers and virtual machines to the cloud or to a secondary datacenter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-site-recovery.png
  humanURL: https://azure.microsoft.com/en-us/services/site-recovery/
  baseURL: ://management.azure.com//
  tags: Storage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/storage/master/_listings/azure-recovery-services/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/site-recovery/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/site-recovery/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/site-recovery/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/site-recovery/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---