---
title: EmfModifyWorldTransformMode
second_title: Aspose.Imaging for Java API Reference
description: The ModifyWorldTransformMode enumeration defines modes for using specified transform data to modify the world-space to page-space transform that is currently defined in the playback device context.
type: docs
weight: 33
url: /java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

The ModifyWorldTransformMode enumeration defines modes for using specified transform data to modify the world-space to page-space transform that is currently defined in the playback device context.
## Fields

| Field | Description |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Reset the current transform using the identity matrix. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Multiply the current transform. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Multiply the current transform. |
| [MWT_SET](#MWT-SET) | Perform the function of an EMR\_SETWORLDTRANSFORM record (section 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Reset the current transform using the identity matrix. In this mode, the specified transform data is ignored

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Multiply the current transform. In this mode, the specified transform data is the left multiplicand, and the transform that is currently defined in the playback device context is the right multiplicand

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Multiply the current transform. In this mode, the specified transform data is the right multiplicand, and the transform that is currently defined in the playback device context is the left multiplicand

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Perform the function of an EMR\_SETWORLDTRANSFORM record (section 2.3.12.2).

