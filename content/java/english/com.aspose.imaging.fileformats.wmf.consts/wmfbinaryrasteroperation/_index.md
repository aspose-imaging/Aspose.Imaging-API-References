---
title: WmfBinaryRasterOperation
second_title: Aspose.Imaging for Java API Reference
description: The BinaryRasterOperation Enumeration section lists the binary raster-operation codes.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

The BinaryRasterOperation Enumeration section lists the binary raster-operation codes. Raster operation codes define how metafile processing combines the bits from the selected pen with the bits in the destination bitmap.

--------------------

Each raster-operation code represents a Boolean operation in which the values of the pixels in the selected pen and the destination bitmap are combined. Following are the two operands used in these operations. Operand Meaning P Selected pen D Destination bitmap a Bitwise AND n Bitwise NOT (inverse) o Bitwise OR x Bitwise exclusive OR (XOR)
## Fields

| Field | Description |
| --- | --- |
| [Black](#Black) | 0, Pixel is always 0. |
| [Notmergepen](#Notmergepen) | DPon, Pixel is the inverse of the MERGEPEN color |
| [Masknotpen](#Masknotpen) | DPna, Pixel is a combination of the screen color and the inverse of the pen color. |
| [Notcopypen](#Notcopypen) | Pn, Pixel is the inverse of the pen color. |
| [Maskpennot](#Maskpennot) | PDna, Pixel is a combination of the colors common to both the pen and the inverse of the screen. |
| [Not](#Not) | Dn, Pixel is the inverse of the screen color. |
| [Xorpen](#Xorpen) | DPx, Pixel is a combination of the colors in the pen or in the screen, but not in both. |
| [Notmaskpen](#Notmaskpen) | DPan, Pixel is the inverse of the MASKPEN color. |
| [Maskpen](#Maskpen) | DPa, Pixel is a combination of the colors common to both the pen and the screen. |
| [Notxorpen](#Notxorpen) | DPxn, Pixel is the inverse of the XORPEN color. |
| [Nop](#Nop) | D, Pixel remains unchanged. |
| [Mergenotpen](#Mergenotpen) | DPno, Pixel is a combination of the colors common to both the screen and the inverse of the pen. |
| [Copypen](#Copypen) | P, Pixel is the pen color. |
| [Mergepennot](#Mergepennot) | PDno, Pixel is a combination of the pen color and the inverse of the screen color. |
| [Mergepen](#Mergepen) | DPo, Pixel is a combination of the pen color and the screen color. |
| [White](#White) | 1, Pixel is always 1 |
### Black {#Black}
```
public static final int Black
```


0, Pixel is always 0.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, Pixel is the inverse of the MERGEPEN color

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, Pixel is a combination of the screen color and the inverse of the pen color.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, Pixel is the inverse of the pen color.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, Pixel is a combination of the colors common to both the pen and the inverse of the screen.

### Not {#Not}
```
public static final int Not
```


Dn, Pixel is the inverse of the screen color.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, Pixel is a combination of the colors in the pen or in the screen, but not in both.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, Pixel is the inverse of the MASKPEN color.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, Pixel is a combination of the colors common to both the pen and the screen.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, Pixel is the inverse of the XORPEN color.

### Nop {#Nop}
```
public static final int Nop
```


D, Pixel remains unchanged.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, Pixel is a combination of the colors common to both the screen and the inverse of the pen.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Pixel is the pen color.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Pixel is a combination of the pen color and the inverse of the screen color.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Pixel is a combination of the pen color and the screen color.

### White {#White}
```
public static final int White
```


1, Pixel is always 1

