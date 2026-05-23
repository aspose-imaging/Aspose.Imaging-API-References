---
title: "EmfMaskBlt Sınıfı"
type: docs
weight: 600
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | Yeni bir [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Kaynak bitmap'in arka plan rengini belirten <br/>            ([MS-WMF] bölüm 2.2.2.8) bir WMF ColorRef nesnesini alır veya ayarlar. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) bu nesne hedef sınırlayıcı dikdörtgeni cihaz birimlerinde tanımlar.<br/>             |
| cx_dest | int | r/w | Hedef dikdörtgenin mantıksal genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| cy_dest | int | r/w | Hedef dikdörtgenin mantıksal yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Maske bitmaplerini içeren bir tamponu alır veya ayarlar, bu bitmapler EMR_MASKBLT kaydının sabit bölümüyle ya da birbirleriyle <br/>            bitişik olmak zorunda değildir. Bu nedenle, \"UndefinedSpace\" olarak etiketlenmiş bu tampondaki alanlar isteğe bağlıdır ve <br/>            YOK SAYILMALIDIR. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | Dörtlü raster işlemini alır veya ayarlar, bu işlem bitmapin ön plan ve arka plan renkleri için üçlü raster işlemlerini belirler. Bu değerler kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle nasıl birleştirileceğini tanımlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmaplerini içeren bir tamponu alır veya ayarlar, bu bitmapler EMR_MASKBLT kaydının sabit bölümüyle ya da birbirleriyle <br/>            bitişik olmak zorunda değildir. Bu nedenle, \"UndefinedSpace\" olarak etiketlenmiş bu tampondaki alanlar isteğe bağlıdır ve <br/>            YOK SAYILMALIDIR. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 32-bit işaretsiz tamsayıyı alır veya ayarlar, bu değer mask bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirler. Bu değer DIBColors enumarasyonunda olmalıdır. |
| usage_src | int | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır. |
| x_dest | int | r/w | Üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| x_mask | int | r/w | Maske bitmap'inin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Kaynak bitmap'e uygulanacak dünya‑uzayından sayfa‑uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| y_dest | int | r/w | Hedef dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_mask | int | r/w | Maske bitmap'inin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

Yeni bir [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) sınıfı örneği başlatır.

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


