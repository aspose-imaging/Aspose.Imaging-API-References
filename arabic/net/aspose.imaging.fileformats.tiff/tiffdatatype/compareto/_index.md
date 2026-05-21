---
title: "TiffDataType.CompareTo"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffDataType. تقارن المثيلة الحالية مع كائن آخر من نفس النوع وتُرجع عددًا صحيحًا يشير إلى ما إذا كانت المثيلة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.tiff/tiffdatatype/compareto/
---
## TiffDataType.CompareTo method

يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

```csharp
public int CompareTo(object obj)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | Object | كائن للمقارنة مع هذه المثيلة. |

### قيمة الإرجاع

عدد صحيح موقع 32‑بت يشير إلى الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها المعاني التالية: القيمة المعنى أقل من الصفر هذه المثيلة أقل من *obj*. صفر هذه المثيلة مساوية لـ *obj*. أكبر من الصفر هذه المثيلة أكبر من *obj*.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | النوع المتوقع هو TiffDataType. |

### انظر أيضًا

* class [TiffDataType](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffdatatype/)
* assembly [Aspose.Imaging](../../../)


