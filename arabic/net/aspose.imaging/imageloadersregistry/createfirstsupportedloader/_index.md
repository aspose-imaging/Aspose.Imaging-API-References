---
title: CreateFirstSupportedLoader
second_title: Aspose.Imaging لمرجع NET API
description: إنشاء أول محمل يتم العثور عليه مناسبًا لما هو محددstream واختيارياloadOptions .
type: docs
weight: 30
url: /ar/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

إنشاء أول محمل يتم العثور عليه مناسبًا لما هو محدد*stream* واختياريا*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

المُحمل الذي يدعم ملفات*stream* و*loadOptions* أو لاغية إذا لم يتم العثور على هذا المحمل.

### ملاحظات

سيكون المحمل الأول هو آخر محمل مسجل.

### أنظر أيضا

* interface [IImageLoader](../../iimageloader)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* مساحة الاسم [Aspose.Imaging](../../imageloadersregistry)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->