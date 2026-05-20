---
title: "WmfRasterizationOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di rasterizzazione Wmf."
type: docs
weight: 55
url: /it/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Le opzioni di rasterizzazione Wmf.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Inizializza una nuova istanza della classe `WmfRasterizationOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Ottiene o imposta la modalità di rendering WMF. |
| [setRenderMode(int value)](#setRenderMode-int-) | Ottiene o imposta la modalità di rendering WMF. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia questo in `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Inizializza una nuova istanza della classe `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Ottiene o imposta la modalità di rendering WMF.

Valore: La modalità di rendering WMF.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Ottiene o imposta la modalità di rendering WMF.

Valore: La modalità di rendering WMF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Il testo verrà convertito in forme.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La dimensione della pagina.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Se esiste un emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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

