---
title: "EmfStretchDiBits Sınıfı"
type: docs
weight: 1410
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | Yeni bir [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Raster işlem kodunu (32-bit işaretsiz tamsayı) belirten bir değeri alır veya ayarlar <br/>            . Bu kodlar, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece nihai renk elde edilir. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) bu nesne hedef sınırlayıcı dikdörtgeni cihaz birimlerinde tanımlar.<br/>             |
| cx_dest | int | r/w | Hedef dikdörtgenin mantıksal genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| cx_src | int | r/w | Kaynak dikdörtgenin piksel cinsinden genişliğini belirten bir 32-bit işaretli tamsayıyı alır veya ayarlar. |
| cy_dest | int | r/w | Hedef dikdörtgenin mantıksal yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| cy_src | int | r/w | Kaynak dikdörtgenin piksel cinsinden yüksekliğini belirten bir 32-bit işaretli tamsayıyı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmap'i içeren bir tamponu alır veya ayarlar, bu tamponun EMR_STRETCHDIBITS kaydının sabit kısmıyla bitişik olması gerekmez.<br/>            Buna göre, bu tamponda "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve MUST göz ardı edilmelidir. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır. |
| x_dest | int | r/w | Üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden x koordinatını belirten bir 32-bit işaretli tamsayıyı alır veya ayarlar.<br/>             |
| y_dest | int | r/w | Hedef dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin sol üst köşesinin piksel cinsinden y koordinatını belirten bir 32-bit işaretli tamsayıyı alır veya ayarlar.<br/>             |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

Yeni bir [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/) sınıfı örneği başlatır.

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


