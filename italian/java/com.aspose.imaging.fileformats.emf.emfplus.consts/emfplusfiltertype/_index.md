---
title: "EmfPlusFilterType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione FilterType definisce i tipi di algoritmi di filtraggio che possono essere usati per il miglioramento della qualità di testo e grafica e per il rendering delle immagini."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

L'enumerazione FilterType definisce i tipi di algoritmi di filtraggio che possono essere usati per il miglioramento della qualità di testo e grafica e per il rendering delle immagini.
## Campi

| Campo | Descrizione |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Specifica che il filtraggio non viene eseguito. |
| [FilterTypePoint](#FilterTypePoint) | Specifica che ogni pixel di destinazione viene calcolato campionando il pixel più vicino dell'immagine sorgente. |
| [FilterTypeLinear](#FilterTypeLinear) | Specifica che viene eseguita l'interpolazione lineare utilizzando la media ponderata di un'area 2x2 di pixel intorno al pixel sorgente. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Specifica che ogni pixel dell'immagine sorgente contribuisce in modo uguale all'immagine di destinazione. |
| [FilterTypeBox](#FilterTypeBox) | Specifica un algoritmo di filtro a scatola, in cui ogni pixel di destinazione viene calcolato facendo la media di un rettangolo di pixel sorgente. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | Specifica che viene utilizzato un filtro a tenda a 4 campioni. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | Specifica che viene utilizzato un filtro gaussiano a 4 campioni, che crea un effetto di sfocatura su un'immagine. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Specifica che il filtraggio non viene eseguito.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Specifica che ogni pixel di destinazione viene calcolato campionando il pixel più vicino dell'immagine sorgente.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Specifica che viene eseguita l'interpolazione lineare utilizzando la media ponderata di un'area 2x2 di pixel intorno al pixel sorgente.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Specifica che ogni pixel dell'immagine sorgente contribuisce in modo uguale all'immagine di destinazione. Questo è il più lento degli algoritmi di filtraggio.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Specifica un algoritmo di filtro a scatola, in cui ogni pixel di destinazione è calcolato facendo la media di un rettangolo di pixel di origine. Questo algoritmo è utile solo quando si riduce la dimensione di un'immagine.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


Specifica che viene utilizzato un filtro a tenda a 4 campioni.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


Specifica che viene utilizzato un filtro gaussiano a 4 campioni, che crea un effetto di sfocatura su un'immagine.

