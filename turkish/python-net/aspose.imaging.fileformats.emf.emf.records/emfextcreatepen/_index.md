---
title: "EmfExtCreatePen Sınıfı"
type: docs
weight: 430
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

**Summary:** The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExtCreatePen()](#EmfExtCreatePen__1) | Yeni bir [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) sınıfının örneğini başlatır. |
| [EmfExtCreatePen(record)](#EmfExtCreatePen_record_2) | Yeni bir [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | İsteğe bağlı bir tampon alır veya ayarlar; bu tampon, WMF DeviceIndependentBitmap nesnesi biçiminde paketlenmiş bir DIB içerir<br/>            ([MS-WMF] bölüm 2.2.2.9). EMR_EXTCREATEPEN kaydının sabit kısmıyla bitişik olması gerekmez. |
| elp | [EmfLogPenEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/) | r/w | LogPenEx nesnesini (bölüm 2.2.20) alır veya ayarlar; bu nesne, isteğe bağlı bir çizgi stili dizisi dahil olmak üzere niteliklere sahip genişletilmiş mantıksal <br/>            kalemi belirtir. |
| ih_pen | int | r/w | Genişletilmiş mantıksal <br/>            kalem nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) dizinini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. <br/>            Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExtCreatePen() {#EmfExtCreatePen__1}


```
 EmfExtCreatePen() 
```

Yeni bir [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) sınıfının örneğini başlatır.

### Constructor: EmfExtCreatePen(record) {#EmfExtCreatePen_record_2}


```
 EmfExtCreatePen(record) 
```

Yeni bir [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kayıt. |

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


