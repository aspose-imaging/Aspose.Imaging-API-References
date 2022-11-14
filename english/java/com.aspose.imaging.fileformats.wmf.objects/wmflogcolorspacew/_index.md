---
title: WmfLogColorSpaceW
second_title: Aspose.Imaging for Java API Reference
description: The LogColorSpaceW object specifies a logical color space which can be     defined by a color profile file with a name consisting of Unicode 16-bit     characters.
type: docs
weight: 45
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

The LogColorSpaceW object specifies a logical color space, which can be defined by a color profile file with a name consisting of Unicode 16-bit characters.

See the `WmfLogColorSpace` object (section 2.2.2.11) for additional details concerning the interpretation of field values of this object.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets or sets a 32-bit unsigned integer that specifies the `signature` of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC". |
| [setSignature(int value)](#setSignature-int-) | Gets or sets a 32-bit unsigned integer that specifies the `signature` of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC". |
| [getVersion()](#getVersion--) | Gets or sets a 32-bit unsigned integer that defines a `version` number; it MUST be0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets a 32-bit unsigned integer that defines a `version` number; it MUST be0x00000400. |
| [getSize()](#getSize--) | Gets or sets a 32-bit unsigned integer that defines the `size` of this object, in bytes. |
| [setSize(int value)](#setSize-int-) | Gets or sets a 32-bit unsigned integer that defines the `size` of this object, in bytes. |
| [getColorSpaceType()](#getColorSpaceType--) | Gets or sets a 32-bit signed integer that specifies the color space type. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Gets or sets a 32-bit signed integer that specifies the color space type. |
| [getIntent()](#getIntent--) | Gets or sets a 32-bit signed integer that defines the gamut mapping intent. |
| [setIntent(int value)](#setIntent-int-) | Gets or sets a 32-bit signed integer that defines the gamut mapping intent. |
| [getEndpoints()](#getEndpoints--) | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB `endpoints` for the logical color space associated with the bitmap. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB `endpoints` for the logical color space associated with the bitmap. |
| [getGammaRed()](#getGammaRed--) | Gets or sets a 32-bit fixed point value that defines the toned response curve for red. |
| [setGammaRed(int value)](#setGammaRed-int-) | Gets or sets a 32-bit fixed point value that defines the toned response curve for red. |
| [getGammaGreen()](#getGammaGreen--) | Gets or sets a 32-bit fixed point value that defines the toned response curve for green. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Gets or sets a 32-bit fixed point value that defines the toned response curve for green. |
| [getGammaBlue()](#getGammaBlue--) | Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. |
| [getFilename()](#getFilename--) | Gets or sets an optional, null-terminated Unicode UTF16-LE character string, which specifies the name of a file that contains a color profile. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Gets or sets an optional, null-terminated Unicode UTF16-LE character string, which specifies the name of a file that contains a color profile. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets or sets a 32-bit unsigned integer that specifies the `signature` of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the `signature` of color space objects; it MUST be set to the value 0x50534F43, which is the ASCII encoding of the string "PSOC".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets a 32-bit unsigned integer that defines a `version` number; it MUST be0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets a 32-bit unsigned integer that defines a `version` number; it MUST be0x00000400.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Gets or sets a 32-bit unsigned integer that defines the `size` of this object, in bytes.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Gets or sets a 32-bit unsigned integer that defines the `size` of this object, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Gets or sets a 32-bit signed integer that specifies the color space type. It MUST be defined in the LogicalColorSpace enumeration (section 2.1.1.14). If this value is LCS\_sRGB or LCS\_WINDOWS\_COLOR\_SPACE, the sRGB color space MUST be used.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Gets or sets a 32-bit signed integer that specifies the color space type. It MUST be defined in the LogicalColorSpace enumeration (section 2.1.1.14). If this value is LCS\_sRGB or LCS\_WINDOWS\_COLOR\_SPACE, the sRGB color space MUST be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets or sets a 32-bit signed integer that defines the gamut mapping intent. It MUST be defined in the GamutMappingIntent enumeration (section 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Gets or sets a 32-bit signed integer that defines the gamut mapping intent. It MUST be defined in the GamutMappingIntent enumeration (section 2.1.1.11).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB `endpoints` for the logical color space associated with the bitmap. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Gets or sets a CIEXYZTriple object (section 2.2.2.7) that defines the CIE chromaticity x, y, and z coordinates of the three colors that correspond to the RGB `endpoints` for the logical color space associated with the bitmap. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for red. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for red. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for green. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for green. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Gets or sets a 32-bit fixed point value that defines the toned response curve for blue. If the `ColorSpaceType` field does not specify LCS\_CALIBRATED\_RGB, this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Gets or sets an optional, null-terminated Unicode UTF16-LE character string, which specifies the name of a file that contains a color profile. If a file name is specified, and the `ColorSpaceType` field is set to LCS\_CALIBRATED\_RGB, the other fields of this structure SHOULD be ignored.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Gets or sets an optional, null-terminated Unicode UTF16-LE character string, which specifies the name of a file that contains a color profile. If a file name is specified, and the `ColorSpaceType` field is set to LCS\_CALIBRATED\_RGB, the other fields of this structure SHOULD be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

