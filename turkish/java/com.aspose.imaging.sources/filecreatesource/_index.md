---
title: "FileCreateSource"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Oluşturma için bir dosya kaynağını temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Oluşturma için bir dosya kaynağını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Yeni bir `FileCreateSource` sınıfı örneği başlatır. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Yeni bir `FileCreateSource` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFilePath()](#getFilePath--) | Oluşturulacak dosya yolunu alır. |
| [isTemporal()](#isTemporal--) | Dosyanın geçici olup olmayacağını gösteren bir değeri alır. |
| [getStreamContainer()](#getStreamContainer--) | Akış konteynerini alır. |

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

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Yeni bir `FileCreateSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Oluşturulacak dosya yolu. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Yeni bir `FileCreateSource` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Oluşturulacak dosya yolu. |
| isTemporal | boolean | `true` olarak ayarlanırsa oluşturulan dosya geçici olur. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Oluşturulacak dosya yolunu alır.

Değer: Oluşturulacak dosya yolu.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Dosyanın geçici olup olmayacağını gösteren bir değeri alır.

Değer: Dosya geçici olacaksa `true`; aksi takdirde `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Akış konteynerini alır.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Dikkatli kullanın. Alımdan sonra akış konteynerini serbest bırakmanız gerekir.
