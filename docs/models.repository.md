<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [Repository](./models.repository.md)

## Repository class

Represents a Repository: a context for BluePrinting.

**Signature:**

```typescript
export declare class Repository extends SystemWideObject
```

**Extends:** [SystemWideObject](./models.systemwideobject.md)

## Constructors

| Constructor                                                                                                                                                                                                                                                                                              | Modifiers | Description                                                    |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------- |
| [(constructor)({ backendModel, accessControlList, businessProcessType, contentSecurityDescriptor, defaultMultimediaSchema, locationInfo, metadataSchema, minimalLocalizeApprovalStatus, parents, rootFolder, taskProcess, versionInfo, ...systemWideObjectArgs })](./models.repository._constructor_.md) |           | Constructs a new instance of the <code>Repository</code> class |

## Properties

| Property                                                                              | Modifiers | Type                                                                    | Description                                                              |
| ------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [\_backendModel](./models.repository._backendmodel.md)                                |           | [BackendRepository](./open-api-client.repository.md)                    |                                                                          |
| [accessControlList](./models.repository.accesscontrollist.md)                         |           | [AccessControlList](./models.accesscontrollist.md) \| undefined         |                                                                          |
| [businessProcessType](./models.repository.businessprocesstype.md)                     |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [contentSecurityDescriptor](./models.repository.contentsecuritydescriptor.md)         |           | [SecurityDescriptor](./models.securitydescriptor.md) \| undefined       |                                                                          |
| [defaultMultimediaSchema](./models.repository.defaultmultimediaschema.md)             |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [getInternalModel](./models.repository.getinternalmodel.md)                           |           | () =&gt; [BackendRepository](./open-api-client.repository.md)           |                                                                          |
| [hasChildren](./models.repository.haschildren.md)                                     |           | boolean                                                                 | Whether this Repository has child Repositories in a BluePrint hierarchy. |
| [key](./models.repository.key.md)                                                     |           | string \| undefined                                                     |                                                                          |
| [locationInfo](./models.repository.locationinfo.md)                                   |           | [LocationInfo](./models.locationinfo.md) \| undefined                   |                                                                          |
| [metadata](./models.repository.metadata.md)                                           |           | [FieldsValueDictionary](./models.fieldsvaluedictionary.md) \| undefined |                                                                          |
| [metadataSchema](./models.repository.metadataschema.md)                               |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [minimalLocalizeApprovalStatus](./models.repository.minimallocalizeapprovalstatus.md) |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [parents](./models.repository.parents.md)                                             |           | ReadonlyArray&lt;[Link](./models.link.md)<!-- -->&gt; \| undefined      |                                                                          |
| [rootFolder](./models.repository.rootfolder.md)                                       |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [taskProcess](./models.repository.taskprocess.md)                                     |           | [Link](./models.link.md) \| undefined                                   |                                                                          |
| [versionInfo](./models.repository.versioninfo.md)                                     |           | [LimitedVersionInfo](./models.limitedversioninfo.md) \| undefined       |                                                                          |