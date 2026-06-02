---
title: "VectorRasterizationOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di rasterizzazione vettoriale."
type: docs
weight: 52
url: /it/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Le opzioni di rasterizzazione vettoriale. Si prega di notare che [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) non deriverà più da [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) a partire dalla versione Aspose.Imaging 24.12.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Restituisce la modalità di smussatura. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Imposta la modalità di smussatura. |
| [getBorderX()](#getBorderX--) | Restituisce o imposta il bordo X. |
| [setBorderX(float value)](#setBorderX-float-) | Restituisce o imposta il bordo X. |
| [getBorderY()](#getBorderY--) | Restituisce o imposta il bordo Y. |
| [setBorderY(float value)](#setBorderY-float-) | Restituisce o imposta il bordo Y. |
| [getCenterDrawing()](#getCenterDrawing--) | Restituisce un valore che indica se il disegno è centrato. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Imposta un valore che indica se il disegno è centrato. |
| [getPageHeight()](#getPageHeight--) | Restituisce l'altezza della pagina. |
| [setPageHeight(float value)](#setPageHeight-float-) | Imposta l'altezza della pagina. |
| [getPageSize()](#getPageSize--) | Restituisce la dimensione della pagina. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Imposta la dimensione della pagina. |
| [getPageWidth()](#getPageWidth--) | Restituisce la larghezza della pagina. |
| [setPageWidth(float value)](#setPageWidth-float-) | Imposta la larghezza della pagina. |
| [getBackgroundColor()](#getBackgroundColor--) | Restituisce un colore di sfondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta un colore di sfondo. |
| [getDrawColor()](#getDrawColor--) | Restituisce un colore di primo piano. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Imposta un colore di primo piano. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Restituisce il suggerimento di rendering del testo. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Imposta il suggerimento di rendering del testo. |
| [getPositioning()](#getPositioning--) | Restituisce il posizionamento. |
| [setPositioning(int value)](#setPositioning-int-) | Imposta il posizionamento. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Restituisce la mappatura di sostituzione del testo. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Imposta la mappatura di sostituzione del testo. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia questa istanza in `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Crea una copia superficiale dell'oggetto. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Restituisce la modalità di smussatura.

**Returns:**
int - la modalità di smussatura.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Imposta la modalità di smussatura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la modalità di smussatura. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usare Aspose.Imaging.Image.Load è un modo unificato per caricare un'immagine.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Imposta il colore predefinito di sfondo per un'immagine. Il valore predefinito è bianco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Imposta la dimensione della pagina
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anti-aliasing è applicato a linee, curve e ai bordi delle aree riempite.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Riduci la dimensione dell'immagine di 10 volte, cioè la dimensione di output sarà il 10% della dimensione originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Salva in un file PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Restituisce o imposta il bordo X.

**Returns:**
float - Il bordo X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Restituisce o imposta il bordo X.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il bordo X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Restituisce o imposta il bordo Y.

**Returns:**
float - Il bordo Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Restituisce o imposta il bordo Y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il bordo Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Restituisce un valore che indica se il disegno è centrato.

**Returns:**
boolean - un valore che indica se il disegno è centrato.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Imposta un valore che indica se il disegno è centrato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se il disegno è centrato. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Restituisce l'altezza della pagina.

**Returns:**
float - l'altezza della pagina.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Imposta l'altezza della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'altezza della pagina. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Restituisce la dimensione della pagina.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Imposta la dimensione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | la dimensione della pagina. |


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

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Restituisce la larghezza della pagina.

**Returns:**
float - la larghezza della pagina.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Imposta la larghezza della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | la larghezza della pagina. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Restituisce un colore di sfondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta un colore di sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un colore di sfondo. |


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

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Restituisce un colore di primo piano.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Imposta un colore di primo piano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un colore di primo piano. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Restituisce il suggerimento di rendering del testo.

Valore: Il suggerimento di rendering del testo.

**Returns:**
int - il suggerimento di rendering del testo.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Imposta il suggerimento di rendering del testo.

Valore: Il suggerimento di rendering del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il suggerimento di rendering del testo. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usare Aspose.Imaging.Image.Load è un modo unificato per caricare un'immagine.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Per rasterizzare SVG è necessario specificare le opzioni di rasterizzazione.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Imposta il colore predefinito di sfondo per un'immagine. Il valore predefinito è bianco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Imposta la dimensione della pagina
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // L'anti-aliasing è applicato a linee, curve e ai bordi delle aree riempite.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Ogni carattere è disegnato usando il suo bitmap di glifo antialiasato senza hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Riduci la dimensione dell'immagine di 10 volte, cioè la dimensione di output sarà il 10% della dimensione originale.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Salva in un file PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Restituisce il posizionamento.

Valore: Il posizionamento.

**Returns:**
int - il posizionamento.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Imposta il posizionamento.

Valore: Il posizionamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il posizionamento. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Restituisce la mappatura di sostituzione del testo.

Valore: La mappatura di sostituzione del testo.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - la mappatura di sostituzione del testo.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Imposta la mappatura di sostituzione del testo.

Valore: La mappatura di sostituzione del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.HashMap<java.lang.String,java.lang.String> | la mappatura di sostituzione del testo. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia questa istanza in `vectorRasterizationOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Le opzioni di rasterizzazione vettoriale. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Crea una copia superficiale dell'oggetto.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
