---
title: "BitmapV4Header"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هيكل BitmapV4Header هو ملف رأس معلومات الـ bitmap."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)، [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

هيكل BitmapV4Header هو ملف رأس معلومات bitmap. وهو نسخة موسعة من هيكل BITMAPINFOHEADER.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRedMask()](#getRedMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | يحصل أو يعيّن قناع اللون الذي يحدد المكوّن ألفا لكل بكسل. |
| [getCSType()](#getCSType--) | يحصل أو يعيّن مساحة اللون لـ DIB. |
| [setCSType(int value)](#setCSType-int-) | يحصل أو يعيّن مساحة اللون لـ DIB. |
| [getEndpoints()](#getEndpoints--) | يحصل أو يعيّن فئة CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | يحصل أو يعيّن فئة CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | يحصل أو يعيّن قيمة غاما الحمراء. |
| [setGammaRed(int value)](#setGammaRed-int-) | يحصل أو يعيّن قيمة غاما الحمراء. |
| [getGammaGreen()](#getGammaGreen--) | يحصل أو يعيّن قيمة غاما الخضراء. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | يحصل أو يعيّن قيمة غاما الخضراء. |
| [getGammaBlue()](#getGammaBlue--) | يحصل أو يعيّن قيمة غاما الزرقاء. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | يحصل أو يعيّن قيمة غاما الزرقاء. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأحمر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأخضر لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


يحصل أو يعيّن قناع اللون الذي يحدد المكوّن الأزرق لكل بكسل، صالح فقط إذا تم تعيين bV4Compression إلى BI\_BITFIELDS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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
| القيمة | int |  |

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
| القيمة | int |  |

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


يحصل أو يعيّن قيمة غاما الحمراء.

**Returns:**
int - غاما الحمراء.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


يحصل أو يعيّن قيمة غاما الحمراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | غاما الحمراء. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


يحصل أو يعيّن قيمة غاما الخضراء.

**Returns:**
int - غاما الخضراء.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


يحصل أو يعيّن قيمة غاما الخضراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | غاما الخضراء. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


يحصل أو يعيّن قيمة غاما الزرقاء.

**Returns:**
int - غاما الزرقاء.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


يحصل أو يعيّن قيمة غاما الزرقاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الجاما الأزرق. |

