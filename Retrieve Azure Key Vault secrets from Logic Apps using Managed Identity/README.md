# Retrieve Azure Key Vault secrets from Logic Apps using Managed Identity

This template will create a Key Vault with a secret, and a Logic App with a Managed Identity assigned. The Logic App retrieves the secret from Key Vault using an HTTP action with the Managed Identity as authentication. After deployment access should be granted for the Managed Identity of the Logic App on Key Vault. The complete scenario can be found on <https://blog.eldert.net/retrieve-azure-key-vault-secrets-from-logic-apps-using-managed-identity>.

Tags: logic apps, key vault

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FRetrieve%20Azure%20Key%20Vault%20secrets%20from%20Logic%20Apps%20using%20Managed%20Identity%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FRetrieve%20Azure%20Key%20Vault%20secrets%20from%20Logic%20Apps%20using%20Managed%20Identity%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
