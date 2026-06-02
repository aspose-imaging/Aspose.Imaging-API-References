---
title: "DxfOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'API per la creazione di immagini vettoriali DXF (Drawing Interchange Format) offre soluzioni su misura per generare file di disegno AutoCAD con precisione e flessibilità."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

L'API per la creazione di immagini vettoriali DXF (Drawing Interchange Format) offre soluzioni su misura per generare file di disegno AutoCAD con precisione e flessibilità. Progettata specificamente per lavorare con linee di testo e curve di Bézier, gli sviluppatori possono manipolare questi elementi in modo efficiente, contare i punti Bézier e convertire le curve in polilinee per un'esportazione senza interruzioni, garantendo compatibilità e fedeltà nelle immagini vettoriali DXF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Costruttore di coping |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Quanti punti generare durante la conversione delle curve Bézier in polilinee, minimo 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Quanti punti generare durante la conversione delle curve Bézier in polilinee, minimo 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Funziona quando \#textAsLines è impostato su `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Funziona quando \#textAsLines è impostato su `true`. |
| [getTextAsLines()](#getTextAsLines--) | Se il testo deve essere esportato come contorni costituiti da polilinee (predefinito) o come entità TEXT modificabili di Autocad. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Se il testo deve essere esportato come contorni costituiti da polilinee (predefinito) o come entità TEXT modificabili di Autocad. |

## Example: This example demonstrates export to Dxf format

``` java

//Crea un'istanza Image e inizializzala con un file immagine esistente dalla posizione su disco.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Costruttore di coping

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Le opzioni di origine per coping |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Quanti punti generare durante la conversione delle curve Bézier in polilinee, minimo 4. Utilizzato quando (/) e (/) sono entrambi /// impostati su `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Quanti punti generare durante la conversione delle curve Bézier in polilinee, minimo 4. Utilizzato quando (/) e (/) sono entrambi /// impostati su `true`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Funziona quando \#textAsLines è impostato su `true`. Se convertire le curve Bézier nei contorni di testo in polilinee multipunto.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Funziona quando \#textAsLines è impostato su `true`. Se convertire le curve Bézier nei contorni di testo in polilinee multipunto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Se il testo deve essere esportato come contorni costituiti da polilinee (predefinito) o come entità TEXT modificabili di Autocad. Se questa opzione è impostata

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Se il testo deve essere esportato come contorni costituiti da polilinee (predefinito) o come entità TEXT modificabili di Autocad. Se questa opzione è impostata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

