---
title: "DisposableObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un oggetto eliminabile."
type: docs
weight: 40
url: /it/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Rappresenta un oggetto eliminabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDisposed()](#getDisposed--) | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere utilizzata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [dispose()](#dispose--) | Elimina l'istanza corrente. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Ottiene un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean - `true` se eliminato; altrimenti, `false`.
### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere utilizzata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### dispose() {#dispose--}
```
public void dispose()
```


Elimina l'istanza corrente.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Questo è Font e Brush per disegnare testo su singoli fotogrammi.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crea 5 fotogrammi
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crea un'immagine PNG e disegna il numero di pagina su di essa.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crea un fotogramma basato sull'immagine PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Aggiungi il fotogramma all'immagine TIFF.
        tiffImage.addFrame(frame);
    }

    // L'immagine è stata creata con un unico fotogramma predefinito. Rimuoviamolo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Non dimenticare di eliminare il fotogramma se non lo aggiungerai a un altro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

