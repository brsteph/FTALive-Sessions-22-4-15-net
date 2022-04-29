# Milestone: Assess and Select Target File Share Service
#### [prev](./overview.md) | [home](./readme.md)  | [next](./scan.md)

The following content can be used as a checklist to incorporate within your migration project plan to ensure best practices.

## **Choose a Target File Share Service** 
### Choose between IaaS vs. PaaS file shares.

Review this [table](https://docs.microsoft.com/en-us/azure/virtual-desktop/store-fslogix-profile#azure-platform-details) to help identify your initial file share cloud platform model. 
### Validate best fit scenario 

Review this [table](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/considerations/storage-options?toc=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fazure%2Farchitecture%2Ftoc.json&bc=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fazure%2Farchitecture%2Fbread%2Ftoc.json#file-and-object-storage-scenarios) to help identify your initial scenario and suggested PaaS file share service.
### Initial review for protocol, performance and limits

Review this [decision tree](https://docs.microsoft.com/en-us/azure/storage/common/storage-migration-overview?bc=/azure/cloud-adoption-framework/_bread/toc.json&toc=/azure/cloud-adoption-framework/toc.json#choose-a-target-storage-service) to help choose between Azure Files, Azure NetApps, and Blob Storage.

### Deeper Review to help choose between Blob, Azure Files and NetApps

Validate your selection via the below comparison tables to help make the final decision on a target file share service:
- [Table Comparison for Blob Storage, Azure Files and NetApps](https://docs.microsoft.com/en-us/azure/storage/common/nfs-comparison?toc=/azure/storage/files/toc.json)
- [Table Comparison for Azure and NetApps](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-netapp-comparison)

