---
title: "EmfPlusPixelOffsetMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PixelOffsetMode sayımı, piksellerin nasıl ofsetlendiğini tanımlar ve bu, işleme hızı ile kalite arasındaki dengeyi belirtir."
type: docs
weight: 44
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

PixelOffsetMode sayımı, piksellerin nasıl ofsetleneceğini tanımlar; bu, render hızı ile kalite arasındaki dengeyi belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Pikseller tam sayı koordinatlarda merkezlenir, hızın kaliteye tercih edildiğini belirtir. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Pikseller tam sayı koordinatlarda merkezlenir, PixelOffsetModeNone gibi. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Pikseller yarı tam sayı koordinatlarda merkezlenir, PixelOffsetModeHalf gibi. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Pikseller orijinde merkezlenir, bu da pikselin x ve y eksenlerinde -0.5 ile 0.5 arasını kapsadığı ve merkezinin (0,0) olduğu anlamına gelir. |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Pikseller yarı tam sayı koordinatlarda merkezlenir, bu da pikselin x ve y eksenlerinde 0 ile 1 arasını kapsadığı ve merkezinin (0.5,0.5) olduğu anlamına gelir. |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Pikseller tam sayı koordinatlarda merkezlenir, hızın kaliteye tercih edildiğini belirtir.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Pikseller tam sayı koordinatlarda merkezlenir, PixelOffsetModeNone gibi. Kalitenin pahasına daha yüksek hız belirtilir.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Pikseller yarı tam sayı koordinatlarda merkezlenir, PixelOffsetModeHalf gibi. Hızın pahasına daha yüksek kalite belirtilir.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Pikseller orijinde merkezlenir, bu da pikselin x ve y eksenlerinde -0.5 ile 0.5 arasını kapsadığı ve merkezinin (0,0) olduğu anlamına gelir.

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Pikseller yarı tam sayı koordinatlarda merkezlenir, bu da pikselin x ve y eksenlerinde 0 ile 1 arasını kapsadığı ve merkezinin (0.5,0.5) olduğu anlamına gelir. İşleme sırasında pikselleri ofsetleyerek, işleme hızı pahasına işleme kalitesi artırılabilir.

