<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [UserRuntimeInfo](./models.userruntimeinfo.md)

## UserRuntimeInfo class

Represents the runtime information of the User.

**Signature:**

```typescript
export declare class UserRuntimeInfo
```

## Constructors

| Constructor                                                                          | Modifiers | Description                                                         |
| ------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------- |
| [(constructor)({ backendModel, locale })](./models.userruntimeinfo._constructor_.md) |           | Constructs a new instance of the <code>UserRuntimeInfo</code> class |

## Properties

| Property                                                                             | Modifiers | Type                                                                    | Description                                                              |
| ------------------------------------------------------------------------------------ | --------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [\_backendModel](./models.userruntimeinfo._backendmodel.md)                          |           | [BackendUserRuntimeInfo](./open-api-client.userruntimeinfo.md)          |                                                                          |
| [getInternalModel](./models.userruntimeinfo.getinternalmodel.md)                     |           | () =&gt; [BackendUserRuntimeInfo](./open-api-client.userruntimeinfo.md) |                                                                          |
| [hasPublishRights](./models.userruntimeinfo.haspublishrights.md)                     |           | boolean                                                                 | Whether the User has the publish rights.                                 |
| [isAdministrator](./models.userruntimeinfo.isadministrator.md)                       |           | boolean                                                                 | Whether the User is a system administrator.                              |
| [isPublicationAdministrator](./models.userruntimeinfo.ispublicationadministrator.md) |           | boolean                                                                 | Whether the current User has the repository-local administration rights. |
| [locale](./models.userruntimeinfo.locale.md)                                         |           | [UserLocaleInfo](./models.userlocaleinfo.md) \| undefined               | Information about User locale.                                           |
