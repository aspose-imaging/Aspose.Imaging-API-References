---
title: "EmfRasterizationOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Emf-rasteriseringsalternativen."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Emf-rasteriseringsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Hämtar eller anger renderingsläget. |
| [setRenderMode(int value)](#setRenderMode-int-) | Hämtar eller anger renderingsläget. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopierar detta till `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Hämtar eller anger renderingsläget.

**Returns:**
int – renderingsläget.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Hämtar eller anger renderingsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Renderingsläget. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla bildtyper inklusive EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Ställ in den horisontella marginalen
    rasterizationOptions.setBorderX(50);

    // Ställ in den vertikala marginalen
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopierar detta till `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

