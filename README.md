# gitops.action.cd-env-bicep


Run following command

```
az ad sp create-for-rbac --name cd-env-bicep --role contributor --scopes /subscriptions/30a911a0-bad6-47e9-8aeb-507c96ed5d18 --sdk-auth
```


```
{
  "clientId": "89056882-5ceb-4d34-8824-2981850bcf81",
  "clientSecret": "6sbZGLKG42BgGukbhlUIZ7~k2ibpTWpT.8",
  "subscriptionId": "30a911a0-bad6-47e9-8aeb-507c96ed5d18",
  "tenantId": "301492ba-4fbf-4114-be09-2b346e16849f",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```
