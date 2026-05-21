---
title: "DisposableObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет объект, подлежащий освобождению."
type: docs
weight: 40
url: /ru/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Представляет объект, подлежащий освобождению.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getDisposed()](#getDisposed--) | Возвращает значение, указывающее, освобожден ли этот экземпляр. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Возвращает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean — `true`, если освобожден; иначе `false`.
### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает текущий экземпляр.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

