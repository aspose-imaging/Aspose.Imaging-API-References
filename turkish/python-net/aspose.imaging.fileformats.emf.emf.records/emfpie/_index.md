---
title: "EmfPie Sınıfı"
type: docs
weight: 730
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Yeni bir [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) sınıfının örneğini başlatır. |
| [EmfPie(source)](#EmfPie_source_2) | Yeni bir [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | [MS-WMF] bölüm 2.2.2.19'da belirtilen 128-bit WMF RectL nesnesini alır veya ayarlar, bu <br/>            kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirtir. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | İkinci radyalın <br/>            son noktasının mantıksal birimlerdeki koordinatlarını belirten 64-bit PointL nesnesini alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | İlk radyalın son noktasının mantıksal birimlerdeki koordinatlarını belirten, [MS-WMF] bölüm 2.2.2.15'te tanımlanan 64-bit WMF PointL nesnesini alır veya ayarlar.<br/> |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Yeni bir [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) sınıfının örneğini başlatır.

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Yeni bir [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kaynak. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kaynak. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Kayıt türü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


