---
title: "تعداد WmfFontQuality"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfFontQuality enum. يحدد تعداد FontQuality مدى قرب تطابق سمات الخط المنطقي مع سمات الخط الفيزيائي عند عرض النص"
type: docs
weight: 8360
url: /ar/net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

يحدد تعداد FontQuality مدى قرب تطابق خصائص الخط المنطقي مع خصائص الخط الفعلي عند عرض النص.

```csharp
public enum WmfFontQuality : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Default | `0` | يحدد أن جودة الأحرف للخط غير مهمة، لذا يمكن استخدام DRAFT. |
| Draft | `1` | يحدد أن جودة الأحرف للخط أقل أهمية من مطابقة السمات المنطقية. بالنسبة للخطوط rasterized، يجب أن يكون التحجيم SHOULD مُمكّنًا، مما يعني توفر أحجام خطوط أكثر. |
| Proof | `2` | يحدد أن جودة الأحرف للخط أكثر أهمية من مطابقة السمات المنطقية. بالنسبة للخطوط rasterized، يجب أن يكون التحجيم SHOULD معطَّلًا، ويجب اختيار الخط الأقرب في الحجم SHOULD. |
| Nonantialiased | `3` | يحدد أنه SHOULD NOT يتم استخدام مضاد التعرج عند عرض النص. |
| Antialiased | `4` | يحدد أنه SHOULD يتم استخدام مضاد التعرج عند عرض النص، إذا كان الخط يدعم ذلك. |
| Cleartype | `5` | يحدد أنه SHOULD يتم استخدام مضاد التعرج ClearType عند عرض النص، إذا كان الخط يدعم ذلك. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


