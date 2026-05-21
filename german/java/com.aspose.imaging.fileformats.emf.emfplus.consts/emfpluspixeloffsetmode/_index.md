---
title: "EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PixelOffsetMode-Aufzählung definiert, wie Pixel versetzt werden, was den Kompromiss zwischen Rendering-Geschwindigkeit und Qualität festlegt."
type: docs
weight: 44
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

Die PixelOffsetMode-Aufzählung definiert, wie Pixel versetzt werden, was den Kompromiss zwischen Rendergeschwindigkeit und Qualität festlegt.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Pixel sind auf ganzzahligen Koordinaten zentriert, was Geschwindigkeit über Qualität priorisiert. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Pixel sind auf ganzzahligen Koordinaten zentriert, wie bei PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Pixel sind auf halbzahliger Koordinate zentriert, wie bei PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Pixel sind auf dem Ursprung zentriert, was bedeutet, dass das Pixel den Bereich von -0,5 bis 0,5 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0,0) liegt. |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Pixel sind auf halbzahliger Koordinate zentriert, was bedeutet, dass das Pixel den Bereich von 0 bis 1 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0.5,0.5) liegt. |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Pixel sind auf ganzzahligen Koordinaten zentriert, was Geschwindigkeit über Qualität priorisiert.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Pixel sind auf ganzzahligen Koordinaten zentriert, wie bei PixelOffsetModeNone. Höhere Geschwindigkeit zulasten der Qualität wird angegeben.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Pixel sind auf halbzahliger Koordinate zentriert, wie bei PixelOffsetModeHalf. Höhere Qualität zulasten der Geschwindigkeit wird angegeben.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Pixel sind auf dem Ursprung zentriert, was bedeutet, dass das Pixel den Bereich von -0,5 bis 0,5 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0,0) liegt.

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Pixel sind auf halbzahliger Koordinate zentriert, was bedeutet, dass das Pixel den Bereich von 0 bis 1 auf beiden Achsen x und y abdeckt und sein Zentrum bei (0.5,0.5) liegt. Durch das Versetzen von Pixeln während des Renderns kann die Renderqualität auf Kosten der Rendergeschwindigkeit verbessert werden.

