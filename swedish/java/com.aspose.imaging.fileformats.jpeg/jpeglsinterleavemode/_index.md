---
title: "JpegLsInterleaveMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar interleavläget för flerkomponentfärgpikeldatat."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Definierar interleavläget för flerkomponent (färg) pixeldata.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Datan kodas och lagras som komponent för komponent: RRRGGGBBB. |
| [Line](#Line) | Interleavläget är per rad. |
| [Sample](#Sample) | Datan kodas och lagras per prov. |
### None {#None}
```
public static final int None
```


Datan kodas och lagras som komponent för komponent: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


Interleavläget är per rad. En hel rad av varje komponent kodas innan nästa rad behandlas.

### Sample {#Sample}
```
public static final int Sample
```


Datan kodas och lagras per prov. För färgbilder är detta formatet som RGBRGBRGB.

