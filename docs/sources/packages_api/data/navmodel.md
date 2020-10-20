+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "NavModel"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## NavModel interface

Interface used to describe different kinds of page titles and page navigation. Navmodels are usually generated in the backend and stored in Redux.

<b>Signature</b>

```typescript
export interface NavModel 
```
<b>Import</b>

```typescript
import { NavModel } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [breadcrumbs](#breadcrumbs-property) | <code>NavModelItem[]</code> | Describes breadcrumbs that are used in places such as data source settings., folder page and plugins page. |
|  [main](#main-property) | <code>NavModelItem</code> | Main page. that wraps the navigation. Generate the <code>children</code> property generate tabs when used with the Page component. |
|  [node](#node-property) | <code>NavModelItem</code> | This is the current active tab/navigation. |

### breadcrumbs property

Describes breadcrumbs that are used in places such as data source settings., folder page and plugins page.

<b>Signature</b>

```typescript
breadcrumbs?: NavModelItem[];
```

### main property

Main page. that wraps the navigation. Generate the `children` property generate tabs when used with the Page component.

<b>Signature</b>

```typescript
main: NavModelItem;
```

### node property

This is the current active tab/navigation.

<b>Signature</b>

```typescript
node: NavModelItem;
```