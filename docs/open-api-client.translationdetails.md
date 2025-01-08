<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [TranslationDetails](./open-api-client.translationdetails.md)

## TranslationDetails type

Contains information about the translation state of the Item. Created by calling {<!-- -->M:Tridion.TranslationManager.DomainModel.TmSession.GetTcmItemTranslationInfo(System.String)<!-- -->}<!-- -->.

**Signature:**

```typescript
export type TranslationDetails = {
    CompletedTranslationInfo?: TranslationJobInfo;
    InProgressTranslationInfo?: Array<TranslationJobInfo>;
    SourceItemTitle?: string;
    SourceItemUri?: string;
    SourcePublicationTitle?: string;
    SourcePublicationUri?: string;
    Status?: TranslationStatus;
    TargetItemTitle?: string;
    TargetItemUri?: string;
    TargetPublicationTitle?: string;
    TargetPublicationUri?: string;
};
```

**References:** [TranslationJobInfo](./open-api-client.translationjobinfo.md)<!-- -->, [TranslationStatus](./open-api-client.translationstatus.md)