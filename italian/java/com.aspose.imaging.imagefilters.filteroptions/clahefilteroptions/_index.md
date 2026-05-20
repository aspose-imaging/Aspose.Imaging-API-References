---
title: "ClaheFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce opzioni per configurare il filtro Contrast-Limited Adaptive Histogram Equalization CLAHE."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Fornisce opzioni per configurare il filtro Contrast-Limited Adaptive Histogram Equalization (CLAHE).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Inizializza una nuova istanza della classe [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) con i parametri specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Restituisce un valore che indica se il filtro opera in modalità scala di grigi. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Restituisce il numero di tile nella direzione orizzontale. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Restituisce il numero di tile nella direzione verticale. |
| [getClipLimit()](#getClipLimit--) | Restituisce la soglia di limitazione del contrasto. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Inizializza una nuova istanza della classe [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) con i parametri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isGrayscale | boolean | Indica se il filtro deve operare in modalità scala di grigi. |
| tilesNumberHorizontal | int | Numero di tile orizzontalmente. Il valore predefinito è 8. |
| tilesNumberVertical | int | Numero di tile verticalmente. Il valore predefinito è 8. |
| clipLimit | double | Soglia di limitazione del contrasto. Il valore predefinito è 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Restituisce un valore che indica se il filtro opera in modalità scala di grigi.

**Returns:**
boolean - un valore che indica se il filtro opera in modalità scala di grigi.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Restituisce il numero di tile nella direzione orizzontale. Determina in quante regioni l'immagine è suddivisa orizzontalmente per l'equalizzazione locale del contrasto.

**Returns:**
int - il numero di tile nella direzione orizzontale.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Restituisce il numero di tile nella direzione verticale. Determina in quante regioni l'immagine è suddivisa verticalmente per l'equalizzazione locale del contrasto.

**Returns:**
int - il numero di tile nella direzione verticale.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Restituisce la soglia di limitazione del contrasto. Valori più alti consentono più contrasto; valori più bassi limitano il miglioramento per evitare l'amplificazione del rumore.

**Returns:**
double - la soglia di limitazione del contrasto.
