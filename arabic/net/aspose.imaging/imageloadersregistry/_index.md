---
title: "الفئة ImageLoadersRegistry"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageLoadersRegistry. تمثل سجل محملات الصور"
type: docs
weight: 10210
url: /ar/net/aspose.imaging/imageloadersregistry/
---
## ImageLoadersRegistry class

يمثل سجل محمّلي الصور.

```csharp
public static class ImageLoadersRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging/imageloadersregistry/registereddescriptors/) { get; } | يحصل على الوصفيات المسجلة. |
| static [RegisteredFormats](../../aspose.imaging/imageloadersregistry/registeredformats/) { get; } | يحصل على صيغ تحميل الصور المسجلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.imaging/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | ينشئ أول محمل تم العثور عليه المناسب للـ *stream* المحدد واختياريًا *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | يحصل على الوصف المدعوم الأول الموجود المناسب للـ *stream* المحدد واختياريًا *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | يحصل على أول صيغة ملف مدعومة حسب اسم النوع. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول وصف مدعوم حسب اسم النوع. |
| static [Register](../../aspose.imaging/imageloadersregistry/register/)(IImageLoaderDescriptor) | يسجل الوصف المحدد لمحمل الصورة. |
| static [RegisterLoader](../../aspose.imaging/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | يسجل المحمل. |
| static [UnregisterLoader](../../aspose.imaging/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | يلغي تسجيل المحمل. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


