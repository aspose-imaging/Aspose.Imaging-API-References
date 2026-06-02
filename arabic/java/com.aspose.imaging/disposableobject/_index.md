---
title: "DisposableObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل كائنًا يمكن التخلص منه."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

يمثل كائنًا يمكن التخلص منه.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [close()](#close--) | ينفّذ واجهة Closable ويمكن استخدامه في عبارة try-with-resources منذ JDK 1.7. |
| [dispose()](#dispose--) | يتخلص من الكائن الحالي. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
منطقي - `true` إذا تم التخلص؛ وإلا `false`.
### close() {#close--}
```
public void close()
```


ينفّذ واجهة Closable ويمكن استخدامه في عبارة try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### dispose() {#dispose--}
```
public void dispose()
```


يتخلص من الكائن الحالي.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.addFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. دعنا نزيله.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // لا تنسَ التخلص من الإطار إذا لم تقم بإضافته إلى TiffImage آخر.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

