---
title: AnimationDisposalMethods
second_title: Aspose.Imaging for Java API Reference
description: Indicates the way in which the graphic is to be treated after being displayed.
type: docs
weight: 11
url: /java/com.aspose.imaging/animationdisposalmethods/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnimationDisposalMethods extends System.Enum
```

Indicates the way in which the graphic is to be treated after being displayed.
## Fields

| Field | Description |
| --- | --- |
| [PRESERVE](#PRESERVE) | Do not dispose. |
| [BACKGROUND](#BACKGROUND) | Restore to background color. |
| [PREVIOUS](#PREVIOUS) | Restore to previous. |
### PRESERVE {#PRESERVE}
```
public static final int PRESERVE
```


Do not dispose. The graphic is to be left in place.

### BACKGROUND {#BACKGROUND}
```
public static final int BACKGROUND
```


Restore to background color. The area used by the graphic must be restored to the background color.

### PREVIOUS {#PREVIOUS}
```
public static final int PREVIOUS
```


Restore to previous. The decoder is required to restore the area overwritten by the graphic with what was there prior to rendering the graphic.

