---
title: "EmfPlusPixelOffsetMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione PixelOffsetMode definisce come vengono offsettati i pixel, specificando il compromesso tra velocità di rendering e qualità."
type: docs
weight: 44
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

L'enumerazione PixelOffsetMode definisce come vengono spostati i pixel, specificando il compromesso tra velocità di rendering e qualità.
## Campi

| Campo | Descrizione |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | I pixel sono centrati su coordinate intere, specificando velocità rispetto alla qualità. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | I pixel sono centrati su coordinate intere, come con PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | I pixel sono centrati su coordinate semi-intere, come con PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | I pixel sono centrati sull'origine, il che significa che il pixel copre l'area da -0.5 a 0.5 su entrambi gli assi x e y e il suo centro è a (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | I pixel sono centrati su coordinate semi-intere, il che significa che il pixel copre l'area da 0 a 1 su entrambi gli assi x e y e il suo centro è a (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


I pixel sono centrati su coordinate intere, specificando velocità rispetto alla qualità.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


I pixel sono centrati su coordinate intere, come con PixelOffsetModeNone. Si specifica una maggiore velocità a scapito della qualità.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


I pixel sono centrati su coordinate semi-intere, come con PixelOffsetModeHalf. Si specifica una maggiore qualità a scapito della velocità.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


I pixel sono centrati sull'origine, il che significa che il pixel copre l'area da -0.5 a 0.5 su entrambi gli assi x e y e il suo centro è a (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


I pixel sono centrati su coordinate semi-intere, il che significa che il pixel copre l'area da 0 a 1 su entrambi gli assi x e y e il suo centro è a (0.5,0.5). Offsettando i pixel durante il rendering, la qualità del rendering può essere migliorata a costo della velocità di rendering.

