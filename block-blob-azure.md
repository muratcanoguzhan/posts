Uploading Large Size Files By Using Azure Blob Storage

The idea in this text is just how to upload a large file to Azure Blob Storage. So let's directly start with how we can do it.
First, we need to create a storage account in azure https://portal.azure.com/. It is easy to find just type "storage account" into the search box then configure it according to your needs. You can follow up on this link https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal.
To upload a large file to Azure we will use Block Blob. There are different types of blobs in Azure so why we will use and what are the differences between the other blob types you can read this link https://docs.microsoft.com/en-us/rest/api/storageservices/understanding-block-blobs--append-blobs--and-page-blobs. But the first two sentences are enough to understand;
Block blobs are optimized for uploading large amounts of data efficiently. Block blobs are composed of blocks, each of which is identified by a block ID.
So go on;
Now we can connect to Azure Blob Storage by using our new connection string. 

https://gist.github.com/muratcanoguzhan/50c96b7d0018211db8361c02c59e45ad
