---
title: "EmfBitBlt Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | Yeni bir [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Raster işlem kodunu belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar <br/>            bu kod, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle ve isteğe bağlı olarak bir fırça deseniyle nasıl birleştirileceğini tanımlar, böylece son renk elde edilir. |
| bk_src_argb_32_color | int | r/w | WMF ColorRef nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8) bu nesne kaynak bitmap'in<br/>            arka plan rengini belirler. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) bu nesne hedef sınırlayıcı dikdörtgeni cihaz birimlerinde tanımlar.<br/>             |
| cx_dest | int | r/w | Kaynak ve <br/>            hedef dikdörtgenlerin mantıksal genişliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar. |
| cy_dest | int | r/w | Kaynak ve <br/>            hedef dikdörtgenlerin mantıksal yüksekliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmap'i içeren bir tamponu alır veya ayarlar; bu tamponun EMR_BITBLT kaydının sabit bölümüne <br/>            bitişik olması gerekmez. Buna göre, bu tampondaki "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır. |
| x_dest | int | r/w | Üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Kaynak bitmap'e uygulanacak dünya‑uzayından sayfa‑uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| y_dest | int | r/w | Hedef dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

Yeni bir [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/) sınıfı örneği başlatır.

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


