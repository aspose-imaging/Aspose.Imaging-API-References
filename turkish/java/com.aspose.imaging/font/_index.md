---
title: "Yazı tipi"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Yazı tipi yüzü, boyutu ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar."
type: docs
weight: 48
url: /tr/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Yazı tipi yüzü, boyutu ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Belirtilen mevcut `com.aspose.imaging.Font` ve `com.aspose.imaging.FontStyle` enum değerini kullanan yeni bir `com.aspose.imaging.Font` başlatır. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Belirtilen bir boyut kullanarak yeni bir `com.aspose.imaging.Font` başlatır. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Belirtilen bir boyut ve stil kullanarak yeni bir `com.aspose.imaging.Font` başlatır. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir `com.aspose.imaging.Font` başlatır. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Belirtilen bir boyut, stil ve birim kullanarak yeni bir `com.aspose.imaging.Font` başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Belirtilen bir boyut ve birim kullanarak yeni bir `com.aspose.imaging.Font` başlatır. |
| [getBold()](#getBold--) | Bu `Font` nesnesinin kalın olup olmadığını gösteren bir değer alır. |
| [getCharacterSet()](#getCharacterSet--) | Bu `Font` nesnesinin kullandığı karakter kümesini belirten bir bayt değeri alır. |
| [getItalic()](#getItalic--) | Bu `Font` nesnesinin italik olup olmadığını gösteren bir değer alır. |
| [getName()](#getName--) | Bu `Font` nesnesinin yüz adını alır. |
| [getStrikeout()](#getStrikeout--) | Bu `Font` nesnesinin yazı tipinde yatay bir çizgi belirleyip belirlemediğini gösteren bir değer alır. |
| [getUnderline()](#getUnderline--) | Bu `Font` nesnesinin altı çizili olup olmadığını gösteren bir değer alır. |
| [getStyle()](#getStyle--) | Bu `Font` nesnesi için stil bilgilerini alır. |
| [getSize()](#getSize--) | Bu `Font` nesnesinin `P:Aspose.Imaging.Font.Unit` özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır. |
| [getUnit()](#getUnit--) | Bu `Font` için ölçü birimini alır. |
| [deepClone()](#deepClone--) | Bu `Font`'un tam bir derin kopyasını oluşturur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bir `com.aspose.imaging.Font` olup olmadığını ve bu `com.aspose.imaging.Font` ile aynı özellik değerlerine sahip olup olmadığını gösterir. |
| [hashCode()](#hashCode--) | Bu `com.aspose.imaging.Font` için karma kodunu alır. |
| [toString()](#toString--) | Bu `com.aspose.imaging.Font`'un insan tarafından okunabilir bir dize temsili döndürür. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Bu örnek, Font ve SolidBrush sınıfının Image yüzeyine dize çizmek için kullanımını gösterir. Örnek yeni bir Image oluşturur ve Figures ve GraphicsPath kullanarak şekiller çizer.
``` java
//BmpOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
//İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Bir Image örneği oluşturur
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Graphics sınıfının bir örneğini oluşturur ve başlatır
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Graphics yüzeyini temizler
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Bir Font örneği oluşturur
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Kırmızı renkli bir SolidBrush örneği oluşturur
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Bir dize çizer
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // tüm değişiklikleri kaydet
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Belirtilen mevcut `com.aspose.imaging.Font` ve `com.aspose.imaging.FontStyle` enum değerini kullanan yeni bir `com.aspose.imaging.Font` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Yeni `com.aspose.imaging.Font`'u oluşturmak için kullanılacak mevcut `com.aspose.imaging.Font`. |
| newStyle | int | Yeni `com.aspose.imaging.Font`'a uygulanacak `com.aspose.imaging.FontStyle`. `com.aspose.imaging.FontStyle` enum'ının birden çok değeri OR operatörü ile birleştirilebilir. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Belirtilen bir boyut kullanarak yeni bir `com.aspose.imaging.Font` başlatır. Karakter kümesi `F:Aspose.Imaging.CharacterSet.Default`, grafik birimi `F:Aspose.Imaging.GraphicsUnit.Point` ve font stili `F:Aspose.Imaging.FontStyle.Regular` olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` adının dize temsili. |
| emSize | float | Yeni fontun puan cinsinden em-boyutu. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Belirtilen bir boyut ve stil kullanarak yeni bir `com.aspose.imaging.Font` başlatır. Karakter kümesi `F:Aspose.Imaging.CharacterSet.Default`, grafik birimi `F:Aspose.Imaging.GraphicsUnit.Point` olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` adının dize temsili. |
| emSize | float | Yeni fontun puan cinsinden em-boyutu. |
| style | int | Yeni fontun `com.aspose.imaging.FontStyle` değeri. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir `com.aspose.imaging.Font` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` adının dize temsili. |
| emSize | float | `unit` parametresiyle belirtilen birimlerde yeni fontun em-boyutu. |
| style | int | Yeni fontun `com.aspose.imaging.FontStyle` değeri. |
| unit | int | Yeni yazı tipinin `com.aspose.imaging.GraphicsUnit`. |
| characterSet | int | Bu yazı tipi için kullanılacak bir karakter kümesi. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Belirtilen bir boyut, stil ve birim kullanarak yeni bir `com.aspose.imaging.Font` başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` adının dize temsili. |
| emSize | float | `unit` parametresiyle belirtilen birimlerde yeni fontun em-boyutu. |
| style | int | Yeni fontun `com.aspose.imaging.FontStyle` değeri. |
| unit | int | Yeni yazı tipinin `com.aspose.imaging.GraphicsUnit`. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Belirtilen boyut ve birim kullanılarak yeni bir `com.aspose.imaging.Font` başlatır. Karakter kümesi `F:Aspose.Imaging.CharacterSet.Default` olarak ayarlanır, stil ise `F:Aspose.Imaging.FontStyle.Regular` olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` adının dize temsili. |
| emSize | float | `unit` parametresiyle belirtilen birimlerde yeni fontun em-boyutu. |
| unit | int | Yeni yazı tipinin `com.aspose.imaging.GraphicsUnit`. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Bu `Font` nesnesinin kalın olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu `Font` kalın ise doğru; aksi takdirde yanlış.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Bu `Font` nesnesinin kullandığı karakter kümesini belirten bir bayt değeri alır.

**Returns:**
int - Bu `Font`'un kullandığı bir karakter kümesi.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Bu `Font` nesnesinin italik olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu `Font` italik ise doğru; aksi takdirde yanlış.
### getName() {#getName--}
```
public String getName()
```


Bu `Font` nesnesinin yüz adını alır.

**Returns:**
java.lang.String - Bu `Font`'un yüz adı temsili bir dize.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Bu `Font` nesnesinin yazı tipinde yatay bir çizgi belirleyip belirlemediğini gösteren bir değer alır.

**Returns:**
boolean - Bu `Font`'un üzerinden yatay bir çizgi geçiyorsa doğru; aksi takdirde yanlış.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Bu `Font` nesnesinin altı çizili olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu `Font` altı çizili ise doğru; aksi takdirde yanlış.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Bu `Font` nesnesi için stil bilgilerini alır.

**Returns:**
int - Bu `Font` için stil bilgilerini içeren bir `FontStyle` numaralandırması.
### getSize() {#getSize--}
```
public float getSize()
```


Bu `Font` nesnesinin `P:Aspose.Imaging.Font.Unit` özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır.

**Returns:**
float - Bu `Font`'un em-boyutu.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Bu `Font` için ölçü birimini alır.

**Returns:**
int - Bu `Font` için ölçü birimini temsil eden bir `GraphicsUnit`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Bu `Font`'un tam bir derin kopyasını oluşturur.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bir `com.aspose.imaging.Font` olup olmadığını ve bu `com.aspose.imaging.Font` ile aynı özellik değerlerine sahip olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek nesne. |

**Returns:**
boolean - `obj` parametresi bir `com.aspose.imaging.Font` ise ve bu `com.aspose.imaging.Font` ile aynı özellik değerlerine sahipse doğru; aksi takdirde yanlış.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu `com.aspose.imaging.Font` için karma kodunu alır.

**Returns:**
int - Bu `com.aspose.imaging.Font` için hash kodu.
### toString() {#toString--}
```
public String toString()
```


Bu `com.aspose.imaging.Font`'un insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu `com.aspose.imaging.Font`'u temsil eden bir dize.
