---
title: "WmfRasterizationOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Wmf rasteriseringsalternativ."
type: docs
weight: 55
url: /sv/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Wmf rasteriseringsalternativ.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Initierar en ny instans av klassen `WmfRasterizationOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Hämtar eller anger WMF-renderingsläget. |
| [setRenderMode(int value)](#setRenderMode-int-) | Hämtar eller anger WMF-renderingsläget. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopierar detta till `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Initierar en ny instans av klassen `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Hämtar eller anger WMF-renderingsläget.

Värde: WMF-renderingsläget.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Hämtar eller anger WMF-renderingsläget.

Värde: WMF-renderingsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text kommer att konverteras till former.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Bakgrundsfärgen på ritytan.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Sidstorleken.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Om inbäddad emf finns, rendera emf; annars rendera wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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

