---
swagger: "2.0"
x-collection-name: Azure Recovery Services
x-complete: 1
info:
  title: RecoveryServicesClient
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /Subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.RecoveryServices/vaults/{vaultName}/backupstorageconfig/vaultstorageconfig
  : get:
      summary: Backup Storage Configs Get
      description: Fetches resource storage config.
      operationId: BackupStorageConfigs_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnamebackupstorageconfigvaultstorageconfig-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Backup Storage Configs
    patch:
      summary: Backup Storage Configs Update
      description: Updates vault storage model type.
      operationId: BackupStorageConfigs_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-recoveryservicesvaultsvaultnamebackupstorageconfigvaultstorageconfig-patch
      parameters:
      - in: body
        name: backupStorageConfig
        description: Backup storage config
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Backup Storage Configs
---