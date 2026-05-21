---
title: "SampleRoundingMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define una forma en que un valor de n bits se convierte a un valor de 8 bits."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Define una forma en que un valor de n bits se convierte a un valor de 8 bits.
## Campos

| Campo | Descripción |
| --- | --- |
| [Extrapolate](#Extrapolate) | Extrapolar un valor de 8 bits para ajustarlo a n bits, donde 1 < n < 8. |
| [Truncate](#Truncate) | Truncar un valor de 8 bits para ajustarlo a n bits, donde 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Extrapolar un valor de 8 bits para ajustarlo a n bits, donde 1 < n < 8. El número de todos los valores posibles de 8 bits es 1 << 8 = 256, de 0 a 255. El número de todos los valores posibles de n bits es 1 << n, de 0 a (1 << n) - 1. El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Truncar un valor de 8 bits para ajustarlo a n bits, donde 1 < n < 8. El número de todos los valores posibles de n bits es 1 << n, de 0 a (1 << n) - 1. El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 & ((1 << n) - 1).

