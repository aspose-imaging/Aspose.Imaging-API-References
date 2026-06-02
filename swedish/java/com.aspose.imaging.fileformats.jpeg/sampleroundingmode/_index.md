---
title: "SampleRoundingMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Extrapolate](#Extrapolate) | Extrapolera ett 8-bitars värde för att passa in i n bitar, där 1 < n < 8. |
| [Truncate](#Truncate) | Trunkera ett 8-bitars värde för att passa in i n bitar, där 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Extrapolera ett 8-bitars värde för att passa in i n bitar, där 1 < n < 8. Antalet möjliga 8-bitars värden är 1 << 8 = 256, från 0 till 255. Antalet möjliga n-bitars värden är 1 << n, från 0 till (1 << n) - 1. Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Trunkera ett 8-bitars värde för att passa in i n bitar, där 1 < n < 8. Antalet möjliga n-bitars värden är 1 << n, från 0 till (1 << n) - 1. Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 & ((1 << n) - 1).

