{
  "info": {
    "name": "Azure Recovery Service API Backup Storage Configs Get",
    "_postman_id": "7ee1b0ba-438f-4b06-a4c3-b55064fea924",
    "description": "Fetches resource storage config.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "backup storage configs",
      "item": [
        {
          "id": "3ab7502e-c86d-4816-8b14-50b9897ae1c1",
          "name": "BackupStorageConfigs_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "Subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.RecoveryServices/vaults/:vaultName/backupstorageconfig/vaultstorageconfig"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "vaultName",
                  "value": "vaultName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetches resource storage config"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d8ebc3e-abb0-4cbc-9ca7-a7cdc6352ed1"
            }
          ]
        }
      ]
    }
  ]
}