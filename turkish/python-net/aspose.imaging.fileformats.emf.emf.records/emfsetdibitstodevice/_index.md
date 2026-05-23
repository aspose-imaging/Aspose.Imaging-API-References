---
title: "EmfSetDiBitsToDevice Sınıfı"
type: docs
weight: 1150
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

**Summary:** The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSetDiBitsToDevice(source)](#EmfSetDiBitsToDevice_source_1) | Yeni bir [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) bu nesne hedef sınırlayıcı dikdörtgeni cihaz birimlerinde tanımlar.<br/>             |
| c_scans | int | r/w | Tarama satırı sayısını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| cx_src | int | r/w | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten bir 32-bit işaretli tamsayıyı alır veya ayarlar. |
| cy_src | int | r/w | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmap'i içeren bir tampon alır veya ayarlar; bu tamponun EMR_SETDIBITSTODEVICE kaydının sabit kısmıyla <br/>            bitişik olması gerekmez. Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST yok sayılmalıdır. |
| start_scan | int | r/w | Dizideki ilk tarama satırını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır. |
| x_dest | int | r/w | Üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin sol-alt <br/>            köşesinin piksel cinsinden x-koordinatını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
| y_dest | int | r/w | Hedef dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin sol-alt <br/>            köşesinin piksel cinsinden y-koordinatını belirten 32 bit işaretli tamsayıyı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSetDiBitsToDevice(source) {#EmfSetDiBitsToDevice_source_1}


```
 EmfSetDiBitsToDevice(source) 
```

Yeni bir [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) sınıfı örneği başlatır.

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


