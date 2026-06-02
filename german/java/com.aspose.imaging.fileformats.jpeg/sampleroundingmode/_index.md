---
title: "SampleRoundingMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert eine Methode, wie ein n‑Bit‑Wert in einen 8‑Bit‑Wert umgewandelt wird."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Definiert eine Methode, wie ein n‑Bit‑Wert in einen 8‑Bit‑Wert umgewandelt wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Extrapolate](#Extrapolate) | Extrapoliere einen 8‑Bit‑Wert, um ihn in n Bits zu passen, wobei 1 < n < 8 gilt. |
| [Truncate](#Truncate) | Schneide einen 8‑Bit‑Wert ab, um ihn in n Bits zu passen, wobei 1 < n < 8 gilt. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Extrapoliere einen 8‑Bit‑Wert, um ihn in n Bits zu passen, wobei 1 < n < 8 gilt. Die Anzahl aller möglichen 8‑Bit‑Werte beträgt 1 << 8 = 256, von 0 bis 255. Die Anzahl aller möglichen n‑Bit‑Werte beträgt 1 << n, von 0 bis (1 << n) - 1. Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist gleich Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Schneide einen 8‑Bit‑Wert ab, um ihn in n Bits zu passen, wobei 1 < n < 8 gilt. Die Anzahl aller möglichen n‑Bit‑Werte beträgt 1 << n, von 0 bis (1 << n) - 1. Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist gleich Vn = V8 & ((1 << n) - 1).

