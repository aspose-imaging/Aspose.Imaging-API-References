---
title: "EmfAlphaBlend Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Yeni bir [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | WMF ColorRef nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.8) bu nesne kaynak bitmap'in<br/>            arka plan rengini belirler. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Kaynak ve<br/>            hedef bitmap'ler için karıştırma işlemlerini belirten bir yapıyı alır veya ayarlar. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) bu nesne hedef sınırlayıcı dikdörtgeni cihaz birimlerinde tanımlar.<br/>             |
| cx_dest | int | r/w | Hedef<br/>            dikdörtgenin mantıksal genişliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar. Bu değer SIFIR'DAN büyük olmalıdır. |
| cx_src | int | r/w | Kaynak dikdörtgenin mantıksal genişliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar.<br/>            Bu değer SIFIR'DAN büyük olmalıdır. |
| cy_dest | int | r/w | Hedef dikdörtgenin mantıksal yüksekliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar.<br/>            Bu değer SIFIR'DAN büyük olmalıdır. |
| cy_src | int | r/w | Kaynak dikdörtgenin mantıksal yüksekliğini belirten 32-bit işaretli tamsayıyı alır veya ayarlar.<br/>            Bu değer SIFIR'DAN büyük olmalıdır. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Kaynak bitmap'i içeren bir tamponu alır veya ayarlar, bu tamponun EMR_ALPHABLEND kaydının sabit bölümüyle bitişik olması gerekmez.<br/>            Bu nedenle, bu<br/>            tamponda "UndefinedSpace" olarak etiketlenmiş alanlar isteğe bağlıdır ve YOK SAYILMALIdır. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Kaynak bitmap başlığındaki renk tablosundaki değerlerin nasıl yorumlanacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>            Bu değer DIBColors sayımında (bölüm 2.1.9) olmalıdır. |
| x_dest | int | r/w | Üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| x_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal x koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Kaynak bitmap'e uygulanacak dünya‑uzayından sayfa‑uzayına dönüşümü belirten bir XForm nesnesi (bölüm 2.2.28) alır veya ayarlar. |
| y_dest | int | r/w | Hedef dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
| y_src | int | r/w | Kaynak dikdörtgenin üst‑sol <br/>            köşesinin mantıksal y koordinatını belirten 32‑bit işaretli bir tamsayı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Yeni bir [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) sınıfı örneği başlatır.

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


