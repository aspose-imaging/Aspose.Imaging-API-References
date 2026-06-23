---
title: "BitmapV4Header"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "بنية BitmapV4Header هي ملف رأس معلومات البت ماب."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

هيكل BitmapV4Header هو ملف رأس معلومات bitmap. وهو نسخة موسعة من هيكل BITMAPINFOHEADER.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRedMask()](#getRedMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل. |
| [getCSType()](#getCSType--) | يحصل أو يعيّن مساحة اللون لـ DIB. |
| [setCSType(int value)](#setCSType-int-) | يحصل أو يعيّن مساحة اللون لـ DIB. |
| [getEndpoints()](#getEndpoints--) | يحصل أو يعيّن فئة CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | يحصل أو يعيّن فئة CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | يحصل أو يعيّن قيمة غاما للون الأحمر. |
| [setGammaRed(int value)](#setGammaRed-int-) | يحصل أو يعيّن قيمة غاما للون الأحمر. |
| [getGammaGreen()](#getGammaGreen--) | يحصل أو يضبط غاما الأخضر. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | يحصل أو يضبط غاما الأخضر. |
| [getGammaBlue()](#getGammaBlue--) | يحصل أو يضبط غاما الأزرق. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | يحصل أو يضبط غاما الأزرق. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم ضبط bV4Compression على BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


يحصل أو يعيّن مساحة اللون لـ DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


يحصل أو يعيّن مساحة اللون لـ DIB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


يحصل أو يعيّن فئة CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


يحصل أو يعيّن فئة CoordinatesTriple.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | نقاط النهاية. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


يحصل أو يعيّن قيمة غاما للون الأحمر.

**Returns:**
int - غاما الأحمر.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


يحصل أو يعيّن قيمة غاما للون الأحمر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | غاما الأحمر. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


يحصل أو يضبط غاما الأخضر.

**Returns:**
int - غاما الأخضر.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


يحصل أو يضبط غاما الأخضر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | غاما الأخضر. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


يحصل أو يضبط غاما الأزرق.

**Returns:**
int - غاما الأزرق.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


يحصل أو يضبط غاما الأزرق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | غاما الأزرق. |

