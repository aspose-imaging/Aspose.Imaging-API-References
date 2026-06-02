---
title: "الفئة GifBlocksRegistry"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Gif.GifBlocksRegistry. تمثل سجل مُفتاحي كتل الـ GIF."
type: docs
weight: 6790
url: /ar/net/aspose.imaging.fileformats.gif/gifblocksregistry/
---
## GifBlocksRegistry class

يمثل سجل مُفتحات كتل gif.

```csharp
public static class GifBlocksRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging.fileformats.gif/gifblocksregistry/registereddescriptors/) { get; } | يحصل على الوصفيات المسجلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/)(Stream) | يحصل على أول موصّف للمفتاح المدعوم. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول وصف مدعوم حسب اسم النوع. |
| static [LoadBlockByFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/)(Stream, IColorPalette) | يقوم بتحميل كتلة GIF باستخدام أول مفتاح تم العثور عليه مناسب لـ *stream* المحدد. |
| static [RegisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/registeropener/)(IGifBlockLoaderDescriptor) | يسجّل المفتاح. |
| static [UnregisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/unregisteropener/)(IGifBlockLoaderDescriptor) | يلغي تسجيل المفتاح. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)


