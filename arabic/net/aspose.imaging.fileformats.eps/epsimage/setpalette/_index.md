---
title: SetPalette
second_title: Aspose.Imaging لمرجع NET API
description: يضبط لوحة الصور .
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.eps/epsimage/setpalette/
---
## EpsImage.SetPalette method

يضبط لوحة الصور .

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| palette | IColorPalette | اللوحة المراد ضبطها. |
| updateColors | Boolean | إذا تم التعيين على`حقيقي`سيتم تحديث الألوان وفقًا للوحة الجديدة ؛ وإلا تظل فهارس اللون دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتلف الصورة عند التحميل إذا لم يكن لبعض الفهارس مدخلات لوحة ألوان مقابلة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotImplementedException | غير صالح للصور المتجهة |

### أنظر أيضا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [EpsImage](../../epsimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Eps](../../epsimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->