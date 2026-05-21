---
title: "EmfImage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة EmfImage. تعيين لوحة ألوان الصورة"
type: docs
weight: 130
url: /ar/net/aspose.imaging.fileformats.emf/emfimage/setpalette/
---
## EmfImage.SetPalette method

يضبط لوحة ألوان الصورة.

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
| NotImplementedException |  |

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [EmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../emfimage/)
* assembly [Aspose.Imaging](../../../)


