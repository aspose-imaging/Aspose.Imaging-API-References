---
title: WmfClipPrecisionFlags
second_title: Aspose.Imaging for Java API Reference
description: ClipPrecision Flags specify clipping precision which defines how to clip characters that are partially outside a clipping region.
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

ClipPrecision Flags specify clipping precision, which defines how to clip characters that are partially outside a clipping region. These flags can be combined to specify multiple options.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Specifies that default clipping MUST be used. |
| [Character](#Character) | This value SHOULD NOT be used. |
| [Stroke](#Stroke) | This value MAY be returned when enumerating rasterized, TrueType and vector fonts |
| [LhAngles](#LhAngles) | This value is used to control font rotation, as follows: - If set, the rotation for all fonts SHOULD be determined by the orientation of the coordinate system; that is, whether the orientation is left-handed or right-handed |
| [TtAlways](#TtAlways) | This value SHOULD NOT [34] be used |
| [DfaDisable](#DfaDisable) | This value specifies that font association SHOULD [35] be turned off |
| [Embedded](#Embedded) | This value specifies that font embedding MUST be used to render document content; embedded fonts are read-only. |
### Default {#Default}
```
public static final byte Default
```


Specifies that default clipping MUST be used.

### Character {#Character}
```
public static final byte Character
```


This value SHOULD NOT be used.

### Stroke {#Stroke}
```
public static final byte Stroke
```


This value MAY be returned when enumerating rasterized, TrueType and vector fonts. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000, and Windows XP: This value is always returned when enumerating fonts.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


This value is used to control font rotation, as follows: - If set, the rotation for all fonts SHOULD be determined by the orientation of the coordinate system; that is, whether the orientation is left-handed or right-handed. - If clear, device fonts SHOULD rotate counterclockwise, but the rotation of other fonts SHOULD be determined by the orientation of the coordinate system.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


This value SHOULD NOT [34] be used. [34] This value is ignored in the following Windows versions: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


This value specifies that font association SHOULD [35] be turned off. [35] This value is not supported.in Windows 95, Windows 98, and Windows Millennium Edition. Font association is turned off in Windows 2000, Windows XP, and Windows Server 2003. This value is ignored in these Windows versions: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


This value specifies that font embedding MUST be used to render document content; embedded fonts are read-only.

