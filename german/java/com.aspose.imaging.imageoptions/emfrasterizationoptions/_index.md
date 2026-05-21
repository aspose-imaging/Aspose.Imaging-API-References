---
title: "EmfRasterizationOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die EMF‑Rasterungsoptionen."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Die EMF‑Rasterungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Ruft den Rendermodus ab oder legt ihn fest. |
| [setRenderMode(int value)](#setRenderMode-int-) | Ruft den Rendermodus ab oder legt ihn fest. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopiert dies zu `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Ruft den Rendermodus ab oder legt ihn fest.

**Returns:**
int – der Rendermodus.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Ruft den Rendermodus ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Rendermodus. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen einschließlich EMF zu laden.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Setzen Sie den horizontalen Rand
    rasterizationOptions.setBorderX(50);

    // Setzen Sie den vertikalen Rand
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


Kopiert dies zu `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

