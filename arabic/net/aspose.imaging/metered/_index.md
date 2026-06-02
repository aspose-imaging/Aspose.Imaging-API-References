---
title: "فئة Metered"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Metered. توفر طرقًا محسوبة للتكامل"
type: docs
weight: 11150
url: /ar/net/aspose.imaging/metered/
---
## Metered class

يوفر طرقًا محسوبة للتكامل

توفر طرقًا لتعيين المفتاح المحسوب.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.imaging/metered/equals/)(object) | يحدد ما إذا كان الكائن المحدد مساويًا لهذه المثيلة. |
| [SetMeteredKey](../../aspose.imaging/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص المحسوب. إذا قمت بشراء ترخيص محسوب، عند بدء التطبيق، يجب استدعاء هذه API، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوزت 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه API مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.imaging/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.imaging/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |

## أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المحسوب

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


