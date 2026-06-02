---
title: "الفئة WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeviceIndependentBitmap. كائن DeviceIndependentBitmap يحدد صورةً بتنسيق bitmap المستقل عن الجهاز DIB."
type: docs
weight: 8760
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
## WmfDeviceIndependentBitmap class

كائن DeviceIndependentBitmap يعرّف صورة بتنسيق صورة نقطية مستقلة عن الجهاز (DIB).

```csharp
public class WmfDeviceIndependentBitmap : MetaObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfDeviceIndependentBitmap](wmfdeviceindependentbitmap/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/adata/) { get; set; } | يحصل أو يعيّن مصفوفة من البايتات التي تحدد الصورة. يتم تحديد حجم وتنسيق هذه البيانات بواسطة المعلومات الموجودة في حقل DIBHeaderInfo. |
| [CachedImage](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/cachedimage/) { get; set; } | يحصل أو يعيّن صورة الراستر المخزنة مؤقتًا. |
| [ColorsData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/colorsdata/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية إما لكائنات RGBQuad (القسم 2.2.2.20) أو أعداد صحيحة غير موقعة 16‑بت تُحدد جدول ألوان. يجب تحديد حجم ومحتويات هذا الحقل بناءً على سجل الميتافايل أو الكائن الذي يحتوي على هذا DeviceIndependentBitmap ومن المعلومات في حقل DIBHeaderInfo. راجع تعداد ColorUsage (القسم 2.1.1.6) وتعداد BitCount (القسم 2.1.1.3) للحصول على تفاصيل إضافية. |
| [Header](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/header/) { get; set; } | يحصل أو يعيّن إما كائن BitmapCoreHeader (القسم 2.2.2.2) أو كائن BitmapInfoHeader (القسم 2.2.2.3) الذي يحدد معلومات حول الصورة. |

### انظر أيضًا

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


