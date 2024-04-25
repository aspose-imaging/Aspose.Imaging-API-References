---
title: SampleRoundingMode
second_title: Aspose.Imaging for Java API Reference
description: Defines a way in which an n-bit value is converted to an 8-bit value.
type: docs
weight: 17
url: /com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Defines a way in which an n-bit value is converted to an 8-bit value.
## Fields

| Field | Description |
| --- | --- |
| [Extrapolate](#Extrapolate) | Extrapolate an 8-bit value to fit it into n bits, where 1 < n < 8. |
| [Truncate](#Truncate) | Truncate an 8-bit value to fit it into n bits, where 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Extrapolate an 8-bit value to fit it into n bits, where 1 < n < 8. The number of all possible 8-bit values is 1 << 8 = 256, from 0 to 255. The number of all possible n-bit values is 1 << n, from 0 to (1 << n) - 1. The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Truncate an 8-bit value to fit it into n bits, where 1 < n < 8. The number of all possible n-bit values is 1 << n, from 0 to (1 << n) - 1. The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 & ((1 << n) - 1).

