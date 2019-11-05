# Retrieve Azure Storage access keys in ARM template

This template will create a Storage account, after which it will create a API connection by dynamically retrieving the primary key of the Storage account. The API connection is then used in a Logic App as a trigger polling for blob changes. The complete scenario can be found on <https://blog.eldert.net/retrieve-azure-storage-access-keys-in-arm-template>.

Tags: arm, storage

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FRetrieve%2520Azure%2520Storage%2520access%2520keys%2520in%2520ARM%2520template%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FRetrieve%2520Azure%2520Storage%2520access%2520keys%2520in%2520ARM%2520template%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
