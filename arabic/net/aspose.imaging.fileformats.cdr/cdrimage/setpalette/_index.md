---
title: "CdrImage.SetPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CdrImage. خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تطبيق أنماط ألوان محددة أو تعديلات بشكل ديناميكي لضمان تحكم دقيق في المظهر البصري لصورهم"
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimage/setpalette/
---
## CdrImage.SetPalette method

خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تطبيق أنظمة ألوان محددة أو تعديلات بشكل ديناميكي، مما يضمن تحكمًا دقيقًا في المظهر البصري لصورهم.

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
* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


