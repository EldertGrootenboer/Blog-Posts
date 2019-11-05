# Implementing smart caching of secrets in Azure API Management policies

This template will create a Key Vault with a secret, and an API Management instance with an API with a single operation. After creation the endpoint of the secret should be updated in the API Management policy, and access should be granted for the Managed Identity of API Management on Key Vault. The complete scenario can be found on <https://blog.eldert.net/implementing-smart-caching-of-secrets-in-azure-api-management-policies>.

Tags: api management, key vault, caching

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FImplementing%2520smart%2520caching%2520of%2520secrets%2520in%2520Azure%2520API%2520Management%2520policies%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FEldertGrootenboer%2FBlog-Posts%2Fmaster%2FImplementing%2520smart%2520caching%2520of%2520secrets%2520in%2520Azure%2520API%2520Management%2520policies%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
