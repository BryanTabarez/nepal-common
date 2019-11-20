<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@al/common](./common.md) &gt; [AlLocation](./common.allocation.md)

## AlLocation class

AlLocationType is an enumeration of different location types, each corresponding to a specific application. Each type is presumed to have a single unique instance inside a given environment and residency.

<b>Signature:</b>

```typescript
export declare class AlLocation 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [AccountsUI](./common.allocation.accountsui.md) | <code>static</code> | <code>string</code> |  |
|  [Auth0](./common.allocation.auth0.md) | <code>static</code> | <code>string</code> |  |
|  [ConfigurationUI](./common.allocation.configurationui.md) | <code>static</code> | <code>string</code> |  |
|  [DashboardsUI](./common.allocation.dashboardsui.md) | <code>static</code> | <code>string</code> |  |
|  [DisputesUI](./common.allocation.disputesui.md) | <code>static</code> | <code>string</code> |  |
|  [EndpointsAPI](./common.allocation.endpointsapi.md) | <code>static</code> | <code>string</code> |  |
|  [EndpointsUI](./common.allocation.endpointsui.md) | <code>static</code> | <code>string</code> |  |
|  [ExposuresUI](./common.allocation.exposuresui.md) | <code>static</code> | <code>string</code> |  |
|  [Fino](./common.allocation.fino.md) | <code>static</code> | <code>string</code> | Miscellaneous/External Resources |
|  [GestaltAPI](./common.allocation.gestaltapi.md) | <code>static</code> | <code>string</code> |  |
|  [GlobalAPI](./common.allocation.globalapi.md) | <code>static</code> | <code>string</code> | API Stacks |
|  [HealthUI](./common.allocation.healthui.md) | <code>static</code> | <code>string</code> |  |
|  [HudUI](./common.allocation.hudui.md) | <code>static</code> | <code>string</code> |  |
|  [IncidentsUI](./common.allocation.incidentsui.md) | <code>static</code> | <code>string</code> |  |
|  [InsightAPI](./common.allocation.insightapi.md) | <code>static</code> | <code>string</code> |  |
|  [InsightBI](./common.allocation.insightbi.md) | <code>static</code> | <code>string</code> |  |
|  [IntegrationsUI](./common.allocation.integrationsui.md) | <code>static</code> | <code>string</code> |  |
|  [IntelligenceUI](./common.allocation.intelligenceui.md) | <code>static</code> | <code>string</code> |  |
|  [IrisUI](./common.allocation.irisui.md) | <code>static</code> | <code>string</code> |  |
|  [LandscapeUI](./common.allocation.landscapeui.md) | <code>static</code> | <code>string</code> |  |
|  [LegacyUI](./common.allocation.legacyui.md) | <code>static</code> | <code>string</code> | Modern UI Nodes |
|  [OverviewUI](./common.allocation.overviewui.md) | <code>static</code> | <code>string</code> |  |
|  [RemediationsUI](./common.allocation.remediationsui.md) | <code>static</code> | <code>string</code> |  |
|  [SearchUI](./common.allocation.searchui.md) | <code>static</code> | <code>string</code> |  |
|  [SecurityContent](./common.allocation.securitycontent.md) | <code>static</code> | <code>string</code> |  |
|  [Segment](./common.allocation.segment.md) | <code>static</code> | <code>string</code> |  |
|  [SupportPortal](./common.allocation.supportportal.md) | <code>static</code> | <code>string</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [uiNode(locTypeId, appCode, devPort)](./common.allocation.uinode.md) | <code>static</code> | Generates location type definitions for residency-specific prod, integration, and dev versions of a UI |
