---
title: OrderNotificationEventBase<TOrder>
description: API reference for OrderNotificationEventBase<TOrder> in Umbraco Commerce
---
## OrderNotificationEventBase&lt;TOrder&gt;

```csharp
public abstract class OrderNotificationEventBase<TOrder> : NotificationEventBase
    where TOrder : OrderReadOnly
```

**Inheritance**

* class [NotificationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/notificationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderNotificationEventBase&lt;TOrder&gt;

```csharp
public OrderNotificationEventBase(TOrder order)
```


### Properties

#### Order

```csharp
public TOrder Order { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
