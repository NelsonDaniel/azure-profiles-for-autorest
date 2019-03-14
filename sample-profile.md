# Hybrid Profile Definition - Azure Stack General Availability and Azure Cloud

> see https://aka.ms/autorest

This is a dummy profile. Not official.

To use this profile add the flag:

--profile=2017-03-09-profile

```yaml
profiles:
    sample-profile:
        microsoft.compute:
            '2018-10-01':
                - availabilitySets
                - images
                - locations
                - locations/publishers
                - locations/operations
                - locations/usages
                - locations/vmSizes
                - operations
                - virtualMachines
                - virtualMachines/extensions
                - virtualMachineScaleSets
                - virtualMachineScaleSets/extensions
                - virtualmachineScaleSets/networkInterfaces
                - virtualMachineScaleSets/virtualMachines
                - virtualMachineScaleSets/virtualMachines/networkInterfaces
                - disks
                - locations/diskoperations
                - snapshots
        microsoft.storage:
            '2018-11-01':
                - checkNameAvailability
                - locations
                - locations/quotas
                - operations
                - storageAccounts
                - storageAccounts/blobServices
                - storageAccounts/queueServices
                - storageAccounts/tableServices
                - usages
```
