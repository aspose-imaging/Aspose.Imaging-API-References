---
title: "DisposableObject"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Atılabilir nesneyi temsil eder."
type: docs
weight: 40
url: /tr/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Atılabilir nesneyi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDisposed()](#getDisposed--) | Bu örneğin serbest bırakılmış olup olmadığını gösteren bir değer alır. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin serbest bırakılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - `true` ise serbest bırakılmış; aksi takdirde `false`.
### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose metodunu çağırır.

### dispose() {#dispose--}
```
public void dispose()
```


Mevcut örneği serbest bırakır.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

