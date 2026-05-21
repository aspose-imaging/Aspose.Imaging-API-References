---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce opzioni di configurazione per il filtro Auto White Balance."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Fornisce opzioni di configurazione per il filtro Auto White Balance. Consente la regolazione dei parametri di stretching del contrasto e della scala dei canali per migliorare l'aspetto delle immagini digitali.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Inizializza una nuova istanza della classe [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Ottiene il percentile alto target per lo stretching del contrasto. |
| [getTargetValue()](#getTargetValue--) | Ottiene il valore target per il percentile alto. |
| [getMaxScale()](#getMaxScale--) | Ottiene il fattore di scala massimo per ciascun canale. |
| [getLowPercentile()](#getLowPercentile--) | Il percentile basso per il punto nero, utilizzato per la protezione delle aree scure (predefinito: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Offset dal percentile basso al di sotto del quale i pixel scuri non vengono allungati (protezione). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Inizializza una nuova istanza della classe [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowPercentile | int | Il percentile basso per il punto nero, utilizzato per la protezione delle aree scure (predefinito: 3). |
| targetHighPercentile | int | Il percentile alto target per lo stretching del contrasto (predefinito 97). |
| targetValue | int | Il valore target per il percentile alto (default 255). |
| maxScale | float | Il fattore di scala massimo per ciascun canale (default 1.4f). |
| protectedDarkOffset | int | Offset dal percentile basso al di sotto del quale i pixel scuri non vengono allungati (protezione). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Restituisce il percentile alto target per lo stretching del contrasto. Determina quale percentile di luminosità sarà mappato al valore target.

**Returns:**
int - il percentile alto target per lo stretching del contrasto.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Restituisce il valore target per il percentile alto. Questo valore sarà usato come riferimento bianco per lo stretching del contrasto.

**Returns:**
int - il valore target per il percentile alto.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Restituisce il fattore di scala massimo per ciascun canale. Limita l'amplificazione di qualsiasi canale per evitare spostamenti di colore eccessivi.

**Returns:**
float - il fattore di scala massimo per ciascun canale.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Il percentile basso per il punto nero, utilizzato per la protezione delle aree scure (predefinito: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Offset dal percentile basso al di sotto del quale i pixel scuri non vengono allungati (protezione).

**Returns:**
int
