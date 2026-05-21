---
title: "فئة ImageExportersRegistry"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.ImageExportersRegistry فئة. تمثّل سجل مُصدّري الصور"
type: docs
weight: 9900
url: /ar/net/aspose.imaging/imageexportersregistry/
---
## ImageExportersRegistry class

يمثل سجل مصدري الصور.

```csharp
public static class ImageExportersRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.imaging/imageexportersregistry/registeredexporterdescriptors/) { get; } | يحصل على أوصاف المُصدّر المسجّلة. |
| static [RegisteredFormats](../../aspose.imaging/imageexportersregistry/registeredformats/) { get; } | يحصل على صيغ التصدير المسجّلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.imaging/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | ينشئ أول مُصدّر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| static [Register](../../aspose.imaging/imageexportersregistry/register/)(IImageExporterDescriptor) | يسجّل وصف مُصدّر الصور المحدد. |
| static [RegisterExporter](../../aspose.imaging/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | يسجّل المُصدّر. |
| static [UnregisterExporter](../../aspose.imaging/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | يلغي تسجيل المُصدّر. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


