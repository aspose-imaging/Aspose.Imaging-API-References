---
title: DisposalMethod
second_title: Aspose.Imaging for Java API Reference
description: Indicates the way in which the graphic is to be treated after being displayed.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.gif/disposalmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DisposalMethod extends System.Enum
```

Indicates the way in which the graphic is to be treated after being displayed.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No disposal specified. |
| [Preserve](#Preserve) | Do not dispose. |
| [Restore](#Restore) | Restore to background color. |
| [Previous](#Previous) | Restore to previous. |
| [Undefined](#Undefined) | Undefined value. |
### None {#None}
```
public static final int None
```


No disposal specified.

### Preserve {#Preserve}
```
public static final int Preserve
```


Do not dispose. The graphic is to be left in place.

### Restore {#Restore}
```
public static final int Restore
```


Restore to background color. The area used by the graphic must be restored to the background color.

### Previous {#Previous}
```
public static final int Previous
```


Restore to previous. The decoder is required to restore the area overwritten by the graphic with what was there prior to rendering the graphic.

### Undefined {#Undefined}
```
public static final int Undefined
```


Undefined value.

