---
title: "InterpolationMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione com.aspose.imaging.InterpolationMode specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate."
type: docs
weight: 65
url: /it/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

L'enumerazione `com.aspose.imaging.InterpolationMode` specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Invalid](#Invalid) | Modalità di interpolazione non valida. |
| [Default](#Default) | Specifica la modalità predefinita. |
| [Low](#Low) | Specifica l'interpolazione a bassa qualità. |
| [High](#High) | Specifica l'interpolazione ad alta qualità. |
| [Bilinear](#Bilinear) | Specifica l'interpolazione bilineare. |
| [Bicubic](#Bicubic) | Specifica l'interpolazione bicubica. |
| [NearestNeighbor](#NearestNeighbor) | Specifica l'interpolazione nearest-neighbor. |
| [HighQualityBilinear](#HighQualityBilinear) | Specifica un'interpolazione bilineare di alta qualità. |
| [HighQualityBicubic](#HighQualityBicubic) | Specifica un'interpolazione bicubica di alta qualità. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Modalità di interpolazione non valida.

### Default {#Default}
```
public static final int Default
```


Specifica la modalità predefinita.

### Low {#Low}
```
public static final int Low
```


Specifica l'interpolazione a bassa qualità.

### High {#High}
```
public static final int High
```


Specifica l'interpolazione ad alta qualità.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Specifica l'interpolazione bilineare. Non viene eseguito alcun prefiltraggio. Questa modalità non è adatta per ridurre un'immagine al di sotto del 50% della sua dimensione originale.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Specifica l'interpolazione bicubica. Non viene eseguito alcun prefiltraggio. Questa modalità non è adatta per ridurre un'immagine al di sotto del 25% della sua dimensione originale.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Specifica l'interpolazione nearest-neighbor.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Specifica un'interpolazione bilineare di alta qualità. Viene eseguito il prefiltraggio per garantire una riduzione di alta qualità.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Specifica un'interpolazione bicubica di alta qualità. Viene eseguito il prefiltraggio per garantire una riduzione di alta qualità. Questa modalità produce le immagini trasformate della massima qualità.

