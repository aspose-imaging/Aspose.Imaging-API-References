---
title: "EmfLogFontEx Sınıfı"
type: docs
weight: 140
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---

**Summary:** The LogFontEx object specifies the extended attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfLogFontEx(emf_log_font)](#EmfLogFontEx_emf_log_font_1) | Yeni bir [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Karakter glif kümesini belirten 8-bit işaretsiz tam sayıyı alır veya ayarlar. Bu <br/>            WMF CharacterSet numaralandırmasında ([MS-WMF] bölüm 2.1.1.5) bir değer OLMALIDIR. Karakter kümesi bilinmiyorsa, metafile işleme <br/>            bu fontla oluşturulan dizeleri çevirmeye veya yorumlamaya ÇALIŞMAMALIDIR. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Kırpma hassasiyetini belirten 8-bit işaretsiz tam sayıyı alır veya ayarlar. Kırpma hassasiyeti, kırpma bölgesinin dışına kısmen çıkan karakterlerin nasıl kırpılacağını tanımlar. <br/>            Bu, WMF ClipPrecision Bayraklarından bir veya birden fazla olabilir. |
| escapement | int | r/w | Escapement vektörü ile cihazın x ekseni arasındaki açıyı, derece ondalıkları cinsinden belirten 32-bit işaretli tam sayıyı alır veya ayarlar. Escapement vektörü <br/>            bir metin satırının temel çizgisine paraleldir. |
| yazı tipi adı | string | r/w | Facename'i (64 bayt) alır veya ayarlar:  Fontun tipografisini belirten en fazla 32 Unicode karakterden oluşan bir dizedir. Bu dizenin uzunluğu 32 karakterden az ise, sonlandırıcı <br/>            NULL bulunmalıdır ve bu noktadan sonra alanın geri kalan kısmı GÖZ ARDI EDİLMELİDİR. |
| full_name | string | r/w | Fontun tam adını içeren 64 Unicode karakterlik bir dizeyi alır veya ayarlar. Bu dizenin uzunluğu 64 karakterden az ise, sonlandırıcı <br/>            NULL bulunmalıdır ve bu noktadan sonra alanın geri kalan kısmı GÖZ ARDI EDİLMELİDİR. |
| height | int | r/w | Yazı tipinin <br/>            karakter hücresi veya karakterinin yüksekliğini, mantıksal birimlerde belirten 32 bit işaretli bir tam sayı alır veya ayarlar. Karakter yüksekliği değeri, em boyutu olarak da bilinir, <br/>            karakter hücresi yüksekliği değerinden iç önek değerinin çıkarılmasıyla elde edilir. Yazı tipi eşleyicisi, Yükseklik alanında belirtilen değeri aşağıdaki şekilde YORUMLAMALIDIR. |
| italik | System.Byte | r/w | 0x01 olarak ayarlanırsa italik bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; aksi takdirde, <br/>            0x00 olarak ayarlanmalıdır. |
| yönlendirme | int | r/w | Her karakterin taban çizgisi ile cihazın x ekseni arasındaki açıyı, derece ondalıkları cinsinden belirten 32 bit işaretli bir tam sayı alır veya ayarlar. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Çıktı hassasiyetini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar. <br/>            Çıktı hassasiyeti, yazı tipinin istenen yükseklik, genişlik, <br/>            karakter yönlendirmesi, kaçış, pitch ve yazı tipi türüyle ne kadar yakın eşleşmesi gerektiğini tanımlar. WMF <br/>            OutPrecision sayımından bir değer OLMALIDIR. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Yazı tipinin pitch ve familyasını belirten bir WMF PitchAndFamily nesnesi ([MS-WMF] bölüm 2.2.2.14) alır veya ayarlar. <br/>            Yazı tipi aileleri, bir yazı tipinin görünümünü genel bir şekilde tanımlar. Belirtilen yazı tipi mevcut olmadığında bir yazı tipi belirtmek için tasarlanmıştır. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Çıktı kalitesini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar. Çıktı kalitesi, <br/>            mantıksal yazı tipi özelliklerini gerçek bir <br/>            fiziksel yazı tipiyle ne kadar yakından eşleştirmeye çalışılacağını tanımlar. WMF FontQuality sayımındaki ([MS-WMF] <br/>            bölüm 2.1.1.10) değerlerden biri OLMALIDIR. |
| betik | string | r/w | Yazı tipinin karakter kümesini tanımlayan 32 Unicode karakterlik bir dize alır veya ayarlar. <br/>            Bu dizenin uzunluğu 32 karakterden az ise, sonlandırıcı NULL bulunmalıdır, <br/>            ardından bu alanın geri kalan kısmı YOK SAYILMALIDIR. |
| üstü çizili | System.Byte | r/w | 0x01 olarak ayarlanırsa üstü çizili bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; <br/>            aksi takdirde, 0x00 olarak ayarlanmalıdır. |
| stil | string | r/w | Yazı tipinin stilini tanımlayan 32 Unicode karakterlik bir dize alır veya ayarlar. Eğer bu dizenin uzunluğu <br/>            32 karakterden az ise, sonlandırıcı NULL bulunmalıdır, ardından bu alanın <br/>            geri kalan kısmı YOK SAYILMALIDIR. |
| altı çizili | System.Byte | r/w | 0x01 olarak ayarlanırsa altı çizili bir yazı tipini belirten 8 bit işaretsiz bir tam sayı alır veya ayarlar; <br/>            aksi takdirde, 0x00 olarak ayarlanmalıdır. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Yazı tipinin ağırlığını, sıfır ile 1000 arasında bir değer olarak belirten 32 bit işaretli bir tam sayı alır veya ayarlar. <br/>            Örneğin, 400 normal ve 700 kalındır. Bu değer sıfır ise, varsayılan bir <br/>            ağırlık kullanılabilir. |
| width | int | r/w | Yazı tipindeki karakterlerin ortalama genişliğini, mantıksal birimlerde belirten 32 bit işaretli bir tam sayı alır veya ayarlar. <br/>            Genişlik alanı değeri sıfır ise, tipografinin istediği <br/>            en-boy oranına sahip bir yazı tipi bulmak için diğer LogFont değerlerinden uygun bir değer HESAPLANMALIDIR. |


### Constructor: EmfLogFontEx(emf_log_font) {#EmfLogFontEx_emf_log_font_1}


```
 EmfLogFontEx(emf_log_font) 
```

Yeni bir [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | EMF günlük yazı tipi. |

