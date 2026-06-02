---
title: "JpegLsInterleaveMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce la modalità di interlacciamento per i dati pixel a colori multicomponente."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Definisce la modalità di interlacciamento per dati pixel multicomponente (colore).
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | I dati sono codificati e memorizzati come componente per componente: RRRGGGBBB. |
| [Line](#Line) | La modalità di interlacciamento è per riga. |
| [Sample](#Sample) | I dati sono codificati e memorizzati per campione. |
### None {#None}
```
public static final int None
```


I dati sono codificati e memorizzati come componente per componente: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


La modalità di interlacciamento è per riga. Una riga completa di ciascun componente è codificata prima di passare alla riga successiva.

### Sample {#Sample}
```
public static final int Sample
```


I dati sono codificati e memorizzati per campione. Per le immagini a colori questo è il formato tipo RGBRGBRGB.

