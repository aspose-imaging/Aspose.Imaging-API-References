---
title: StretchMode
second_title: Aspose.Imaging for Java API Reference
description: The  Enumeration specifies the bitma stretching mode which defines how the system combines rows or columns of a bitmap with existing pixels.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

The [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) Enumeration specifies the bitmap stretching mode, which defines how the system combines rows or columns of a bitmap with existing pixels.
## Fields

| Field | Description |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Performs a Boolean AND operation by using the color values for the eliminated and existing pixels. |
| [WhiteOnBlack](#WhiteOnBlack) | Performs a Boolean OR operation by using the color values for the eliminated and existing pixels. |
| [ColorOnColor](#ColorOnColor) | Deletes the pixels. |
| [HalfTone](#HalfTone) | Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Performs a Boolean AND operation by using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves black pixels at the expense of white pixels

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Performs a Boolean OR operation by using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves white pixels at the expense of black pixels

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Deletes the pixels. This mode deletes all eliminated lines of pixels without trying to preserve their information.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. The average color over the destination block of pixels approximates the color of the source pixels.

