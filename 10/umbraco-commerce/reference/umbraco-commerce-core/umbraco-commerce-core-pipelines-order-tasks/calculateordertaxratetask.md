---
title: CalculateOrderTaxRateTask
description: API reference for CalculateOrderTaxRateTask in Umbraco Commerce
---
## CalculateOrderTaxRateTask

```csharp
public class CalculateOrderTaxRateTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Order.Tasks](README.md)

### Constructors

#### CalculateOrderTaxRateTask

The default constructor.

```csharp
public CalculateOrderTaxRateTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
