---
title: ProductAttributeEditDto
description: API reference for ProductAttributeEditDto in Umbraco Commerce
---
## ProductAttributeEditDto

```csharp
public class ProductAttributeEditDto : ProductAttributeDto, IHasPath, INotificationModel
```

**Inheritance**

* class [ProductAttributeDto](productattributedto.md)
* interface [IHasPath](ihaspath.md)

**Namespace**
* [Umbraco.Commerce.Cms.Web.Models](README.md)

### Constructors

#### ProductAttributeEditDto

The default constructor.

```csharp
public ProductAttributeEditDto()
```


### Properties

#### Notifications

```csharp
public List<BackOfficeNotification> Notifications { get; set; }
```


---

#### Path

```csharp
public List<string> Path { get; set; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
