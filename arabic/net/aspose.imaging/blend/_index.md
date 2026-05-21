---
title: "الفئة Blend"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Blend. تحدد نمط مزج. لا يمكن وراثة هذه الفئة"
type: docs
weight: 120
url: /ar/net/aspose.imaging/blend/
---
## Blend class

يحدد نمط المزج. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class Blend
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Blend](blend/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `Blend`. سيكون عدد العناصر في مصفوفات العامل والمزج مساويًا لـ 1. |
| [Blend](blend/#constructor_1)(int) | يُنشئ مثيلًا جديدًا من الفئة `Blend` بالعدد المحدد من العوامل والمواضع. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Factors](../../aspose.imaging/blend/factors/) { get; set; } | يحصل أو يعيّن مصفوفة عوامل المزج للتدرج. |
| [Positions](../../aspose.imaging/blend/positions/) { get; set; } | يحصل أو يعيّن مصفوفة مواضع المزج للتدرج. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging/blend/equals/)(object) | يختبر ما إذا كان الكائن المحدد هو فئة `Blend` ومكافئ لهذه الفئة `Blend`. |
| override [GetHashCode](../../aspose.imaging/blend/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |

## ملاحظات

الاستخدام النموذجي لفئة المزج هو تعريف نمط مزج للفرشاة. وبالتالي يجب تهيئة خصائص المزج بعناية. لا يُسمح بالمصفوفات الفارغة. ستطلق الفرشاة الاستثناء المناسب إذا كانت مصفوفة عوامل المزج أو مواضعها فارغة أو إذا لم يكن طولها متساويًا. إذا كان هناك عنصران أو أكثر في مصفوفة المواضع، يجب أن يكون العنصر الأول 0 والأخير 1.

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


