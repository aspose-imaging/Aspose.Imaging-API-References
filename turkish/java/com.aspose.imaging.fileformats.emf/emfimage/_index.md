---
title: "EmfImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gelişmiş Metafile Formatı EMF vektör görüntü formatı desteği için API, grafik görüntüleri cihazdan bağımsız bir şekilde işlerken orijinal özelliklerini koruyan kapsamlı bir araçtır."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

Gelişmiş Metafile Formatı (EMF) vektör görüntü formatı desteği için API, grafik görüntüleri cihazdan bağımsız bir şekilde işlerken orijinal özelliklerini koruyan kapsamlı bir araçtır. Oranları, boyutları, renkleri ve diğer grafik özniteliklerini korumak üzere geliştirilmiş olup, EMF Plus format desteği ve bölgeleri kırpma, tuvali ve görüntüleri yeniden boyutlandırma, döndürme, çevirme, görüntü paletlerini ayarlama, APS cihaz bağlamına dışa ve içe aktarma, sıkıştırma ve EMF'yi diğer formatlara dönüştürme özelliklerini içerir; böylece EMF görüntülerinin çeşitli uygulamalarda esnek bir şekilde işlenmesi ve sorunsuz entegrasyonu sağlanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfImage()](#EmfImage--) | EMF görüntüleriyle çalışmaya, yeni bir [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) sınıfı örneği başlatarak başlayın. |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Genişlik ve yükseklik parametrelerini belirterek yeni bir [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) sınıfı örneği oluşturun. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeader()](#getHeader--) | Bu özellik ile EMF metafile başlık kaydını alın. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Bu özellik ile EMF metafile başlık kaydını değiştirin. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbellekte olup olmadığını gösteren bir değere erişin, böylece ek veri okuma ihtiyacı ortadan kalkar. |
| [getRecords()](#getRecords--) | Nesneyle ilişkili kayıtları alın veya değiştirin. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Nesneyle ilişkili kayıtları değiştirin. |
| [getFileFormat()](#getFileFormat--) | Nesneyle ilişkili dosya formatı değerine erişin. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu parametrenin vektör görüntülerine uygulanmadığı için, raster görüntülere özgü bit-per-piksel sayısını alın. |
| [getWidthF()](#getWidthF--) | Görüntünün genişliğine erişin; bu, kesin renderleme ve işleme için temel bilgi sağlar. |
| [getHeightF()](#getHeightF--) | Görüntünün yüksekliğini alın; bu, doğru renderleme ve düzen ayarlamaları için kolaylık sağlar. |
| [cacheData()](#cacheData--) | Bu yöntemle temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) verilerini verimli bir şekilde önbelleğe alın ve gereksiz yüklemeleri önleyin. |
| [getUsedFonts()](#getUsedFonts--) | Bu yöntemle metafilde kullanılan yazı tipleri listesini alın. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Bu işlevi kullanarak tuvali kolayca yeniden boyutlandırın. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal görüntü seçeneklerini alır. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntü paletini ayarlar. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, EMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Metin şekillere dönüştürülecek.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Çizim yüzeyinin arka plan rengi.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sayfa boyutu.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Gömülü emf varsa emf işlenir; aksi takdirde wmf işlenir.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Yatay kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderX(50);

    // Dikey kenar boşluğunu ayarlayın
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


EMF görüntüleriyle çalışmaya, yeni bir [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) sınıfı örneği başlatarak başlayın. EMF görüntülerini projelerinize hızlı ve verimli bir şekilde eklemek için idealdir.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Genişlik ve yükseklik parametrelerini belirterek yeni bir [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) sınıfı örneği oluşturun. Bu yapıcı, belirli boyutlarla EMF görüntülerini başlatma sürecini basitleştirir ve geliştirme iş akışınızın verimliliğini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Bu özellik ile EMF metafile başlık kaydını alın. Uygulamanız içinde metafile verilerini verimli bir şekilde yönetmek için idealdir. Metafile başlık bilgilerine hızlı erişimle iş akışınızı iyileştirin.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Bu özellik ile EMF metafile başlık kaydını değiştirin. Uygulamanız içinde metafile verilerini verimli bir şekilde yönetmek için idealdir. Metafile başlık bilgilerine hızlı erişimle iş akışınızı iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbellekte olup olmadığını gösteren bir değere erişin, böylece ek veri okuma ihtiyacı ortadan kalkar. Önbellekteki verinin anında erişilebilir olup olmadığını hızlıca belirleyerek verimliliği artırın. Veri alma süreçlerini hızlandırarak iş akışınızı optimize edin.

**Returns:**
boolean - nesnenin verisi önbellekteyse `true`; aksi takdirde `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Nesneyle ilişkili kayıtları alın veya değiştirin. Kayıt koleksiyonuna verimli bir şekilde erişin ve yönetin, böylece veri işleme ve manipülasyonu geliştirilir. Nesnenin kayıtlarıyla sorunsuz bir şekilde etkileşime girerek iş akışınızı optimize edin.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Nesneyle ilişkili kayıtları değiştirin. Kayıt koleksiyonuna verimli bir şekilde erişin ve yönetin, böylece veri işleme ve manipülasyonu geliştirilir. Nesnenin kayıtlarıyla sorunsuz bir şekilde etkileşime girerek iş akışınızı optimize edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Kayıtlar. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Nesneyle ilişkili dosya formatı değerine erişin. Nesneyle ilişkili dosyanın formatını kolayca belirleyerek işlemeyi ve uyumluluk kontrollerini kolaylaştırın. Dosya formatı bilgilerini zahmetsizce alarak iş akışınızı basitleştirin.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Vektör görüntülerine uygulanmadığı için raster görüntülere özgü bit-per-piksel sayısını alın. Raster görüntülerin piksel derinliğini hızlıca belirleyerek kesin analiz ve manipülasyon yapın, görüntü verilerinin doğru işlenmesini sağlayın.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Görüntünün genişliğine erişin, bu kesin render ve işleme için temel bilgi sağlar. Görüntünün genişliğini hızlıca alarak çeşitli uygulama ve platformlarda uyumluluk ve doğru yerleşimi garantileyin.

**Returns:**
float - Görüntünün piksel cinsinden genişliği.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Görüntünün yüksekliğini alın, doğru render ve yerleşim ayarlamalarını kolaylaştırır. Yükseklik özelliğine erişmek, farklı platform ve uygulamalarda uyumluluk ve sorunsuz entegrasyon sağlar.

**Returns:**
float - Görüntünün piksel cinsinden yüksekliği.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Bu yöntemle temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\\#getDataStreamContainer))'den veri önbelleğe almayı verimli bir şekilde yapın ve gereksiz yüklemeleri önleyin. Uygulamanızda performansı artırın ve veri erişimini düzenleyin, kaynak kullanımını optimize ederek yanıt süresini iyileştirin.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Tüm kayıtları yüklemek için verileri önbelleğe alın.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Anahtar bir kayıt türüdür, değer ise WMF görüntüsündeki o türdeki kayıt sayısını gösterir.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // İstatistikleri topla
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
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
    emfImage.dispose();
}

//Çıktı şöyle görünebilir:
//Toplam kayıt sayısı: 1188
//Kayıt Türü                              Sayı
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Bu yöntemle metafilde kullanılan yazı tiplerinin listesini alın. Yazı tipi kullanımına dair içgörüler elde edin, böylece yazı tipi kaynaklarını verimli bir şekilde yönetin ve optimize edin, render ve görüntü doğruluğunu artırın.

**Returns:**
java.lang.String[] - Yazı tipi listesi
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Bu işlevi kullanarak tuvali kolayca yeniden boyutlandırın. İçeriği değiştirmeden görüntünün genel boyutlarını ayarlamak için mükemmeldir. Sunumu geliştirin ve görüntüleri çeşitli gösterim boyutlarına zahmetsizce hazırlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Yeni dikdörtgen. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal görüntü seçeneklerini alır.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

