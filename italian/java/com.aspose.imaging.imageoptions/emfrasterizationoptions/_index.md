---
title: "EmfRasterizationOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di rasterizzazione Emf."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Le opzioni di rasterizzazione Emf.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Ottiene o imposta la modalità di rendering. |
| [setRenderMode(int value)](#setRenderMode-int-) | Ottiene o imposta la modalità di rendering. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia questo in `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Ottiene o imposta la modalità di rendering.

**Returns:**
int - La modalità di rendering.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Ottiene o imposta la modalità di rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di rendering. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Imposta il margine orizzontale
    rasterizationOptions.setBorderX(50);

    // Imposta il margine verticale
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


Copia questo in `vectorRasterizationOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

