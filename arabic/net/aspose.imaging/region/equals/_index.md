---
title: "Region.Equals"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Region. تحقق ما إذا كانت الكائنات متساوية"
type: docs
weight: 40
url: /ar/net/aspose.imaging/region/equals/
---
## Equals(object) {#equals_1}

تحقق مما إذا كانت الكائنات متساوية.

```csharp
public override bool Equals(object obj)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | Object | الكائن الآخر. |

### قيمة الإرجاع

نتيجة مقارنة المساواة.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)

---

## Equals(Region, Graphics) {#equals}

تختبر ما إذا كان الـ[`Region`](../) المحدد مطابقًا لهذا [`Region`](../) على سطح الرسم المحدد.

```csharp
public bool Equals(Region region, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| region | Region | الـ[`Region`](../) للاختبار. |
| g | Graphics | كائن [`Graphics`](../../graphics/) يمثل سطح رسم. |

### قيمة الإرجاع

True إذا كان داخل المنطقة مطابقًا لداخل هذه المنطقة عندما يُطبق التحويل المرتبط بالمعامل *g*؛ وإلا، false.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *g *or* region* هو null. |

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.Imaging](../../region/)
* assembly [Aspose.Imaging](../../../)


