---
title: "EmfSmallTextOut Sınıfı"
type: docs
weight: 1380
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Yeni bir örnek başlatır [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) sınıfını. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Alır veya ayarlar isteğe bağlı, 128-bit WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) cihaz birimlerinde sınırlayıcı<br/>            dikdörtgeni belirten. |
| c_chars | int | r/w | Alır veya ayarlar 32-bit işaretsiz tam sayıyı, dizedeki 16-bit karakter sayısını belirten<br/>            . Dize NULL ile sonlandırılMAMIŞTIR. |
| ex_scale | float | r/w | Alır veya ayarlar 32-bit kayan nokta değerini, metni x yönünde ne kadar ölçekleyeceğini belirten. |
| ey_scale | float | r/w | Alır veya ayarlar 32-bit kayan nokta değerini, metni y yönünde ne kadar ölçekleyeceğini belirten. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Alır veya ayarlar kullanılacak metin çıkış seçeneklerini belirten 32-bit işaretsiz tam sayıyı. Bu<br/>            seçenekler ExtTextOutOptions sayımından (bölüm 2.1.11) bir veya birden fazla değer kombinasyonu ile belirlenir. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Alır veya ayarlar grafik modunu belirten 32-bit işaretsiz tam sayıyı, GraphicsMode sayımından (bölüm 2.1.16) alınan.<br/>             |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| text_string | string | r/w | Alır veya ayarlar çizilecek metin dizesini içeren değişken uzunlukta bir dizeyi, 8-bit veya 16-bit karakter kodlarından birinde, fuOptions alanının değerine göre.<br/>             |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| x | int | r/w | Alır veya ayarlar dizeyi yerleştirilecek x koordinatını belirten 32-bit işaretli tam sayıyı. |
| y | int | r/w | Alır veya ayarlar dizeyi yerleştirilecek y koordinatını belirten 32-bit işaretli tam sayıyı. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Yeni bir örnek başlatır [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) sınıfını.

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


