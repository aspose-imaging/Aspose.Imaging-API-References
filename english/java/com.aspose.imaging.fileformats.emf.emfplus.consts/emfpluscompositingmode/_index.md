---
title: EmfPlusCompositingMode
second_title: Aspose.Imaging for Java API Reference
description: The CompositingMode enumeration defines modes for combining source colors with background colors.
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingMode extends System.Enum
```

The CompositingMode enumeration defines modes for combining source colors with background colors. The compositing mode represents the enable state of alpha blending.
## Fields

| Field | Description |
| --- | --- |
| [CompositingModeSourceOver](#CompositingModeSourceOver) | Enables alpha blending, which specifies that when a color is rendered, it is blended with the background color. |
| [CompositingModeSourceCopy](#CompositingModeSourceCopy) | Disables alpha blending, which means that when a source color is rendered, it overwrites the background color. |
### CompositingModeSourceOver {#CompositingModeSourceOver}
```
public static final byte CompositingModeSourceOver
```


Enables alpha blending, which specifies that when a color is rendered, it is blended with the background color. The extent of blending is determined by the value of the alpha component of the color being rendered.

### CompositingModeSourceCopy {#CompositingModeSourceCopy}
```
public static final byte CompositingModeSourceCopy
```


Disables alpha blending, which means that when a source color is rendered, it overwrites the background color.

