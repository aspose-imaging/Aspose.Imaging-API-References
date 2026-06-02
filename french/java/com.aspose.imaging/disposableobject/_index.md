---
title: "DisposableObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente un objet jetable."
type: docs
weight: 40
url: /fr/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Représente un objet jetable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
booléen - `true` si libéré ; sinon, `false`.
### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### dispose() {#dispose--}
```
public void dispose()
```


Libère l'instance actuelle.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Il s'agit de Font et Brush pour dessiner du texte sur des images individuelles.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Créer 5 cadres
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Créer une image PNG et y dessiner le numéro de page.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Créer un cadre basé sur l'image PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Ajouter le cadre à l'image TIFF.
        tiffImage.addFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Supprimons‑le.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // N'oubliez pas de libérer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

