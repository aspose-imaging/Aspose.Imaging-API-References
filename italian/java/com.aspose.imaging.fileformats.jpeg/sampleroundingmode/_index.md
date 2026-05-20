---
title: "SampleRoundingMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un metodo per convertire un valore n-bit in un valore a 8 bit."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Definisce un metodo per convertire un valore n-bit in un valore a 8 bit.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Extrapolate](#Extrapolate) | Estrapola un valore a 8 bit per adattarlo a n bit, dove 1 < n < 8. |
| [Truncate](#Truncate) | Tronca un valore a 8 bit per adattarlo a n bit, dove 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Estrapola un valore a 8 bit per adattarlo a n bit, dove 1 < n < 8. Il numero di tutti i possibili valori a 8 bit è 1 << 8 = 256, da 0 a 255. Il numero di tutti i possibili valori a n bit è 1 << n, da 0 a (1 << n) - 1. Il valore a n bit più ragionevole Vn corrispondente a un valore a 8 bit V8 è pari a Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Tronca un valore a 8 bit per adattarlo a n bit, dove 1 < n < 8. Il numero di tutti i possibili valori a n bit è 1 << n, da 0 a (1 << n) - 1. Il valore a n bit più ragionevole Vn corrispondente a un valore a 8 bit V8 è pari a Vn = V8 & ((1 << n) - 1).

