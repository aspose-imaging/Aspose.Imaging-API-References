---
title: "EmfText Sınıfı"
type: docs
weight: 260
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfText()](#EmfText__1) | EmfText sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| chars | int | r/w | Dizedeki karakter sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| dx_buffer | int[] | r/w | İsteğe bağlı karakter aralığı tamponunu alır veya ayarlar<br/>            UndefinedSpace2 (değişken): Kullanılmayan baytların isteğe bağlı sayısı. OutputDx alanının bu yapının önceki kısmını hemen takip etmesi gerekmez.<br/>            OutputDx (değişken): Mantıksal birimlerde yan yana karakter hücrelerinin kökenleri arasındaki çıkış aralığını belirten 32-bit işaretsiz tam sayı dizisi. Bu alanın konumu, kayıttaki başlangıçtan itibaren offDx değerinin bayt cinsinden belirtilmesiyle belirlenir. Aralık tanımlıysa, bu alan çıkış dizesindeki karakter sayısı kadar değer içerir. EmrText nesnesinin Options alanı ETO_PDY bayrağını içeriyorsa, bu tampon çıkış dizesindeki karakter sayısının iki katı kadar değer içerir; her biri için bir yatay ve bir dikey ofset, bu sırayla. ETO_RTLREADING belirtilmişse, karakterler soldan sağa yerine sağdan sola yerleştirilir. Başka hiçbir seçenek bu alanın yorumlanmasını etkilemez. |
| glyph_index_buffer | int[] | r/w | İsteğe bağlı glif indeks tamponunu alır veya ayarlar.<br/>            Eğer seçeneklerde ETO_GLYPH_INDEX bayrağı varsa, çıkış metin dizesindeki karakter kodları aslında bir TrueType yazı tipindeki karakter gliflerinin indeksleridir (2.1.11 ExtTextOutOptions enumarasyonu). Glif indeksleri yazı tipine özgüdür, bu yüzden doğru karakterlerin oynatmada gösterilebilmesi için kullanılan yazı tipi, indeksleri oluşturan yazı tipiyle TAM OLARAK aynı olmalıdır. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Rectangle alanında belirtilen dikdörtgenin nasıl kullanılacağını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu alan birden fazla ExtTextOutOptions <br/>            enumarasyonu (bölüm 2.1.11) değerinin birleşimi olabilir. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | İsteğe bağlı bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) ve mantıksal birimlerde kırpma ve/veya opaklaştırma dikdörtgeni tanımlar. Bu dikdörtgen, içeren kaydın gerçekleştirdiği metin çıkışına uygulanır. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Metni konumlandırmak için kullanılan referans noktasının koordinatlarını belirten bir WMF PointL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15). Referans noktası, son EMR_SETTEXTALIGN kaydı (bölüm 2.3.11.25) ile tanımlanır. Böyle bir kayıt ayarlanmamışsa, varsayılan hizalama TA_LEFT,TA_TOP olur. |
| string_buffer | string | r/w | Karakter dize tamponunu alır veya ayarlar<br/>            UndefinedSpace1 (değişken): Kullanılmayan baytların isteğe bağlı sayısı. <br/>            OutputString alanının bu yapının önceki kısmını hemen takip etmesi gerekmez.<br/>            OutputString (değişken): Çıktı dizesini belirten karakter dizisi. <br/>            Bu alanın konumu, kayıttaki başlangıçtan itibaren offString değerinin bayt cinsinden belirtilmesiyle tanımlanır. <br/>            Karakter sayısı Chars değerinin belirttiği gibi tanımlanır. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

EmfText sınıfının yeni bir örneğini başlatır.

