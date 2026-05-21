---
title: "CdrImagePage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CdrImagePage. تُحدد لوحة ألوان الصورة"
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimagepage/setpalette/
---
## CdrImagePage.SetPalette method

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
| NotImplementedException | NotImplementedException |

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [CdrImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage/)
* assembly [Aspose.Imaging](../../../)


