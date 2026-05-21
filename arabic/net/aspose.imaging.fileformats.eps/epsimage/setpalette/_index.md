---
title: "EpsImage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة EpsImage. تخصيص لوحات ألوان الصورة لتحقيق أنماط لونية فريدة وتعزيز الجاذبية البصرية. تعديل الألوان لتأثيرات محددة وتحسين جودة الصورة عبر منصات وأجهزة مختلفة بسهولة."
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.eps/epsimage/setpalette/
---
## EpsImage.SetPalette method

خصص لوحات ألوان الصورة لتحقيق مخططات ألوان فريدة وتعزيز الجاذبية البصرية. صمم الألوان لتأثيرات محددة وحسّن جودة الصورة عبر مختلف المنصات والأجهزة بسهولة.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | IColorPalette | لوحة الألوان للتعيين. |
| updateColors | Boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات لوحة ألوان مقابلة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | غير مدعوم من قبل VectorImage |

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


