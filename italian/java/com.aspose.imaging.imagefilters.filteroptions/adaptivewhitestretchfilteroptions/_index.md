---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce opzioni per configurare il filtro Adaptive White Stretch."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Fornisce opzioni per configurare il filtro Adaptive White Stretch. Consente la personalizzazione dei parametri di stretching dell'istogramma per migliorare il livello del bianco e aumentare la leggibilità di immagini di documenti con testo tenue o a basso contrasto.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Inizializza una nuova istanza della classe AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Inizializza una nuova istanza della classe AdaptiveWhiteStretchFilter. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Restituisce un valore che indica se il filtro opera in modalità scala di grigi. |
| [getLowPercentile()](#getLowPercentile--) | Restituisce il percentile inferiore per il calcolo del punto nero. |
| [getHighPercentile()](#getHighPercentile--) | Restituisce il percentile superiore per il calcolo del punto bianco. |
| [getTargetWhite()](#getTargetWhite--) | Restituisce il valore bianco target che lo stretching mira a raggiungere. |
| [getMaxScale()](#getMaxScale--) | Restituisce la scala di luminosità massima consentita. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Inizializza una nuova istanza della classe AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Inizializza una nuova istanza della classe AdaptiveWhiteStretchFilter.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isGrayscale | boolean | Indica se il filtro deve operare in modalità scala di grigi. |
| lowPercentile | int | Percentile inferiore per il punto nero (es. 10). |
| highPercentile | int | Percentile superiore per il punto bianco (es. 90). |
| targetWhite | int | Valore bianco target (es. 240). |
|  | maxScale | float | Scala di luminosità massima consentita (es. 1.7). |

--------------------

L'algoritmo allunga l'istogramma in modo che il percentile bianco si avvicini a `targetWhite`, ma senza superare `maxScale` per evitare un'eccessiva luminosità. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Restituisce un valore che indica se il filtro opera in modalità scala di grigi.

**Returns:**
boolean - un valore che indica se il filtro opera in modalità scala di grigi.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Restituisce il percentile inferiore per il calcolo del punto nero. I valori dei pixel al di sotto di questo percentile sono considerati neri durante l'allungamento.

**Returns:**
int - il percentile inferiore per il calcolo del punto nero.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Restituisce il percentile superiore per il calcolo del punto bianco. I valori dei pixel al di sopra di questo percentile sono considerati bianchi durante l'allungamento.

**Returns:**
int - il percentile superiore per il calcolo del punto bianco.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Restituisce il valore bianco target che lo stretching mira a raggiungere.

**Returns:**
int - il valore bianco target che l'allungamento mira a raggiungere.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Restituisce la scala di luminosità massima consentita. L'allungamento effettivo non supererà questo fattore, per evitare un'eccessiva luminosità.

**Returns:**
float - la scala di luminosità massima consentita.
