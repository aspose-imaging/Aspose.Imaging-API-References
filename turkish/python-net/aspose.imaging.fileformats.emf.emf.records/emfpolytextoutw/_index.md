---
title: "EmfPolyTextOutW Sınıfı"
type: docs
weight: 890
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

**Summary:** The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolyTextOutW()](#EmfPolyTextOutW__1) | Yeni bir [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) sınıfı örneği başlatır. |
| [EmfPolyTextOutW(source)](#EmfPolyTextOutW_source_2) | Yeni bir [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Aygıt birimlerinde sınırlayıcı dikdörtgeni belirten bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. <br/>             |
| ex_scale | float | r/w | Sayfa birimlerinden .01mm birimlerine X ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. <br/>            Grafik modu GM_COMPATIBLE ise. |
| ey_scale | float | r/w | Sayfa birimlerinden .01mm birimlerine Y ölçeğini belirten 32 bit kayan nokta değerini alır veya ayarlar. <br/>            Grafik modu GM_COMPATIBLE ise. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Geçerli grafik modunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar, <br/>            GraphicsMode enumundan (bölüm 2.1.16). |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| w_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Çıktı <br/>            dizelerini 16-bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve boşluk değerleriyle belirten EmrText nesnelerinin (bölüm 2.2.5) bir dizisini alır veya ayarlar. EmrText nesnelerinin <br/>            sayısı cStrings tarafından belirtilir. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPolyTextOutW() {#EmfPolyTextOutW__1}


```
 EmfPolyTextOutW() 
```

Yeni bir [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) sınıfı örneği başlatır.

### Constructor: EmfPolyTextOutW(source) {#EmfPolyTextOutW_source_2}


```
 EmfPolyTextOutW(source) 
```

Yeni bir [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) sınıfı örneği başlatır.

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


