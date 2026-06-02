---
title: "BigTiffReader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قارئ BigTiff بنظام النهاية الصغرى."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

قارئ BigTiff بنظام النهاية الصغرى.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | يحصل على حجم طول قيمة العلامة. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


ينشئ مثيلاً جديدًا من الفئة [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |
| dataLength | int | طول البيانات. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


يحصل على حجم طول قيمة العلامة.

**Returns:**
بايت - حجم طول قيمة العلامة.
