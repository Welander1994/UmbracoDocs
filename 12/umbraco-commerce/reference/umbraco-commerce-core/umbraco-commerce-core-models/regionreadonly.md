---
title: RegionReadOnly
description: API reference for RegionReadOnly in Umbraco Commerce
---
## RegionReadOnly

```csharp
public class RegionReadOnly : StoreAggregateBase<RegionReadOnly, Region, RegionState>, IHasName
```

**Inheritance**

* class [StoreAggregateBase&lt;TReadOnlySelf,TWritableSelf,TState&gt;](storeaggregatebase-3.md)
* interface [IHasName](ihasname.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Properties

#### Code

```csharp
public string Code { get; }
```


---

#### CountryId

```csharp
public Guid CountryId { get; }
```


---

#### DefaultPaymentMethodId

```csharp
public Guid? DefaultPaymentMethodId { get; }
```


---

#### DefaultShippingMethodId

```csharp
public Guid? DefaultShippingMethodId { get; }
```


---

#### IsDeleted

```csharp
public bool IsDeleted { get; }
```


---

#### Name

```csharp
public string Name { get; }
```


---

#### SortOrder

```csharp
public int SortOrder { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
