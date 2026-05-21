---
title: "WmfImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Microsoft Windows Metafile WMF görüntülerini API'mizle sorunsuz bir şekilde, değişken uzunlukta kayıtlar içinde depolanan hem vektör hem de bitmap verilerini işleyerek manipüle edin."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Microsoft Windows Metafile (WMF) görüntülerini API'mizle manipüle edin, değişken uzunlukta kayıtlar içinde depolanan hem vektör hem de bitmap verilerini sorunsuz bir şekilde işleyin. Özel görüntü paletleri ayarlarken görüntüleri kolayca yeniden boyutlandırın, döndürün ve çevirin. WMF dosyalarını sıkıştırılmış WMZ formatlarına dönüştürün veya çoklu platform ve uygulamalarda esnek kullanım için raster görüntü formatlarında kaydedin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfImage()](#WmfImage--) | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) sınıfının yeni bir örneğini oluşturun, Windows Metafile (WMF) görüntü verilerinin daha ileri manipülasyon ve işlenmesi için başlatın. |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Özelleştirilebilir genişlik ve yükseklik parametreleriyle [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) sınıfının yeni bir örneğini başlatın, belirli boyutlara göre uyarlanmış boş WMF görüntüleri oluşturmayı kolaylaştırın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir boolean değerini alın, ek veri okuma işlemlerine gerek kalmaz. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alın, renk derinliği veya granülerlik seviyesini gösterir. |
| [getWidthF()](#getWidthF--) | Görüntünün genişliğine erişin, yatay eksenindeki piksel sayısını gösterir. |
| [getHeightF()](#getHeightF--) | Görüntünün yüksekliğine erişin, dikey eksenindeki piksel sayısını temsil eder. |
| [getInch()](#getInch--) | İnç özelliğine erişin veya değiştirin, genellikle baskı veya görüntüleme bağlamlarında fiziksel boyutları belirtmek için kullanılan bir ölçü birimini temsil eder. |
| [setInch(int value)](#setInch-int-) | İnç özelliğine erişin veya değiştirin, genellikle baskı veya görüntüleme bağlamlarında fiziksel boyutları belirtmek için kullanılan bir ölçü birimini temsil eder. |
| [getFileFormat()](#getFileFormat--) | Görüntüyle ilişkili dosya formatı değerine erişin, görüntünün depolandığı format hakkında bilgi sağlar. |
| [getFrameBounds()](#getFrameBounds--) | Çerçevenin sınırlarına erişin, görüntü içindeki konum ve boyutlarını gösterir. |
| [cacheData()](#cacheData--) | Verileri verimli bir şekilde önbelleğe alın, temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) üzerinden ek yüklemeye gerek kalmaz. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Belirtilen paleti görüntüye uygulayın, renk temsilini özelleştirmeyi sağlar. |
| [getUsedFonts()](#getUsedFonts--) | Metafile içinde kullanılan yazı tiplerinin listesini alın, görüntüde kullanılan yazı tipi kaynakları hakkında bilgi verir. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Görüntünün tuvalini yeniden boyutlandırın, içerik korunurken boyutlarını ayarlayın. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Belirtilen kayıt nesnesini görüntüye dahil edin, içeriğini ek veri veya meta veri ile zenginleştirin. |
| [getPostScript()](#getPostScript--) | Görüntüyle ilişkili PostScript verisine erişin, yapısı veya içeriği hakkında ayrıntılı bilgi sağlar. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal görüntü seçeneklerini alır. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


## Example: The following example shows how to convert a compressed images (*.
Aşağıdaki örnek, sıkıştırılmış görüntüleri (*.emz,*.wmz, *.svgz) raster formata nasıl dönüştüreceğinizi gösterir.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Windows Metafile (WMF) görüntü verilerinin daha sonraki işlenmesi ve manipülasyonu için başlatılan [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) sınıfının yeni bir örneğini oluşturun. Bu yapıcı, WMF görüntüleriyle çalışmak için temel bir nesne sağlar ve WMF görüntü işleme yeteneklerinin uygulamanızın işlevselliğine sorunsuz entegrasyonunu mümkün kılar.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) sınıfının genişlik ve yükseklik parametreleri özelleştirilebilir şekilde yeni bir örneğini başlatın; bu, belirli boyutlara göre ayarlanmış boş WMF görüntüleri oluşturmayı kolaylaştırır. Bu yapıcıyı, kesin boyutlarla dinamik olarak WMF görüntüleri üretmek ve uygulamanız içinde esnek görüntü oluşturma ve manipülasyonu sağlamak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir boolean değerini alın; bu, ek veri okuma işlemlerine gerek kalmadan yapılır. Bu özelliği, nesnenin verilerinin maliyetli veri alma süreçlerine ihtiyaç duymadan mevcut olup olmadığını belirleyerek uygulamanızda performansı optimize etmek için kullanın.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alın; bu, renk derinliği veya granülerliğin seviyesini gösterir. Bu özelliği, görüntünün renk temsili ve hassasiyetini belirlemek, uyumluluk kontrolleri ve renkle ilgili işlemleri uygulamanızda kolaylaştırmak için kullanın.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Görüntünün genişliğine erişin; bu, yatay eksen boyunca piksel sayısını gösterir. Bu özelliği, görüntünün uzamsal boyutlarını ve en‑boy oranını belirlemek, uygulamanızda kesin yerleşim ve render ayarlamaları yapabilmek için kullanın.

**Returns:**
float - Görüntünün piksel cinsinden genişliği.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Görüntünün yüksekliğine erişin; bu, dikey eksen boyunca piksel sayısını temsil eder. Bu özelliği, görüntünün uzamsal boyutlarını ve en‑boy oranını belirlemek, uygulamanızda doğru yerleşim ve render ayarlamaları yapabilmek için kullanın.

**Returns:**
float - Görüntünün piksel cinsinden yüksekliği.
### getInch() {#getInch--}
```
public int getInch()
```


İnç özelliğine erişin veya onu değiştirin; bu, genellikle baskı veya görüntüleme bağlamlarında fiziksel boyutları belirtmek için kullanılan bir ölçü birimini temsil eder. Bu özelliği, görüntüyle ilişkili inç değerlerini belirlemek veya almak için kullanın; böylece uygulamanızda fiziksel boyutların doğru temsili sağlanır.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


İnç özelliğine erişin veya onu değiştirin; bu, genellikle baskı veya görüntüleme bağlamlarında fiziksel boyutları belirtmek için kullanılan bir ölçü birimini temsil eder. Bu özelliği, görüntüyle ilişkili inç değerlerini belirlemek veya almak için kullanın; böylece uygulamanızda fiziksel boyutların doğru temsili sağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntüyle ilişkili dosya formatı değerine erişin; bu, görüntünün depolandığı format hakkında bilgi verir. Bu özelliği, görüntünün dosya formatını belirlemek ve uygulamanızda uyumluluk kontrolleri ile format‑özel işlemleri kolaylaştırmak için kullanın.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Çerçevenin sınırlarına erişin; bu, çerçevenin görüntü içindeki konum ve boyutlarını gösterir. Bu özelliği, çerçevenin uzamsal konumu hakkında ayrıntılı bilgi almak ve uygulamanızda kesin manipülasyon ve render sağlamak için kullanın.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Verileri verimli bir şekilde önbelleğe alın; bu, temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) üzerinden ek yüklemeye gerek kalmadan yapılır. Bu yöntemi, yerel veri önbelleğini depolayarak ve erişerek uygulamanızda performansı optimize etmek ve kaynak kullanımını en aza indirmek için kullanın.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Tüm kayıtları yüklemek için verileri önbelleğe alın.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // Anahtar bir kayıt türüdür, değer ise WMF görüntüsündeki o türdeki kayıt sayısını gösterir.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // İstatistikleri topla
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // İstatistikleri yazdır
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Çıktıyı boşluklarla hizala
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    wmfImage.dispose();
}

//Çıktı şöyle görünebilir:
//Toplam kayıt sayısı: 613
//Kayıt Türü                              Sayı
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Belirtilen bir paleti görüntüye uygulayın, renk temsilini özelleştirmenizi sağlar. Bu yöntemi görsel renderlamayı iyileştirmek ve uygulamanız içinde belirli renk efektleri elde etmek için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Metafile içinde kullanılan yazı tiplerinin listesini alın, görüntüde kullanılan yazı tipi kaynakları hakkında bilgi sağlar. Bu yöntemi yazı tipi kullanımını analiz etmek ve renderlama veya uygulamanız içinde daha ileri işlem için yazı tipi kullanılabilirliğini sağlamak amacıyla kullanın.

**Returns:**
java.lang.String[] - Yazı tipi listesi
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Görüntünün tuvalini yeniden boyutlandırın, içerik korunurken boyutlarını ayarlayın. Bu yöntemi tuvalin boyutunu içeriği değiştirmeden değiştirmek, uygulamanız içinde düzen ayarlamaları ve kompozisyon değişikliklerini kolaylaştırmak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Yeni dikdörtgen. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Belirtilen kayıt nesnesini görüntüye dahil edin, içeriğini ek veri veya meta veri ile zenginleştirin. Bu yöntemi kayıt nesnelerini görüntüye sorunsuz bir şekilde entegre etmek, uygulamanız içinde kapsamlı veri depolama ve organizasyonu kolaylaştırmak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | Kayıt. |

**Returns:**
int - Kayıt sayısı.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Görüntüyle ilişkili PostScript verisine erişin, yapısı veya içeriği hakkında ayrıntılı bilgi sağlar. Bu yöntemi PostScript verisini daha ileri analiz veya işlem için uygulamanız içinde almak, PostScript renderlama veya manipülasyonuyla ilgili gelişmiş işlevselliği etkinleştirmek amacıyla kullanın.

**Returns:**
java.lang.String - Post script
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal görüntü seçeneklerini alır.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
