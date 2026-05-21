---
title: "EmfText"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmrText nesnesi, metin çıktısı için değerler içerir."
type: docs
weight: 35
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

EmrText nesnesi, metin çıktısı için değerler içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Dizenin konumlandırılmasında kullanılan referans noktasının koordinatlarını belirten bir WMF PointL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15). |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Dizenin konumlandırılmasında kullanılan referans noktasının koordinatlarını belirten bir WMF PointL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15). |
| [getChars()](#getChars--) | Dizedeki karakter sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setChars(int value)](#setChars-int-) | Dizedeki karakter sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getOptions()](#getOptions--) | Rectangle alanında belirtilen dikdörtgenin nasıl kullanılacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setOptions(int value)](#setOptions-int-) | Rectangle alanında belirtilen dikdörtgenin nasıl kullanılacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getRectangle()](#getRectangle--) | Mantıksal birimlerde kırpma ve/veya opaklaştırma dikdörtgenini tanımlayan isteğe bağlı bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Mantıksal birimlerde kırpma ve/veya opaklaştırma dikdörtgenini tanımlayan isteğe bağlı bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [getStringBuffer()](#getStringBuffer--) | UndefinedSpace1 (değişken) karakter dizi tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | UndefinedSpace1 (değişken) karakter dizi tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | İsteğe bağlı glif indeks tamponunu alır. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | İsteğe bağlı glif indeks tamponunu ayarlar. |
| [getDxBuffer()](#getDxBuffer--) | UndefinedSpace2 (değişken) isteğe bağlı karakter aralığı tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | UndefinedSpace2 (değişken) isteğe bağlı karakter aralığı tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Dizenin konumlandırılmasında kullanılan referans noktasının koordinatlarını belirten bir WMF PointL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15). Referans noktası, son EMR\_SETTEXTALIGN kaydı (bölüm 2.3.11.25) ile tanımlanır. Böyle bir kayıt ayarlanmamışsa, varsayılan hizalama TA\_LEFT,TA\_TOP olur.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Dizenin konumlandırılmasında kullanılan referans noktasının koordinatlarını belirten bir WMF PointL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.15). Referans noktası, son EMR\_SETTEXTALIGN kaydı (bölüm 2.3.11.25) ile tanımlanır. Böyle bir kayıt ayarlanmamışsa, varsayılan hizalama TA\_LEFT,TA\_TOP olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Dizedeki karakter sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Dizedeki karakter sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Rectangle alanında belirtilen dikdörtgenin nasıl kullanılacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Bu alan, birden fazla ExtTextOutOptions (bölüm 2.1.11) değerinin birleşimi olabilir.

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Rectangle alanında belirtilen dikdörtgenin nasıl kullanılacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Bu alan, birden fazla ExtTextOutOptions (bölüm 2.1.11) değerinin birleşimi olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Mantıksal birimlerde kırpma ve/veya opaklaştırma dikdörtgenini tanımlayan isteğe bağlı bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). Bu dikdörtgen, içeren kayıt tarafından gerçekleştirilen metin çıktısına uygulanır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Mantıksal birimlerde kırpma ve/veya opaklaştırma dikdörtgenini tanımlayan isteğe bağlı bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). Bu dikdörtgen, içeren kayıt tarafından gerçekleştirilen metin çıktısına uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


UndefinedSpace1 (değişken) karakter dizi tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. OutputString alanının, bu yapının önceki bölümünden hemen sonra gelmesi zorunlu değildir. OutputString (değişken): Çıktı olarak verilecek dizeyi belirten karakter dizisi. Bu alanın konumu, kaydın başlangıcından itibaren offString değeriyle bayt cinsinden belirtilir. Karakter sayısı Chars değeriyle belirtilir.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


UndefinedSpace1 (değişken) karakter dizi tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. OutputString alanının, bu yapının önceki bölümünden hemen sonra gelmesi zorunlu değildir. OutputString (değişken): Çıktı olarak verilecek dizeyi belirten karakter dizisi. Bu alanın konumu, kaydın başlangıcından itibaren offString değeriyle bayt cinsinden belirtilir. Karakter sayısı Chars değeriyle belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


İsteğe bağlı glif indeks tamponunu alır. Seçeneklerde ETO\_GLYPH\_INDEX bayrağı varsa, çıktı metin dizesindeki karakter kodları aslında bir TrueType yazı tipindeki karakter gliflerinin indeksleridir (2.1.11 ExtTextOutOptions sayımı). Glif indeksleri yazı tipine özgüdür, bu yüzden oynatmada doğru karakterlerin görüntülenmesi için kullanılan yazı tipi, indeksleri oluşturan yazı tipiyle aynı olmalıdır.

**Returns:**
int[] - isteğe bağlı glif indeks tamponu.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


İsteğe bağlı glif indeks tamponunu ayarlar. Seçeneklerde ETO\_GLYPH\_INDEX bayrağı varsa, çıktı metin dizesindeki karakter kodları aslında bir TrueType yazı tipindeki karakter gliflerinin indeksleridir (2.1.11 ExtTextOutOptions sayımı). Glif indeksleri yazı tipine özgüdür, bu yüzden oynatmada doğru karakterlerin görüntülenmesi için kullanılan yazı tipi, indeksleri oluşturan yazı tipiyle aynı olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | isteğe bağlı glif indeks tamponu. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


UndefinedSpace2 (değişken) isteğe bağlı karakter aralığı tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. OutputDx alanının, bu yapının önceki bölümünden hemen sonra gelmesi zorunlu değildir. OutputDx (değişken): Mantıksal birimlerde bitişik karakter hücrelerinin kökenleri arasındaki çıktı aralığını belirten 32-bit işaretsiz tamsayı dizisi. Bu alanın konumu, kaydın başlangıcından itibaren offDx değeriyle bayt cinsinden belirtilir. Aralık tanımlıysa, bu alan çıktı dizesindeki karakter sayısı kadar değer içerir. EmrText nesnesinin Options alanı ETO\_PDY bayrağını içeriyorsa, bu tampon çıktı dizesindeki karakter sayısının iki katı kadar değer içerir; her biri için bir yatay ve bir dikey offset sırasıyla. ETO\_RTLREADING belirtilmişse, karakterler soldan sağa yerine sağdan sola yerleştirilir. Başka hiçbir seçenek bu alanın yorumunu etkilemez.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


UndefinedSpace2 (değişken) isteğe bağlı karakter aralığı tamponunu alır veya ayarlar: Kullanılmayan isteğe bağlı bir miktar bayt. OutputDx alanının, bu yapının önceki bölümünden hemen sonra gelmesi zorunlu değildir. OutputDx (değişken): Mantıksal birimlerde bitişik karakter hücrelerinin kökenleri arasındaki çıktı aralığını belirten 32-bit işaretsiz tamsayı dizisi. Bu alanın konumu, kaydın başlangıcından itibaren offDx değeriyle bayt cinsinden belirtilir. Aralık tanımlıysa, bu alan çıktı dizesindeki karakter sayısı kadar değer içerir. EmrText nesnesinin Options alanı ETO\_PDY bayrağını içeriyorsa, bu tampon çıktı dizesindeki karakter sayısının iki katı kadar değer içerir; her biri için bir yatay ve bir dikey offset sırasıyla. ETO\_RTLREADING belirtilmişse, karakterler soldan sağa yerine sağdan sola yerleştirilir. Başka hiçbir seçenek bu alanın yorumunu etkilemez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

