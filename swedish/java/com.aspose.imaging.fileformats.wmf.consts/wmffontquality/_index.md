---
title: "WmfFontQuality"
second_title: "Aspose.Imaging för Java API-referens"
description: "FontQuality‑enumerationen specificerar hur nära attributen för det logiska teckensnittet bör matcha de för det fysiska teckensnittet vid rendering av text."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

FontQuality‑enumerationen specificerar hur nära attributen för det logiska teckensnittet bör matcha de för det fysiska teckensnittet vid rendering av text.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Default](#Default) | Anger att teckenkvaliteten för teckensnittet inte spelar någon roll, så DRAFT kan användas. |
| [Draft](#Draft) | Anger att teckenkvaliteten för teckensnittet är mindre viktig än matchningen av logiska attribut. |
| [Proof](#Proof) | Anger att teckenkvaliteten för teckensnittet är viktigare än matchningen av logiska attribut. |
| [Nonantialiased](#Nonantialiased) | Anger att anti-aliasing SHOULD NOT bör användas vid rendering av text. |
| [Antialiased](#Antialiased) | Anger att anti-aliasing SHOULD bör användas vid rendering av text, om teckensnittet stödjer det. |
| [Cleartype](#Cleartype) | Anger att ClearType anti-aliasing SHOULD bör användas vid rendering av text, om teckensnittet stödjer det. |
### Default {#Default}
```
public static final byte Default
```


Anger att teckenkvaliteten för teckensnittet inte spelar någon roll, så DRAFT kan användas.

### Draft {#Draft}
```
public static final byte Draft
```


Anger att teckenkvaliteten för teckensnittet är mindre viktig än matchningen av logiska attribut. För rasteriserade teckensnitt bör skalning SHOULD vara aktiverad, vilket betyder att fler teckensnittsstorlekar är tillgängliga.

### Proof {#Proof}
```
public static final byte Proof
```


Anger att teckenkvaliteten för teckensnittet är viktigare än matchningen av logiska attribut. För rasteriserade teckensnitt bör skalning SHOULD vara inaktiverad, och det teckensnitt som är närmast i storlek SHOULD väljs.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Anger att anti-aliasing SHOULD NOT bör användas vid rendering av text.

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Anger att anti-aliasing SHOULD bör användas vid rendering av text, om teckensnittet stödjer det.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Anger att ClearType anti-aliasing SHOULD bör användas vid rendering av text, om teckensnittet stödjer det.

