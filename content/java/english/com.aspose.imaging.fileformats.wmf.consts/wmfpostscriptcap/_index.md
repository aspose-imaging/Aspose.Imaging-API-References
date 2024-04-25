---
title: WmfPostScriptCap
second_title: Aspose.Imaging for Java API Reference
description: The PostScriptCap Enumeration defines line-ending types for use with a PostScript printer driver.
type: docs
weight: 31
url: /com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptcap/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptCap extends System.Enum
```

The PostScriptCap Enumeration defines line-ending types for use with a PostScript printer driver.
## Fields

| Field | Description |
| --- | --- |
| [PostScriptNotSet](#PostScriptNotSet) | Specifies that the line-ending style has not been set, and that a default style MAY [24] be used. |
| [PostScriptFlatCap](#PostScriptFlatCap) | Specifies that the line ends at the last point. |
| [PostScriptRoundCap](#PostScriptRoundCap) | Specifies a circular cap. |
| [PostScriptSquareCap](#PostScriptSquareCap) | Specifies a square cap. |
### PostScriptNotSet {#PostScriptNotSet}
```
public static final int PostScriptNotSet
```


Specifies that the line-ending style has not been set, and that a default style MAY [24] be used.

### PostScriptFlatCap {#PostScriptFlatCap}
```
public static final int PostScriptFlatCap
```


Specifies that the line ends at the last point. The end is squared off.

### PostScriptRoundCap {#PostScriptRoundCap}
```
public static final int PostScriptRoundCap
```


Specifies a circular cap. The center of the circle is the last point in the line. The diameter of the circle is the same as the line width; that is, the thickness of the line.

### PostScriptSquareCap {#PostScriptSquareCap}
```
public static final int PostScriptSquareCap
```


Specifies a square cap. The center of the square is the last point in the line. The height and width of the square are the same as the line width; that is, the thickness of the line.

