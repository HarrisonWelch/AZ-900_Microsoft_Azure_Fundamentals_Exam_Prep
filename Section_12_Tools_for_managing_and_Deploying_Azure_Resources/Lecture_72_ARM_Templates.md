# Lecture_72_ARM_Templates

ARM - Azure Resource Manager

Service that runs underneath the Azure Portal.

Think of this as the middle layer

Protal creates an ARM template

Sample (JSON):
```json
"resources": [
    {
        "type": "Microsoft.Storage/storageAccounts",
        "apiVersion": "2019-06-01",
        "name": "[parameters('storageAccountName')]",
        "location": "[parameters('location')]",
        "sku": {
            "name": "Standard_LRS",
            "tier": "Standard"
        },
        "kind": "StorageV2",
        "properties": {
            "accessTier": "Hot"
        },
        "resources": [
            {
                "type": "blobServices/contaiers",
                "apiVerison": "2019-06-01",
                "name": "[concat('default/', parameters('containerName'))]",
                ...
            }
            ...
        ]
        ...
    }
    ...
]
```

End up with a set of variables

"Type" is a "Microsoft.Storage" object
"accessTier" is "Hot"
