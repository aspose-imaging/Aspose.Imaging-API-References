---
title: "EmfExtTextOutW Sınıfı"
type: docs
weight: 480
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---

**Summary:** The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExtTextOutW()](#EmfExtTextOutW__1) | Yeni bir [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) sınıf örneği başlatır. |
| [EmfExtTextOutW(source)](#EmfExtTextOutW_source_2) | Yeni bir [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Bir WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. Kullanılmaz ve <br/>            alındığında YOK SAYILMALIDIR. |
| ex_scale | float | r/w | Sayfa uzayı birimlerinden .01mm birimlerine dönüştürmek için X ekseni boyunca <br/>            ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar. Bu, iGraphicsMode tarafından belirtilen grafik modu GM_COMPATIBLE ise kullanılmalıdır. |
| ey_scale | float | r/w | Sayfa uzayı birimlerinden .01mm birimlerine dönüştürmek için Y ekseni boyunca <br/>            ölçek faktörünü belirten 32 bit kayan nokta değerini alır veya ayarlar. Bu, iGraphicsMode tarafından belirtilen grafik modu GM_COMPATIBLE ise kullanılmalıdır. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | GraphicsMode sayımından (bölüm 2.1.16) grafik modunu belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| w_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | 16-bit Unicode UTF16-LE karakterlerinde, metin öznitelikleri ve aralık değerleriyle birlikte çıkış dizesini belirten bir EmrText nesnesini alır veya ayarlar (bölüm 2.2.5). |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExtTextOutW() {#EmfExtTextOutW__1}


```
 EmfExtTextOutW() 
```

Yeni bir [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) sınıf örneği başlatır.

### Constructor: EmfExtTextOutW(source) {#EmfExtTextOutW_source_2}


```
 EmfExtTextOutW(source) 
```

Yeni bir [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) sınıf örneği başlatır.

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


