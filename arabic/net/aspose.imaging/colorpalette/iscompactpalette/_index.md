---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ColorPalette. يحصل أو يعيّن قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة"
type: docs
weight: 60
url: /ar/net/aspose.imaging/colorpalette/iscompactpalette/
---
## ColorPalette.IsCompactPalette property

يحصل أو يعيّن قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` إذا تم استخدام لوحة ألوان مدمجة؛ وإلا `false`.

## ملاحظات

تعني لوحة الألوان المدمجة أن الصورة ستحوي فقط إدخالات لوحة الألوان المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر تجميعًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel إدخالًا وستحجز الصورة مساحة أكبر لجميع إدخالات لوحة الألوان الممكنة. ضبط هذه القيمة إلى true وتغيير إدخالات لوحة الألوان قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.

### انظر أيضًا

* class [ColorPalette](../)
* namespace [Aspose.Imaging](../../colorpalette/)
* assembly [Aspose.Imaging](../../../)


