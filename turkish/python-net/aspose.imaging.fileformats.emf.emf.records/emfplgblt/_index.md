---
title: "EmfPlgBlt Sınıfı"
type: docs
weight: 750
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Yeni bir örnek başlatır [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) sınıfını. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Alır veya ayarlar üç WMF PointL nesnesinden oluşan bir dizi ([MS-WMF] bölüm 2.2.2.15) bu <br/>            blok aktarımı için bir paralelkenar hedef alanının üç köşesini belirten. Kaynak dikdörtgenin sol-üst köşesi bu dizideki ilk noktaya, <br/>            sağ-üst köşesi ikinci noktaya ve sol-alt köşesi üçüncü noktaya eşlenir. Kaynak dikdörtgenin sağ-alt köşesi, paralelkenarın içinde örtük dördüncü noktaya <br/>            eşlenir; bu nokta, ilk üç nokta (A, B ve C) vektör olarak ele alınarak hesaplanır.<br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | Alır veya ayarlar WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) belirten <br/>            kaynak bitmap'in arka plan rengini. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Alır veya ayarlar WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19) tanımlayan <br/>            hedefe çıkış için cihaz birimlerinde sınırlayıcı dikdörtgeni. |
| cx_src | int | r/w | Kaynak dikdörtgenin mantıksal genişliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| cy_src | int | r/w | Kaynak dikdörtgenin mantıksal yüksekliğini belirten 32-bit işaretli tam sayıyı alır veya ayarlar. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Maske bitmap'ini içeren bir tamponu alır veya ayarlar, bu tamponun EMR_PLGBLT kaydının sabit bölümüyle veya birbirleriyle bitişik olması gerekmez. <br/>            Buna göre, bu tamponda \"UndefinedSpace\" olarak etiketlenen alanlar isteğe bağlıdır ve MUST göz ardı edilmelidir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmap'ini içeren bir tamponu alır veya ayarlar, bu tamponun EMR_PLGBLT kaydının sabit bölümüyle veya birbirleriyle bitişik olması gerekmez. <br/>            Buna göre, bu tamponda \"UndefinedSpace\" olarak etiketlenen alanlar isteğe bağlıdır ve MUST göz ardı edilmelidir. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | 32-bit işaretsiz tamsayıyı alır veya ayarlar, bu değer mask bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirler. Bu değer DIBColors enumarasyonunda olmalıdır. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. <br/>            Bu değer MUST DIBColors enum'unda olmalıdır. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Kaynak bitmap'e uygulanacak dünya‑uzayından sayfa‑uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| x_mask | int | r/w | Maske bitmap'inin sol üst köşesinin mantıksal x koordinatını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_mask | int | r/w | Maske bitmap'inin sol üst köşesinin mantıksal y koordinatını belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Yeni bir örnek başlatır [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) sınıfını.

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


