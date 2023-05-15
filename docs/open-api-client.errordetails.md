<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [ErrorDetails](./open-api-client.errordetails.md)

## ErrorDetails type

Provides details for errors occuring while sending or retrieving {<!-- -->Tridion.TranslationManager.OpenApi.V2.Dto.TranslationJob<!-- -->}<!-- -->s.

**Signature:**

```typescript
export type ErrorDetails = {
    ExceptionDetails?: ExceptionDetails;
    JobId?: number;
    JobTitle?: string;
    Severity?: ErrorSeverity;
    SourceLanguageId?: string;
    TargetLanguageId?: string;
    TcmItemCurrentTargetTitle?: string;
    TcmItemNewTargetTitle?: string;
    TcmItemSourceTitle?: string;
    TcmItemSourceUri?: string;
    TcmItemTargetUri?: string;
    TmsItemId?: string;
    TmsJobId?: string;
};
```

**References:** [ExceptionDetails](./open-api-client.exceptiondetails.md)<!-- -->, [ErrorSeverity](./open-api-client.errorseverity.md)