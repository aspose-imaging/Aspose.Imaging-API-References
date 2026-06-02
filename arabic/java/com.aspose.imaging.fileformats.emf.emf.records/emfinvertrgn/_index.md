---
title: "EmfInvertRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_INVERTRGN يعكس الألوان في المنطقة المحددة."
type: docs
weight: 67
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)، [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

السجل EMR\_INVERTRGN يعكس الألوان في المنطقة المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfInvertRgn`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [getRgnData()](#getRgnData--) | يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfInvertRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

