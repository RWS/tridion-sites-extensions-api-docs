<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [TcmUri](./models.tcmuri.md)

## TcmUri class

Represents a native Tridion Content Manager URI which uniquely identifies a resource in the system.

The structure of a TCM URI is PublicationID-ItemID\[-ItemType\]\[-vVersion\].

**Signature:**

```typescript
export declare class TcmUri
```

## Properties

| Property                                                        | Modifiers           | Type                                                                                                                       | Description |
| --------------------------------------------------------------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [asString](./models.tcmuri.asstring.md)                         |                     | string                                                                                                                     |             |
| [create](./models.tcmuri.create.md)                             | <code>static</code> | (publicationId: number, itemId: number, itemType: TcmUriItemType, itemVersion?: number) =&gt; [TcmUri](./models.tcmuri.md) |             |
| [createPublicationUri](./models.tcmuri.createpublicationuri.md) | <code>static</code> | (publicationId: number) =&gt; [TcmUri](./models.tcmuri.md)                                                                 |             |
| [getPublicationUri](./models.tcmuri.getpublicationuri.md)       |                     | () =&gt; [TcmUri](./models.tcmuri.md)                                                                                      |             |
| [getUriInPublication](./models.tcmuri.geturiinpublication.md)   |                     | (publicationUri: [TcmUri](./models.tcmuri.md)<!-- -->) =&gt; [TcmUri](./models.tcmuri.md)                                  |             |
| [getUriWithVersion](./models.tcmuri.geturiwithversion.md)       |                     | (version: number) =&gt; [TcmUri](./models.tcmuri.md)                                                                       |             |
| [getVersionlessUri](./models.tcmuri.getversionlessuri.md)       |                     | () =&gt; [TcmUri](./models.tcmuri.md)                                                                                      |             |
| [hasVersion](./models.tcmuri.hasversion.md)                     |                     | boolean                                                                                                                    |             |
| [isDynamic](./models.tcmuri.isdynamic.md)                       |                     | boolean                                                                                                                    |             |
| [isEditableVersion](./models.tcmuri.iseditableversion.md)       |                     | boolean                                                                                                                    |             |
| [isNewUri](./models.tcmuri.isnewuri.md)                         |                     | boolean                                                                                                                    |             |
| [isNullUri](./models.tcmuri.isnulluri.md)                       |                     | boolean                                                                                                                    |             |
| [isSystemUri](./models.tcmuri.issystemuri.md)                   |                     | boolean                                                                                                                    |             |
| [itemId](./models.tcmuri.itemid.md)                             |                     | number                                                                                                                     |             |
| [itemType](./models.tcmuri.itemtype.md)                         |                     | TcmUriItemType                                                                                                             |             |
| [null](./models.tcmuri.null.md)                                 | <code>static</code> | [TcmUri](./models.tcmuri.md)                                                                                               |             |
| [parse](./models.tcmuri.parse.md)                               | <code>static</code> | (input: string) =&gt; [TcmUri](./models.tcmuri.md) \| undefined                                                            |             |
| [publicationId](./models.tcmuri.publicationid.md)               |                     | number                                                                                                                     |             |
| [system](./models.tcmuri.system.md)                             | <code>static</code> | [TcmUri](./models.tcmuri.md)                                                                                               |             |
| [version](./models.tcmuri.version.md)                           |                     | number \| undefined                                                                                                        |             |
