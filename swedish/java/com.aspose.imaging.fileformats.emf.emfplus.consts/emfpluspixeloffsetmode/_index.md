---
title: "EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "PixelOffsetMode‑enumerationen definierar hur pixlar förskjuts, vilket specificerar avvägningen mellan renderingshastighet och kvalitet."
type: docs
weight: 44
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

PixelOffsetMode‑enumerationen definierar hur pixlar förskjuts, vilket specificerar avvägningen mellan renderingshastighet och kvalitet.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Pixlar är centrerade på heltalskoordinater, vilket prioriterar hastighet framför kvalitet. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Pixlar är centrerade på heltalskoordinater, som med PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Pixlar är centrerade på halvtalskoordinater, som med PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Pixlar är centrerade på origo, vilket betyder att pixeln täcker området från -0,5 till 0,5 på både x‑ och y‑axeln och dess centrum är vid (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Pixlar är centrerade på halvtalskoordinater, vilket betyder att pixeln täcker området från 0 till 1 på både x‑ och y‑axeln och dess centrum är vid (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Pixlar är centrerade på heltalskoordinater, vilket prioriterar hastighet framför kvalitet.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Pixlar är centrerade på heltalskoordinater, som med PixelOffsetModeNone. Högre hastighet på bekostnad av kvalitet anges.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Pixlar är centrerade på halvtalskoordinater, som med PixelOffsetModeHalf. Högre kvalitet på bekostnad av hastighet anges.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Pixlar är centrerade på origo, vilket betyder att pixeln täcker området från -0,5 till 0,5 på både x‑ och y‑axeln och dess centrum är vid (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Pixlar är centrerade på halvtalskoordinater, vilket betyder att pixeln täcker området från 0 till 1 på både x‑ och y‑axeln och dess centrum är vid (0.5,0.5). Genom att förskjuta pixlar under rendering kan renderingskvaliteten förbättras på bekostnad av renderingshastigheten.

