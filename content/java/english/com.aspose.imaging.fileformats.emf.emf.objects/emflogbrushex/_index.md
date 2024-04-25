---
title: EmfLogBrushEx
second_title: Aspose.Imaging for Java API Reference
description: The LogBrushEx object defines the style color and pattern of a device-independent brush.
type: docs
weight: 21
url: /com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

The LogBrushEx object defines the style, color, and pattern of a device-independent brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Gets or sets a 32-bit unsigned integer that specifies the brush style. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Gets or sets a 32-bit unsigned integer that specifies the brush style. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. |
| [getBrushHatch()](#getBrushHatch--) | Gets or sets a 32-bit unsigned field that contains the brush hatch data. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Gets or sets a 32-bit unsigned field that contains the brush hatch data. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Gets or sets a 32-bit unsigned integer that specifies the brush style. The value MUST be an enumeration from WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). The style values that are supported in this structure are listed later in this section. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the brush style. The value MUST be an enumeration from WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). The style values that are supported in this structure are listed later in this section. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. The interpretation of this field depends on the value of BrushStyle, as explained in the following table.

Value: The 32-bit ARGB color

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. The interpretation of this field depends on the value of BrushStyle, as explained in the following table.

Value: The 32-bit ARGB color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Gets or sets a 32-bit unsigned field that contains the brush hatch data. Its interpretation depends on the value of BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Gets or sets a 32-bit unsigned field that contains the brush hatch data. Its interpretation depends on the value of BrushStyle,

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

