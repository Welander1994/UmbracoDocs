---
title: CreateDefaultOrderStatusesTask
description: API reference for CreateDefaultOrderStatusesTask in Umbraco Commerce
---
## CreateDefaultOrderStatusesTask

```csharp
public class CreateDefaultOrderStatusesTask : 
    PipelineTaskWithTypedArgsBase<InitStorePipelineArgs, Store>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Store.Tasks](README.md)

### Constructors

#### CreateDefaultOrderStatusesTask

```csharp
public CreateDefaultOrderStatusesTask(IOrderStatusService orderStatusService)
```


### Methods

#### Execute

```csharp
public override PipelineResult<Store> Execute(InitStorePipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
