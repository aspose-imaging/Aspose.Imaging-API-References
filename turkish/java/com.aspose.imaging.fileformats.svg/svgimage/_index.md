---
title: "SvgImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle XML tabanlı metin formatının gücünden yararlanarak Skaler Vektör Grafikleri (SVG) görüntü dosyalarını sorunsuz özelleştirme ve ölçeklenebilirlik için yönetin."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

API'mizle XML tabanlı metin formatının gücünden yararlanarak Skaler Vektör Grafikleri (SVG) görüntü dosyalarını sorunsuz özelleştirme ve ölçeklenebilirlik için yönetin. SVG görüntülerini kolayca yükleyin, vektör öğelerini rasterleştirin ve diğer formatlara dönüştürün; sıkıştırma seviyelerini kontrol ederek dosya boyutunu ve kalitesini projeleriniz için optimize edin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Belirtilen yolu kullanarak görüntüyü bulup yükleyen, [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir nesnesini oluşturur. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Sağlanan akıştan görüntüyü yükleyerek, [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir örneğini oluşturur. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Belirtilen genişlik ve yükseklik ile yeni bir [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) nesnesi oluşturur. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Belirtilen SVG seçenekleri, görüntü genişliği ve yükseklik parametreleriyle [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbellekte olup olmadığını gösteren bir boolean değer döndürür, ek veri okuma işlemlerine gerek kalmaz. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını döndürür. |
| [getFileFormat()](#getFileFormat--) | Görüntünün dosya formatını döndürür, işleme ve uyumluluk kontrolleri için gerekli meta verileri sağlar. |
| [cacheData()](#cacheData--) | `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) altındaki verilerin daha fazla yüklenmeyeceğini garanti ederek verileri önbelleğe al. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü belirtilen boyutlara sığacak şekilde yeniden boyutlandır, en boy oranını koruyarak. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgeni kırpar. |
| [rotate(float angle)](#rotate-float-) | Görüntüyü merkezin etrafında döndür. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntüye belirtilen paleti uygular, estetik veya işlevsel amaçlar için renk şemalarını özelleştirmeyi sağlar. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından SVG görüntüsü yükle.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // SVG'yi rasterleştirmek için rasterleştirme seçeneklerini belirtmemiz gerekir.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Belirtilen yolu kullanarak görüntüyü bulup yükleyen, [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir nesnesini oluşturur. Bu yapıcı, dış dosyalardan SVG görüntü örnekleri oluşturmayı kolaylaştırarak yazılım sistemlerine ve iş akışlarına sorunsuz entegrasyon sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Sağlanan akıştan görüntüyü yükleyerek, [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir örneğini oluşturur. Bu yapıcı, SVG görüntülerinin akışlardan doğrudan yüklenmesini sağlayarak yazılım uygulamalarında görüntü kaynaklarını yönetmede esneklik ve verimlilik kazandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Belirtilen genişlik ve yükseklik ile yeni bir [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) nesnesi oluşturur. Bu yapıcı, geliştiricilerin önceden tanımlı boyutlarla SVG görüntüleri yaratmasına olanak tanır, başlatma sırasında görüntünün boyutu üzerinde hassas kontrol sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Belirtilen SVG seçenekleri, görüntü genişliği ve yükseklik parametreleriyle [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) sınıfının yeni bir örneğini oluşturur. Bu yapıcı, geliştiricilerin özel seçenekler ve boyutlarla SVG görüntülerini başlatmasını sağlayarak SVG içeriği ve düzeni yönetiminde esneklik sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | SVG seçenekleri. |
| genişlik | int | Görüntü genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir boolean değer döndürür, ek veri okuma işlemlerine ihtiyaç duyulmasını ortadan kaldırır. Bu özellik, mevcut önbellekleme durumuna dair bilgi sağlar ve veri alma ve işleme iş akışlarını optimize ederek performans ve verimliliği artırır.

**Returns:**
boolean - nesnenin verisi önbellekteyse `true`; aksi takdirde `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını döndürür. Bu parametrenin vektör görüntülerine uygulanmadığını, çünkü vektörlerin piksel cinsinden ölçülmediğini belirtmek önemlidir. Bu özellik, görüntünün renk derinliği hakkında kritik bilgi sağlar ve işleme ve manipülasyon görevlerine yardımcı olur.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntünün dosya formatını döndürür ve işleme ve uyumluluk kontrolleri için gerekli meta verileri sağlar. Bu özellik, farklı sistem ve uygulamalarda görüntü verisini etkili bir şekilde işlemek için uygun kod çözme ve kodlama stratejilerini belirlemede etkilidir.

**Returns:**
long - dosya formatı
### cacheData() {#cacheData--}
```
public void cacheData()
```


Veriyi önbelleğe al ve temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) üzerinden veri yüklemesinin bir daha gerçekleşmeyeceğini garanti et. Bu optimizasyon, gereksiz veri alma işlemlerini ortadan kaldırarak performansı artırır; özellikle görüntü verisine sık erişim gerektiren senaryolarda faydalıdır.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntüyü belirtilen boyutlara sığacak şekilde yeniden boyutlandır ve en boy oranını koru. Bu yöntem, görüntünün oranlarını bozmadan boyutunu ayarlamanın pratik bir yolunu sunar ve istenen boyutlara göre optimal görüntüleme veya depolamayı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Belirtilen dikdörtgeni kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Belirtilen paleti görüntüye uygular, estetik veya işlevsel amaçlar için renk şemalarının özelleştirilmesini sağlar. Bu yöntem, çeşitli tasarım veya uygulama gereksinimlerine uygun renk paletlerini yönetmede esneklik sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

