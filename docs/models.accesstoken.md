<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [AccessToken](./models.accesstoken.md)

## AccessToken class

**Signature:**

```typescript
export declare class AccessToken extends User
```

**Extends:** [User](./models.user.md)

## Constructors

| Constructor                                                                                                      | Modifiers | Description                                                     |
| ---------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------- |
| [(constructor)({ backendModel, inheritedSystemPrivileges, ...userArgs })](./models.accesstoken._constructor_.md) |           | Constructs a new instance of the <code>AccessToken</code> class |

## Properties

| Property                                                                       | Modifiers | Type                                                                              | Description                                                                                         |
| ------------------------------------------------------------------------------ | --------- | --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| [\_backendModel](./models.accesstoken._backendmodel.md)                        |           | [BackendAccessToken](./open-api-client.accesstoken.md)                            |                                                                                                     |
| [expiresAt](./models.accesstoken.expiresat.md)                                 |           | string \| undefined                                                               | Expiration date and time in UTC format for this token.                                              |
| [getInternalModel](./models.accesstoken.getinternalmodel.md)                   |           | () =&gt; [BackendAccessToken](./open-api-client.accesstoken.md)                   |                                                                                                     |
| [inheritedSystemPrivileges](./models.accesstoken.inheritedsystemprivileges.md) |           | [SystemPrivilegesDictionary](./models.systemprivilegesdictionary.md) \| undefined | Dictionary containing "SystemPrivilege" and link "Group" associations.                              |
| [signature](./models.accesstoken.signature.md)                                 |           | string \| undefined                                                               | Signature value for this token to prevent modifying any of its properties outside of the CM system. |