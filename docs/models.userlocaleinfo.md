<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@tridion-sites/models](./models.md) &gt; [UserLocaleInfo](./models.userlocaleinfo.md)

## UserLocaleInfo class

Represents the information about User locale.

**Signature:**

```typescript
export declare class UserLocaleInfo
```

## Constructors

| Constructor                                                             | Modifiers | Description                                                        |
| ----------------------------------------------------------------------- | --------- | ------------------------------------------------------------------ |
| [(constructor)(backendModel)](./models.userlocaleinfo._constructor_.md) |           | Constructs a new instance of the <code>UserLocaleInfo</code> class |

## Properties

| Property                                                              | Modifiers | Type                                                                  | Description                                                         |
| --------------------------------------------------------------------- | --------- | --------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [\_backendModel](./models.userlocaleinfo._backendmodel.md)            |           | [BackendUserLocaleInfo](./open-api-client.userlocaleinfo.md)          |                                                                     |
| [amDesignator](./models.userlocaleinfo.amdesignator.md)               |           | string                                                                | String designator for hours that are "ante meridiem" (before noon). |
| [dayNames](./models.userlocaleinfo.daynames.md)                       |           | ReadonlyArray&lt;string&gt;                                           | Culture-specific full names of the days of the week.                |
| [fullDateTimeFormat](./models.userlocaleinfo.fulldatetimeformat.md)   |           | string \| undefined                                                   | Custom format string for a long date and long time value.           |
| [getInternalModel](./models.userlocaleinfo.getinternalmodel.md)       |           | () =&gt; [BackendUserLocaleInfo](./open-api-client.userlocaleinfo.md) |                                                                     |
| [longDateFormat](./models.userlocaleinfo.longdateformat.md)           |           | string \| undefined                                                   | Custom format string for a long date value.                         |
| [longTimeFormat](./models.userlocaleinfo.longtimeformat.md)           |           | string \| undefined                                                   | Custom format string for a long time value.                         |
| [monthNames](./models.userlocaleinfo.monthnames.md)                   |           | ReadonlyArray&lt;string&gt;                                           | Culture-specific full names of the months.                          |
| [pmDesignator](./models.userlocaleinfo.pmdesignator.md)               |           | string                                                                | String designator for hours that are "post meridiem" (after noon).  |
| [shortDateFormat](./models.userlocaleinfo.shortdateformat.md)         |           | string \| undefined                                                   | Custom format string for a short date value.                        |
| [shortDateTimeFormat](./models.userlocaleinfo.shortdatetimeformat.md) |           | string \| undefined                                                   | Custom format string for a short date and short time value.         |
| [shortDayNames](./models.userlocaleinfo.shortdaynames.md)             |           | ReadonlyArray&lt;string&gt;                                           | Culture-specific abbreviated names of the days of the week.         |
| [shortestDayNames](./models.userlocaleinfo.shortestdaynames.md)       |           | ReadonlyArray&lt;string&gt;                                           | Shortest unique abbreviated day names.                              |
| [shortMonthNames](./models.userlocaleinfo.shortmonthnames.md)         |           | ReadonlyArray&lt;string&gt;                                           | Culture-specific abbreviated names of the months.                   |
| [shortTimeFormat](./models.userlocaleinfo.shorttimeformat.md)         |           | string \| undefined                                                   | Custom format string for a short time value.                        |
