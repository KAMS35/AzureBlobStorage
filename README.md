# A tutorial for Azure Blob Storage

Prompt 1 will contain the following elements:
* Creating an Azure Blob Storage account 
* Creating a container in that storage account 
* Seeing what containers exist within the storage account
* Uploading data to that container 
* Seeing items are inside of that container 
* Deleting an item in that container 
* Deleting the container 
* Deleting the storage account 


## 1] Creating a storage account
1. Sign into the Azure portal to view the dashboard.

2. Under the resource section, select the "Storage Accounts" and click on "+Add".  ![Add New Storage Account] (https://github.com/KAMS35/AzureBlobStorage/blob/master/screenshots/1.%20adding%20a%20new%20storage%20account.png)

3. Enter in the required details for the storage account as recommended. Here, the deployment model is set to "resource  Manager" and the account kind is choosen as "Blob storage".  ![Details for the storage account](https://github.com/KAMS35/AzureBlobStorage/blob/master/screenshots/2.%20storage%20account%20creation.png)

4. After all the information is entered correctly, click "Create". You may choose the option "Pin to dashboard" for ease of access. The storage account is now created. 

## 2] Creating a container
1. Open the storage account you just created.

2. Click on the "+Container" tab. ![Creating a container](https://github.com/KAMS35/AzureBlobStorage/blob/master/screenshots/3.%20creating%20a%20container.png)

3. Choose a name for the container and click "create". Your container will now be created.

## 3] Uploading data
Inside the container, click on the "Upload" tab to select files from your computer to upload.
Since this is a blob, several file extensions are accepted.
![File upload](https://raw.githubusercontent.com/KAMS35/AzureBlobStorage/master/screenshots/4.%20uploading%20new%20items.png)

![File uploading](https://github.com/KAMS35/AzureBlobStorage/blob/master/screenshots/5.%20uploading%20into%20blob.png)

## 4] Deleting items
1. Click on a file to view its properties and you can either download a copy of this file or choose to delete it. ![Deleting](https://raw.githubusercontent.com/KAMS35/AzureBlobStorage/master/screenshots/6.%20deleting%20data.png)

2. Click on "Delete" and Confirm "Yes" to delete the item. ![Deleting](https://raw.githubusercontent.com/KAMS35/AzureBlobStorage/master/screenshots/7.%20Deleting%20items.png)

## 5] Deleting the Container
To delete a container, click on the desired container, choose "Delete Container", and confirm "Yes". ![deleting the container](https://raw.githubusercontent.com/KAMS35/AzureBlobStorage/master/screenshots/8..%20deleting%20the%20container.png)

## 6] Deleting the storage account
Choose the storage account you wish to delete, click on "Delete". Type in the name of the storage account in the box and click on "Delete" button on the bottom.
![deleting the storage account](https://raw.githubusercontent.com/KAMS35/AzureBlobStorage/master/screenshots/9.%20deleting%20the%20storage%20account.png)
