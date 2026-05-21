---
title: "GraphicsPath.Flatten"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GraphicsPath. تحول كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة"
type: docs
weight: 100
url: /ar/net/aspose.imaging/graphicspath/flatten/
---
## Flatten() {#flatten}

يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten()
```

### انظر أيضًا

* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix) {#flatten_1}

تطبق التحويل المحدد ثم تحول كل منحنى في هذا [`GraphicsPath`](../) إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten(Matrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | Matrix | [`Matrix`](../../matrix/) التي تُستخدم لتحويل هذا [`GraphicsPath`](../) قبل التسوية. |

### انظر أيضًا

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

تحول كل منحنى في هذا [`GraphicsPath`](../) إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | Matrix | [`Matrix`](../../matrix/) التي تُستخدم لتحويل هذا [`GraphicsPath`](../) قبل التسوية. |
| السطحية | فردي | تحدد الحد الأقصى للخطأ المسموح بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد القطع الخطية في التقريب. |

### انظر أيضًا

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


