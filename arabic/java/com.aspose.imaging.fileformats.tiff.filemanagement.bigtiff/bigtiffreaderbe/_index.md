---
title: "BigTiffReaderBE"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كاتب تدفق BigTiff بنظام النهاية الكبيرة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging/fileformats/tiff/filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging/fileformats/tiff/filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

كاتب تدفق BigTiff بنظام النهاية الكبيرة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | يحصل على حجم طول قيمة العلامة. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


يُنشئ مثلاً جديداً من الفئة [BigTiffReaderBE](../../com.aspose.imaging/fileformats/tiff/filemanagement/bigtiff/bigtiffreaderbe).

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
byte - حجم طول قيمة العلامة.
