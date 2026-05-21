---
title: "GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifBlocksRegistry. تقوم بتحميل كتلة GIF باستخدام أول مُفتاح تم العثور عليه ومناسب للتدفق المحدد"
type: docs
weight: 40
url: /ar/net/aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/
---
## GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor method

يقوم بتحميل كتلة GIF باستخدام أول مفتاح تم العثور عليه مناسب لـ *stream* المحدد.

```csharp
public static IGifBlock LoadBlockByFirstSupportedDescriptor(Stream stream, 
    IColorPalette containerPalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| containerPalette | IColorPalette | لوحة ألوان الحاوية. |

### قيمة الإرجاع

كتلة GIF المحمَّلة أو null إذا لم يُعثر على أي مُفتاح.

## ملاحظات

سيكون أول مُفتاح هو في الواقع الأخير المسجَّل.

### انظر أيضًا

* interface [IGifBlock](../../igifblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifBlocksRegistry](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry/)
* assembly [Aspose.Imaging](../../../)


