---
title: "EmfPolyTextOutA Sınıfı"
type: docs
weight: 880
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---

**Summary:** The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolyTextOutA()](#EmfPolyTextOutA__1) | Yeni bir [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) sınıfının bir örneğini başlatır. |
| [EmfPolyTextOutA(source)](#EmfPolyTextOutA_source_2) | Yeni bir [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Çıktı dizelerini 8-bit ASCII karakterlerle, metin öznitelikleri ve boşluk değerleriyle belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. <br/>            EmrText nesnelerinin sayısı cStrings tarafından belirlenir. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Aygıt birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. <br/>             |
| ex_scale | float | r/w | Sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. <br/>            Grafik modu GM_COMPATIBLE ise. |
| ey_scale | float | r/w | Sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. <br/>            Grafik modu GM_COMPATIBLE ise. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Geçerli grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar, <br/>            GraphicsMode enumundan (bölüm 2.1.16). |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPolyTextOutA() {#EmfPolyTextOutA__1}


```
 EmfPolyTextOutA() 
```

Yeni bir [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) sınıfının bir örneğini başlatır.

### Constructor: EmfPolyTextOutA(source) {#EmfPolyTextOutA_source_2}


```
 EmfPolyTextOutA(source) 
```

Yeni bir [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) sınıfının bir örneğini başlatır.

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


