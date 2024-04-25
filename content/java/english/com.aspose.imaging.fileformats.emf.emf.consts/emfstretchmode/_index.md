---
title: EmfStretchMode
second_title: Aspose.Imaging for Java API Reference
description: The StretchMode enumeration is used to specify how color data is added to or removed from bitmaps that are stretched or compressed.
type: docs
weight: 43
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

The StretchMode enumeration is used to specify how color data is added to or removed from bitmaps that are stretched or compressed.
## Fields

| Field | Description |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Performs a Boolean AND operation using the color values for the eliminated and existing pixels. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Performs a Boolean OR operation using the color values for the eliminated and existing pixels. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Deletes the pixels. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Performs a Boolean AND operation using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves black pixels at the expense of white pixels

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Performs a Boolean OR operation using the color values for the eliminated and existing pixels. If the bitmap is a monochrome bitmap, this mode preserves white pixels at the expense of black pixels.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Deletes the pixels. This mode deletes all eliminated lines of pixels without trying to preserve their information.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Maps pixels from the source rectangle into blocks of pixels in the destination rectangle. The average color over the destination block of pixels approximates the color of the source pixels.

