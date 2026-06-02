---
title: "EmfLogFontPanose Sınıfı"
type: docs
weight: 160
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---

**Summary:** The LogFontPanose object specifies the PANOSE characteristics of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontPanose

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfLogFontPanose(emf_log_font)](#EmfLogFontPanose_emf_log_font_1) | Yeni bir [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Karakter glif kümesini belirten 8-bit işaretsiz tam sayıyı alır veya ayarlar. Bu <br/>            WMF CharacterSet numaralandırmasında ([MS-WMF] bölüm 2.1.1.5) bir değer OLMALIDIR. Karakter kümesi bilinmiyorsa, metafile işleme <br/>            bu fontla oluşturulan dizeleri çevirmeye veya yorumlamaya ÇALIŞMAMALIDIR. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Kırpma hassasiyetini belirten 8-bit işaretsiz tam sayıyı alır veya ayarlar. Kırpma hassasiyeti, kırpma bölgesinin dışına kısmen çıkan karakterlerin nasıl kırpılacağını tanımlar. <br/>            Bu, WMF ClipPrecision Bayraklarından bir veya birden fazla olabilir. |
| culture | int | r/w | Sıfıra ayarlanması ve göz ardı edilmesi gereken 32-bit işaretsiz tamsayı alır veya ayarlar. |
| escapement | int | r/w | Escapement vektörü ile cihazın x ekseni arasındaki açıyı, derece ondalıkları cinsinden belirten 32-bit işaretli tam sayıyı alır veya ayarlar. Escapement vektörü <br/>            bir metin satırının temel çizgisine paraleldir. |
| yazı tipi adı | string | r/w | Facename'i (64 bayt) alır veya ayarlar:  Fontun tipografisini belirten en fazla 32 Unicode karakterden oluşan bir dizedir. Bu dizenin uzunluğu 32 karakterden az ise, sonlandırıcı <br/>            NULL bulunmalıdır ve bu noktadan sonra alanın geri kalan kısmı GÖZ ARDI EDİLMELİDİR. |
| full_name | string | r/w | Yazı tipinin tam adını tanımlayan 64 Unicode karakterlik bir dize alır veya ayarlar. Eğer <br/>            bu dizenin uzunluğu 64 karakterden kısa ise, sonlandırıcı NULL bulunmalıdır, ardından <br/>            bu alanın geri kalanının göz ardı edilmesi gerekir. |
| height | int | r/w | Yazı tipinin <br/>            karakter hücresi veya karakterinin yüksekliğini, mantıksal birimlerde belirten 32 bit işaretli bir tam sayı alır veya ayarlar. Karakter yüksekliği değeri, em boyutu olarak da bilinir, <br/>            karakter hücresi yüksekliği değerinden iç önek değerinin çıkarılmasıyla elde edilir. Yazı tipi eşleyicisi, Yükseklik alanında belirtilen değeri aşağıdaki şekilde YORUMLAMALIDIR. |
| italik | System.Byte | r/w | 0x01 olarak ayarlanırsa italik bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; aksi takdirde, <br/>            0x00 olarak ayarlanmalıdır. |
| match | int | r/w | Bu alanı alır veya ayarlar. Göz ardı edilmesi gerekir. |
| yönlendirme | int | r/w | Her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı, derece ondalıkları cinsinden belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Çıktı hassasiyetini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar. <br/>            Çıktı hassasiyeti, yazı tipinin istenen yükseklik, genişlik, <br/>            karakter yönlendirmesi, kaçış, pitch ve yazı tipi türüyle ne kadar yakın eşleşmesi gerektiğini tanımlar. WMF <br/>            OutPrecision sayımından bir değer OLMALIDIR. |
| padding | int | r/w | Bu yapının 32-bit hizalanmasını sağlamak için yalnızca var olan bir alan alır veya ayarlar. Göz ardı edilmesi gerekir |
| panose | [EmfPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpanose/) | r/w | Mantıksal yazı tipinin PANOSE özelliklerini belirten bir Panose nesnesi (bölüm 2.2.21) alır veya ayarlar <br/>            . Bu nesnenin tüm alanları sıfır ise, göz ardı edilmesi gerekir. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Yazı tipinin pitch ve familyasını belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. <br/>            Yazı tipi aileleri, bir yazı tipinin görünümünü genel bir şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir yazı tipi belirtmek için tasarlanmıştır. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Çıktı kalitesini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar. Çıktı kalitesi, <br/>            mantıksal yazı tipi özelliklerini gerçek bir <br/>            fiziksel yazı tipiyle ne kadar yakından eşleştirmeye çalışılacağını tanımlar. WMF FontQuality sayımındaki ([MS-WMF] <br/>            bölüm 2.1.1.10) değerlerden biri OLMALIDIR. |
| üstü çizili | System.Byte | r/w | 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; <br/>            aksi takdirde, 0x00 olarak ayarlanmalıdır. |
| stil | string | r/w | Yazı tipinin stilini tanımlayan 32 Unicode karakterlik bir dize alır veya ayarlar. Eğer bu dizenin uzunluğu <br/>            32 karakterden az ise, sonlandırıcı NULL bulunmalıdır, ardından bu alanın <br/>            geri kalan kısmı YOK SAYILMALIDIR. |
| style_size | int | r/w | Yazı tipi <br/>            ipucu işlemesinin gerçekleştirileceği punto boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar. Sıfıra ayarlanırsa, yazı tipi ipucu işlemesi LogFont nesnesindeki Height alanına karşılık gelen punto boyutunda gerçekleştirilir. |
| altı çizili | System.Byte | r/w | 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; <br/>            aksi takdirde, 0x00 olarak ayarlanmalıdır. |
| vendor_id | int | r/w | Bu alanı alır veya ayarlar. Göz ardı edilmesi gerekir. |
| version | int | r/w | Bu alanı alır veya ayarlar. Göz ardı edilmesi gerekir. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Yazı tipinin ağırlığını, sıfır ile 1000 arasında bir değer olarak belirten 32 bit işaretli bir tam sayı alır veya ayarlar. <br/>            Örneğin, 400 normal ve 700 kalındır. Bu değer sıfır ise, varsayılan bir <br/>            ağırlık kullanılabilir. |
| width | int | r/w | Yazı tipindeki karakterlerin ortalama genişliğini, mantıksal birimlerde belirten 32 bit işaretli bir tam sayı alır veya ayarlar. <br/>            Genişlik alanı değeri sıfır ise, tipografinin istediği <br/>            en-boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer HESAPLANMALIDIR. |


### Constructor: EmfLogFontPanose(emf_log_font) {#EmfLogFontPanose_emf_log_font_1}


```
 EmfLogFontPanose(emf_log_font) 
```

Yeni bir [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | Temel log yazı tipi. |

