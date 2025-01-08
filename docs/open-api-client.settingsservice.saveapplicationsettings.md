<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/open-api-client](./open-api-client.md) &gt; [SettingsService](./open-api-client.settingsservice.md) &gt; [saveApplicationSettings](./open-api-client.settingsservice.saveapplicationsettings.md)

## SettingsService.saveApplicationSettings() method

Saves application settings with specified application Id

**Signature:**

```typescript
static saveApplicationSettings({ applicationId, applicationSettings, }: {
        applicationId: string;
        applicationSettings: Settings;
    }): CancelablePromise<void>;
```

## Parameters

| Parameter                               | Type                                                                                               | Description |
| --------------------------------------- | -------------------------------------------------------------------------------------------------- | ----------- |
| { applicationId, applicationSettings, } | { applicationId: string; applicationSettings: [Settings](./open-api-client.settings.md)<!-- -->; } |             |

**Returns:**

[CancelablePromise](./open-api-client.cancelablepromise.md)<!-- -->&lt;void&gt;

void

## Exceptions

ApiError