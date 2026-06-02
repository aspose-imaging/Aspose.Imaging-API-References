---
title: "JpegLsInterleaveMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert den Interleavemodus für mehrkomponentige Farbpixeldaten."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Definiert den Interleav‑Modus für mehrkomponentige (Farb‑)Pixel‑Daten.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Die Daten werden komponentenweise kodiert und gespeichert: RRRGGGBBB. |
| [Line](#Line) | Der Interleavemodus ist zeilenweise. |
| [Sample](#Sample) | Die Daten werden pro Sample kodiert und gespeichert. |
### None {#None}
```
public static final int None
```


Die Daten werden komponentenweise kodiert und gespeichert: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


Der Interleavemodus ist zeilenweise. Eine komplette Zeile jeder Komponente wird kodiert, bevor zur nächsten Zeile gewechselt wird.

### Sample {#Sample}
```
public static final int Sample
```


Die Daten werden pro Sample kodiert und gespeichert. Bei Farbbildern entspricht dies einem Format wie RGBRGBRGB.

