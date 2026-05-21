---
title: "WmfImage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WmfImage. تطبيق لوحة ألوان محددة على الصورة تمكين تخصيص تمثيل اللون. استخدم هذه الطريقة لتحسين العرض البصري وتحقيق تأثيرات لونية محددة داخل تطبيقك"
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.wmf/wmfimage/setpalette/
---
## WmfImage.SetPalette method

طبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص تمثيل اللون. استخدم هذه الطريقة لتحسين العرض البصري وتحقيق تأثيرات لونية محددة داخل تطبيقك.

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
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


