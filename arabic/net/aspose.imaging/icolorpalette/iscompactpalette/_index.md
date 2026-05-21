---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية IColorPalette. يحصل على قيمة تشير إلى ما إذا كانت اللوحة المدمجة مستخدمة"
type: docs
weight: 40
url: /ar/net/aspose.imaging/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

يحصل على قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مدمجة.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` إذا تم استخدام لوحة ألوان مدمجة؛ وإلا `false`.

## ملاحظات

تعني لوحة الألوان المدمجة أن الصورة ستحوي فقط إدخالات لوحة الألوان المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر تجميعًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel إدخالًا وستحجز الصورة مساحة أكبر لجميع إدخالات لوحة الألوان الممكنة. ضبط هذه القيمة إلى true وتغيير إدخالات لوحة الألوان قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.

### انظر أيضًا

* interface [IColorPalette](../)
* namespace [Aspose.Imaging](../../icolorpalette/)
* assembly [Aspose.Imaging](../../../)


