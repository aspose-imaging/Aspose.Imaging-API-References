---
title: WmfFontQuality
second_title: Aspose.Imaging for Java API Reference
description: The FontQuality Enumeration specifies how closely the attributes of the logical font should match those of the physical font when rendering text.
type: docs
weight: 19
url: /com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

The FontQuality Enumeration specifies how closely the attributes of the logical font should match those of the physical font when rendering text.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Specifies that the character quality of the font does not matter, so DRAFT can be used. |
| [Draft](#Draft) | Specifies that the character quality of the font is less important than the matching of logical attribuetes. |
| [Proof](#Proof) | Specifies that the character quality of the font is more important than the matching of logical attributes. |
| [Nonantialiased](#Nonantialiased) | Specifies that anti-aliasing SHOULD NOT be used when rendering text |
| [Antialiased](#Antialiased) | Specifies that anti-aliasing SHOULD be used when rendering text, if the font supports it. |
| [Cleartype](#Cleartype) | Specifies that ClearType anti-aliasing SHOULD be used when rendering text, if the font supports it. |
### Default {#Default}
```
public static final byte Default
```


Specifies that the character quality of the font does not matter, so DRAFT can be used.

### Draft {#Draft}
```
public static final byte Draft
```


Specifies that the character quality of the font is less important than the matching of logical attribuetes. For rasterized fonts, scaling SHOULD be enabled, which means that more font sizes are available.

### Proof {#Proof}
```
public static final byte Proof
```


Specifies that the character quality of the font is more important than the matching of logical attributes. For rasterized fonts, scaling SHOULD be disabled, and the font closest in size SHOULD be chosen.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Specifies that anti-aliasing SHOULD NOT be used when rendering text

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Specifies that anti-aliasing SHOULD be used when rendering text, if the font supports it.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Specifies that ClearType anti-aliasing SHOULD be used when rendering text, if the font supports it.

