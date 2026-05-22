---
title: "SvgResourceKeeperCallback"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Kaynak tutucu geri arama"
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Kaynak tutucu geri arama
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Görüntü kaynağı dışa aktarma için hazır olduğunda çağrılır. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Yazı tipi kaynağı dışa aktarma için hazır olduğunda çağrılır. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | SVG belgesi dışa aktarma için hazır olduğunda çağrılır. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Görüntü kaynağı dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageData | byte[] | Kaynak verisi. |
| imageType | int | Görüntünün türü. |
| suggestedFileName | java.lang.String | Önerilen dosyanın adı. |
| useEmbeddedImage | boolean[] | `true` olarak ayarlanırsa gömülü görüntü kullanılmalıdır. |

**Returns:**
java.lang.String - Kaydedilen kaynağa giden yolu döndürür. Yol, hedef SVG belgesine göreceli olmalıdır.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Yazı tipi kaynağı dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | com.aspose.svg.options.FontStoringArgs | Yazı tipi depolama seçenekleri. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


SVG belgesi dışa aktarma için hazır olduğunda çağrılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlData | byte[] | SVG verisi. |
| suggestedFileName | java.lang.String | Önerilen dosyanın adı. |

**Returns:**
java.lang.String - Kaydedilen SVG belgesine giden yolu döndürür.
