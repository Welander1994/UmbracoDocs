---
title: ResovleOrderCalculationDependenciesTask
description: API reference for ResovleOrderCalculationDependenciesTask in Umbraco Commerce
---
## ResovleOrderCalculationDependenciesTask

```csharp
public class ResovleOrderCalculationDependenciesTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelinetaskwithtypedargsbase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.Order.Tasks](README.md)

### Constructors

#### ResovleOrderCalculationDependenciesTask

```csharp
public ResovleOrderCalculationDependenciesTask(IStoreService storeService, 
    ICurrencyService currencyService, ITaxService taxService, ICountryService countryService, 
    IPaymentMethodService paymentMethodService, IShippingMethodService shippingMethodService, 
    ITaxSourceFactory taxSourceFactory)
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
