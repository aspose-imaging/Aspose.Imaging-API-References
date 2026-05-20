---
title: "EmfPlusInterpolationMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione InterpolationMode definisce i metodi per eseguire il ridimensionamento, inclusi allungamento e riduzione."
type: docs
weight: 29
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

L'enumerazione InterpolationMode definisce i modi per eseguire il ridimensionamento, inclusi allungamento e riduzione.
## Campi

| Campo | Descrizione |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Specifica la modalità di interpolazione predefinita, definita come InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Specifica una modalità di interpolazione a bassa qualità, definita come InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Specifica una modalità di interpolazione ad alta qualità, definita come InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Specifica l'interpolazione bilineare, che utilizza il più vicino vicinato 2x2 di pixel noti intorno al pixel interpolato. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Specifica l'interpolazione bicubica, che utilizza il più vicino gruppo 4x4 di pixel noti intorno al pixel interpolato. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Specifica l'interpolazione nearest-neighbor, che utilizza solo il valore del pixel più vicino al pixel interpolato. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Specifica l'interpolazione bilineare con prefiltraggio. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Specifica l'interpolazione bicubica con prefiltraggio, che produce il risultato di qualità più alta tra queste opzioni. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Specifica la modalità di interpolazione predefinita, definita come InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Specifica una modalità di interpolazione a bassa qualità, definita come InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Specifica una modalità di interpolazione ad alta qualità, definita come InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Specifica l'interpolazione bilineare, che utilizza il più vicino gruppo 2x2 di pixel noti intorno al pixel interpolato. La media ponderata di questi 4 valori di pixel noti determina il valore da assegnare al pixel interpolato. Il risultato appare più liscio rispetto a InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Specifica l'interpolazione bicubica, che utilizza il più vicino gruppo 4x4 di pixel noti intorno al pixel interpolato. La media ponderata di questi 16 valori di pixel noti determina il valore da assegnare al pixel interpolato. Poiché i pixel noti si trovano a distanze variabili dal pixel interpolato, i pixel più vicini ricevono un peso maggiore nel calcolo. Il risultato appare più liscio rispetto a InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Specifica l'interpolazione nearest-neighbor, che utilizza solo il valore del pixel più vicino al pixel interpolato. Questa modalità duplica o rimuove semplicemente i pixel, producendo il risultato di qualità più bassa tra queste opzioni.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Specifica l'interpolazione bilineare con prefiltraggio.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Specifica l'interpolazione bicubica con prefiltraggio, che produce il risultato di qualità più alta tra queste opzioni.

