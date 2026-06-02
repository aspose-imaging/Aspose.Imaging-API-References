---
title: "EmfCreateMonoBrush Sınıfı"
type: docs
weight: 300
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

**Summary:** The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCreateMonoBrush(source)](#EmfCreateMonoBrush_source_1) | Yeni bir [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Paketlenmiş bir DIB'i WMF<br/>            DeviceIndependentBitmap nesnesi ([MS-WMF] bölüm 2.2.2.9) biçiminde içeren bir tamponu alır veya ayarlar. Bunun<br/>            EMR_CREATEDIBPATTERNBRUSHPT kaydının sabit kısmıyla bitişik olması gerekmez. |
| ih_brush | int | r/w | EMF Nesne Tablosundaki (bölüm 3.1.1.1) monokrom<br/>            desen fırça nesnesinin dizinini belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilmesi için KAYDEDİLMELİDİR.<br/>             |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Renk<br/>            tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer DIBColors sayımında (bölüm 2.1.9) bulunmalıdır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCreateMonoBrush(source) {#EmfCreateMonoBrush_source_1}


```
 EmfCreateMonoBrush(source) 
```

Yeni bir [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/) sınıfının bir örneğini başlatır.

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


