---
title: "EmfCommentWindowsMetaFile"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT_WINDOWS_METAFILE يحدد صورة في ملف WMF ميتافايل مضمّن."
type: docs
weight: 33
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

سجل EMR_COMMENT_WINDOWS_METAFILE يحدد صورة في ملف تعريف WMF مدمج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfCommentWindowsMetaFile`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) | يحصل أو يضبط عددًا صحيحًا غير موقع 16‑بت يحدد إصدار ملف WMF الميتافايل من حيث الدعم للصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion ([MS-WMF] القسم 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | يحصل أو يضبط عددًا صحيحًا غير موقع 16‑بت يحدد إصدار ملف WMF الميتافايل من حيث الدعم للصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion ([MS-WMF] القسم 2.1.1.19). |
| [getChecksum()](#getChecksum--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد قيمة التحقق لهذا السجل. |
| [setChecksum(int value)](#setChecksum-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد قيمة التحقق لهذا السجل. |
| [getFlags()](#getFlags--) | يحصل أو يضبط قيمة 32‑بت يجب أن تكون 0x00000000 ويجب تجاهلها. |
| [setFlags(int value)](#setFlags-int-) | يحصل أو يضبط قيمة 32‑بت يجب أن تكون 0x00000000 ويجب تجاهلها. |
| [getWinMetafileSize()](#getWinMetafileSize--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم ملف WMF الميتافايل بالبايت في حقل WinMetafile. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم ملف WMF الميتافايل بالبايت في حقل WinMetafile. |
| [getWinMetafile()](#getWinMetafile--) | يحصل أو يضبط مخزنًا يحتوي على ملف WMF الميتافايل. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | يحصل أو يضبط مخزنًا يحتوي على ملف WMF الميتافايل. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfCommentWindowsMetaFile`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16‑بت يحدد إصدار ملف WMF الميتافايل من حيث الدعم للصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion ([MS-WMF] القسم 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 16‑بت يحدد إصدار ملف WMF الميتافايل من حيث الدعم للصور النقطية المستقلة عن الجهاز (DIBs)، من تعداد WMF MetafileVersion ([MS-WMF] القسم 2.1.1.19).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد قيمة التحقق لهذا السجل.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد قيمة التحقق لهذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


يحصل أو يضبط قيمة 32‑بت يجب أن تكون 0x00000000 ويجب تجاهلها.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


يحصل أو يضبط قيمة 32‑بت يجب أن تكون 0x00000000 ويجب تجاهلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم ملف WMF الميتافايل بالبايت في حقل WinMetafile.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم ملف WMF الميتافايل بالبايت في حقل WinMetafile.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


يحصل أو يضبط مخزنًا يحتوي على ملف WMF الميتافايل.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


يحصل أو يضبط مخزنًا يحتوي على ملف WMF الميتافايل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

