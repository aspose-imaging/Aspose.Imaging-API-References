---
title: "EmfRegionData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن RegionData يحدد البيانات التي تُعرّف منطقة مكوّنة من مستطيلات غير متداخلة."
type: docs
weight: 33
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

كائن RegionData يحدد البيانات التي تعرف منطقة، والتي تتكون من مستطيلات غير متداخلة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | يُهيئ نسخة جديدة من الفئة `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | يُهيئ نسخة جديدة من الفئة `EmfRegionData`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | يحصل على كائن RegionDataHeader بحجم 256 بت يصف البيانات التالية. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | يضبط كائن RegionDataHeader بحجم 256 بت يصف البيانات التالية. |
| [getData()](#getData--) | يحصل على مصفوفة من كائنات WMF RectL ([MS-WMF] القسم 2.2.2.19)؛ يتم دمج الكائنات لإنشاء المنطقة |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | يضبط مصفوفة من كائنات WMF RectL ([MS-WMF] القسم 2.2.2.19)؛ يتم دمج الكائنات لإنشاء المنطقة |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


يُهيئ نسخة جديدة من الفئة `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


يُهيئ نسخة جديدة من الفئة `EmfRegionData`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


يحصل على كائن RegionDataHeader بحجم 256 بت يصف البيانات التالية.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


يضبط كائن RegionDataHeader بحجم 256 بت يصف البيانات التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


يحصل على مصفوفة من كائنات WMF RectL ([MS-WMF] القسم 2.2.2.19)؛ يتم دمج الكائنات لإنشاء المنطقة

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


يضبط مصفوفة من كائنات WMF RectL ([MS-WMF] القسم 2.2.2.19)؛ يتم دمج الكائنات لإنشاء المنطقة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

