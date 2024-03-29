<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ItemsService](./open-api-client.itemsservice.md) &gt; [update](./open-api-client.itemsservice.update.md)

## ItemsService.update() method

Updates an existing item with the specified item URI. This operation returns an instance of 'IdentifiableObject' type, as implemented by one of the following:<ul class="model-list"><li><span>ActivityHistory</span></li><li><span>ActivityInstance</span></li><li><span>ApprovalStatus</span></li><li><span>Batch</span></li><li><span>Bundle</span></li><li><span>BusinessProcessType</span></li><li><span>Category</span></li><li><span>Component</span></li><li><span>ComponentTemplate</span></li><li><span>ExternalCategory</span></li><li><span>ExternalComponent</span></li><li><span>ExternalContainer</span></li><li><span>ExternalKeyword</span></li><li><span>Folder</span></li><li><span>Group</span></li><li><span>Keyword</span></li><li><span>MultimediaType</span></li><li><span>Page</span></li><li><span>PageTemplate</span></li><li><span>ProcessHistory</span></li><li><span>ProcessInstance</span></li><li><span>Publication</span></li><li><span>PublishTransaction</span></li><li><span>Schema</span></li><li><span>SearchFolder</span></li><li><span>StructureGroup</span></li><li><span>TargetGroup</span></li><li><span>TargetType</span></li><li><span>TemplateBuildingBlock</span></li><li><span>TridionActivityDefinition</span></li><li><span>TridionProcessDefinition</span></li><li><span>User</span></li><li><span>WorkItem</span></li></ul>

**Signature:**

```typescript
static update({ escapedItemId, requestModel, }: {
        escapedItemId: string;
        requestModel: IdentifiableObject;
    }): CancelablePromise<IdentifiableObject>;
```

## Parameters

| Parameter                        | Type                                                                                                            | Description |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------- | ----------- |
| { escapedItemId, requestModel, } | { escapedItemId: string; requestModel: [IdentifiableObject](./open-api-client.identifiableobject.md)<!-- -->; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;[IdentifiableObject](./open-api-client.identifiableobject.md)<!-- -->&gt;

IdentifiableObject The request was successful.

## Exceptions

ApiError
