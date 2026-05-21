---
title: "WmfRasterizationOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die WMF-Rasterisierungsoptionen."
type: docs
weight: 55
url: /de/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Die WMF-Rasterisierungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Initialisiert eine neue Instanz der Klasse `WmfRasterizationOptions`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Liest oder setzt den WMF‑Rendermodus. |
| [setRenderMode(int value)](#setRenderMode-int-) | Liest oder setzt den WMF‑Rendermodus. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopiert dies zu `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Initialisiert eine neue Instanz der Klasse `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Liest oder setzt den WMF‑Rendermodus.

Wert: Der WMF‑Rendermodus.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Liest oder setzt den WMF‑Rendermodus.

Wert: Der WMF‑Rendermodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopiert dies zu `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

