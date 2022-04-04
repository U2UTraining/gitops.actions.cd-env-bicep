# gitops.action.cd-env-bicep


Run following command

```
az ad sp create-for-rbac --name cd-env-bicep --role contributor --scopes /subscriptions/<<SUBSCRIPTION_ID_>> --sdk-auth
```


```
{
  "clientId": "<<CLIENT_GUID>>",
  "clientSecret": "<<SECRET_GUID>>",
  "subscriptionId": "<<SUBSCRIPTION_ID_>>",
  "tenantId": "<<TENANT_GUID>",
}
```
