---
title: "Image.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تعين لوحة ألوان الصورة"
type: docs
weight: 320
url: /ar/net/aspose.imaging/image/setpalette/
---
## Image.SetPalette method

يضبط لوحة ألوان الصورة.

```csharp
public abstract void SetPalette(IColorPalette palette, bool updateColors)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | IColorPalette | لوحة الألوان للتعيين. |
| updateColors | Boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات لوحة ألوان مقابلة. |

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


