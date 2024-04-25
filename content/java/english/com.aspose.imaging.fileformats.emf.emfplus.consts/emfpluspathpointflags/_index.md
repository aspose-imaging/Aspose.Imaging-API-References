---
title: EmfPlusPathPointFlags
second_title: Aspose.Imaging for Java API Reference
description: A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object.
type: docs
weight: 38
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object. C (1 bit): If set, the PathPoints array specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, the PathPoints array specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag MAY be clear and MUST be ignored. R (1 bit): If set, the point types in the PathPointTypes array are specified by EmfPlusPathPointTypeRle objects (section 2.2.2.32), which use run-length encoding (RLE) compression, and/or EmfPlusPathPointType objects (section 2.2.2.31). See [MS-WMF] section 3.1.6 for more information on RLE compression. If clear, the point types in the PathPointTypes array are specified by EmfPlusPathPointType objects. P (1 bit): If set, each element in the PathPoints array specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PathPoints, a previous location at coordinates (0,0) is assumed. If clear, each element in the PathPoints array specifies an absolute location.
## Fields

| Field | Description |
| --- | --- |
| [C](#C) | The c flag |
| [R](#R) | The r flag |
| [P](#P) | The p flag |
### C {#C}
```
public static final short C
```


The c flag

### R {#R}
```
public static final short R
```


The r flag

### P {#P}
```
public static final short P
```


The p flag

