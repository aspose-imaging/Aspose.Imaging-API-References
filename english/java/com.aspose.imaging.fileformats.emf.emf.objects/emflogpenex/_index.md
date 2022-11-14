---
title: EmfLogPenEx
second_title: Aspose.Imaging for Java API Reference
description: The LogPenEx object specifies the style width and color of an extended logical pen.
type: docs
weight: 28
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

The LogPenEx object specifies the style, width, and color of an extended logical pen.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Gets or sets the pen style |
| [setPenStyle(int value)](#setPenStyle-int-) | Gets or sets the pen style |
| [getWidth()](#getWidth--) | Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen. |
| [getBrushStyle()](#getBrushStyle--) | Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Gets or sets the brush hatch pattern. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Gets or sets the brush hatch pattern. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Gets the number of elements in the array specified in the StyleEntry field. |
| [getStyleEntry()](#getStyleEntry--) | Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Gets or sets the brush dib pattern. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets the brush dib pattern. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Gets or sets the pen style

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Gets or sets the pen style

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen. If the pen type in the PenStyle field is PS\_GEOMETRIC, this value is the width in logical units; otherwise, the width is specified in device units. If the pen type in the PenStyle field is PS\_COSMETIC, this value MUST be 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the width of the line drawn by the pen. If the pen type in the PenStyle field is PS\_GEOMETRIC, this value is the width in logical units; otherwise, the width is specified in device units. If the pen type in the PenStyle field is PS\_COSMETIC, this value MUST be 0x00000001.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). If the pen type in the PenStyle field is PS\_GEOMETRIC, this value MUST be either BS\_SOLID or BS\_HATCHED. The value of this field can be BS\_NULL, but only if the line style specified in PenStyle is PS\_NULL. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Gets or sets a 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). If the pen type in the PenStyle field is PS\_GEOMETRIC, this value MUST be either BS\_SOLID or BS\_HATCHED. The value of this field can be BS\_NULL, but only if the line style specified in PenStyle is PS\_NULL. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). The interpretation of this field depends on the BrushStyle value, as shown in the table later in this section.

Value: The 32-bit ARGB color

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8). The interpretation of this field depends on the BrushStyle value, as shown in the table later in this section.

Value: The 32-bit ARGB color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Gets or sets the brush hatch pattern. The definition of this field depends on the BrushStyle value, as shown in the table later in this section.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Gets or sets the brush hatch pattern. The definition of this field depends on the BrushStyle value, as shown in the table later in this section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Gets the number of elements in the array specified in the StyleEntry field. This value SHOULD be zero if PenStyle does not specify PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. The array contains a number of entries specified by NumStyleEntries, but it is used as if it repeated indefinitely The first entry in the array specifies the length of the first dash. The second entry specifies the length of the first gap. Thereafter, lengths of dashes and gaps alternate. If the pen type in the PenStyle field is PS\_GEOMETRIC, the lengths are specified in logical units; otherwise, the lengths are specified in device units.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Gets or sets an optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. The array contains a number of entries specified by NumStyleEntries, but it is used as if it repeated indefinitely The first entry in the array specifies the length of the first dash. The second entry specifies the length of the first gap. Thereafter, lengths of dashes and gaps alternate. If the pen type in the PenStyle field is PS\_GEOMETRIC, the lengths are specified in logical units; otherwise, the lengths are specified in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Gets or sets the brush dib pattern.

Value: The brush dib pattern.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Gets or sets the brush dib pattern.

Value: The brush dib pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

