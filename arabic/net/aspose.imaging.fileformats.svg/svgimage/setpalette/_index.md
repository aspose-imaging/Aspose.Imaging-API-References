---
title: "SvgImage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة SvgImage. تُطبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص مخططات الألوان لأغراض جمالية أو وظيفية. توفر هذه الطريقة مرونة في إدارة لوحات الألوان لتلبية متطلبات التصميم أو التطبيق المختلفة."
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.svg/svgimage/setpalette/
---
## SvgImage.SetPalette method

يطبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص مخططات الألوان لأغراض جمالية أو وظيفية. توفر هذه الطريقة مرونة في إدارة لوحات الألوان لتلبية متطلبات التصميم أو التطبيق المختلفة.

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
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


