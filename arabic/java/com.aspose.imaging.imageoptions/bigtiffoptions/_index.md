---
title: "BigTiffOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لإنشاء صيغة صورة BigTIFF النقطية مصممة خصيصًا لتلبية المتطلبات الفريدة للتطبيقات التي تستخدم بيانات تصويرية واسعة النطاق من الماسحات الضوئية."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

تم تصميم واجهة برمجة التطبيقات لإنشاء تنسيق صورة نقطية BigTIFF خصيصًا لتلبية المتطلبات الفريدة للتطبيقات التي تستخدم بيانات تصويرية واسعة النطاق من الماسحات الضوئية. تُسهل هذه الواجهة توليد تنسيق BigTIFF بسلاسة، الذي يجمع عدة صور TIFF في صورة واحدة شاملة. تضمن معالجة فعّالة للبيانات التصويرية الضخمة، مما يوفّر للمطورين أداة قوية لإنشاء ومعالجة تنسيقات عالية الدقة ومتعددة الصور.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينسخ هذه النسخة. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). بشكل افتراضي يتم استخدام نظام النهاية الصغرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف Tiff المتوقع. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | مصدر الخيارات. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات لتهيئة الخيارات. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


يُنشئ مثيلاً جديدًا من الفئة [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف Tiff المتوقع. |
| byteOrder | int | ترتيب بايت لتنسيق ملف tiff المراد استخدامه. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


ينسخ هذه النسخة.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
