---
title: EmfPlusPixelOffsetMode
second_title: Aspose.Imaging for Java API Reference
description: The PixelOffsetMode enumeration defines how pixels are offset which specifies the trade-off between rendering speed and quality.
type: docs
weight: 44
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelOffsetMode extends System.Enum
```

The PixelOffsetMode enumeration defines how pixels are offset, which specifies the trade-off between rendering speed and quality.
## Fields

| Field | Description |
| --- | --- |
| [PixelOffsetModeDefault](#PixelOffsetModeDefault) | Pixels are centered on integer coordinates, specifying speed over quality. |
| [PixelOffsetModeHighSpeed](#PixelOffsetModeHighSpeed) | Pixels are centered on integer coordinates, as with PixelOffsetModeNone. |
| [PixelOffsetModeHighQuality](#PixelOffsetModeHighQuality) | Pixels are centered on half-integer coordinates, as with PixelOffsetModeHalf. |
| [PixelOffsetModeNone](#PixelOffsetModeNone) | Pixels are centered on the origin, which means that the pixel covers the area from -0.5 to 0.5 on both the x and y axes and its center is at (0,0). |
| [PixelOffsetModeHalf](#PixelOffsetModeHalf) | Pixels are centered on half-integer coordinates, which means that the pixel covers the area from 0 to 1 on both the x and y axes and its center is at (0.5,0.5). |
### PixelOffsetModeDefault {#PixelOffsetModeDefault}
```
public static final byte PixelOffsetModeDefault
```


Pixels are centered on integer coordinates, specifying speed over quality.

### PixelOffsetModeHighSpeed {#PixelOffsetModeHighSpeed}
```
public static final byte PixelOffsetModeHighSpeed
```


Pixels are centered on integer coordinates, as with PixelOffsetModeNone. Higher speed at the expense of quality is specified.

### PixelOffsetModeHighQuality {#PixelOffsetModeHighQuality}
```
public static final byte PixelOffsetModeHighQuality
```


Pixels are centered on half-integer coordinates, as with PixelOffsetModeHalf. Higher quality at the expense of speed is specified.

### PixelOffsetModeNone {#PixelOffsetModeNone}
```
public static final byte PixelOffsetModeNone
```


Pixels are centered on the origin, which means that the pixel covers the area from -0.5 to 0.5 on both the x and y axes and its center is at (0,0).

### PixelOffsetModeHalf {#PixelOffsetModeHalf}
```
public static final byte PixelOffsetModeHalf
```


Pixels are centered on half-integer coordinates, which means that the pixel covers the area from 0 to 1 on both the x and y axes and its center is at (0.5,0.5). By offsetting pixels during rendering, the render quality can be improved at the cost of render speed.

