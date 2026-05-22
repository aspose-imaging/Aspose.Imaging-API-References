---
title: "Html5CanvasOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle HTML5 Canvas dosyalarını zahmetsizce oluşturun, formlar, metin, görüntüler, animasyonlar ve bağlantılar gibi öğeleri sorunsuz bir şekilde birleştirmenizi sağlar."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

API'mizle HTML5 Canvas dosyalarını zahmetsizce oluşturun, formlar, metin, görüntüler, animasyonlar ve bağlantılar gibi öğeleri sorunsuz bir şekilde birleştirmenizi sağlar. Etiket tanımlayıcısı ve kodlama ayarları desteği dahil olmak üzere güçlü özelliklerden yararlanın, web projeleriniz için optimal performans ve özelleştirme sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Yeni bir [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) sınıfının örneğini başlatır. |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Yeni bir `ImageOptionsBase` sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Canvas etiket tanımlayıcısını alır. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Canvas etiket tanımlayıcısını ayarlar. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değeri alır. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değeri ayarlar. |
| [getEncoding()](#getEncoding--) | Kodlamayı alır. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Kodlamayı ayarlar. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Herhangi bir vektör görüntüsü (SVG, WMF, CMX, vb.) Canvas görüntüleriniz için kaynak olarak kullanılabilir. Aşağıdaki kod basit bir Canvas görüntüsü oluşturur.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
HTML sayfasına birden fazla Canvas görüntüsü yerleştirebilir veya mevcut sayfayı güncelleyebilirsiniz. Bunu yapmak için yalnızca Canvas etiketini dışa aktarmanız gerekir.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


Yeni bir [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) sınıfının örneğini başlatır.

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Yeni bir `ImageOptionsBase` sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Görüntü seçenekleri. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Canvas etiket tanımlayıcısını alır.

**Returns:**
java.lang.String - canvas etiket tanımlayıcısı.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Canvas etiket tanımlayıcısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | canvas etiket tanımlayıcısı. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değeri alır.

**Returns:**
boolean - tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değer.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | tam HTML sayfasının oluşturulup oluşturulmayacağını gösteren bir değer. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
HTML sayfasına birden fazla Canvas görüntüsü yerleştirebilir veya mevcut sayfayı güncelleyebilirsiniz. Bunu yapmak için yalnızca Canvas etiketini dışa aktarmanız gerekir.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Kodlamayı alır.

**Returns:**
java.nio.charset.Charset - kodlama.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Kodlamayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset | kodlama. |

