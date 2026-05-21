---
title: "ColorMatrix"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RGBA uzayı için koordinatları içeren 5 x 5 matris tanımlar."
type: docs
weight: 26
url: /tr/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

RGBA uzayı için koordinatları içeren 5 x 5 bir matris tanımlar. [ImageAttributes](../../com.aspose.imaging/imageattributes) sınıfının çeşitli yöntemleri, bir renk matrisi kullanarak görüntü renklerini ayarlar. Bu sınıf kalıtılamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | `Aspose.Imaging.ColorMatrix` sınıfının yeni bir örneğini başlatır. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Belirtilen `newColorMatrix` matrisindeki öğeleri kullanarak `Aspose.Imaging.ColorMatrix` sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | Matris boyutundaki öğe sayısı. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | Matris boyutlarının sayısı. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | Matris içindeki toplam öğe sayısı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve 0 sütunundaki öğeyi alır. |
| [setMatrix00(float value)](#setMatrix00-float-) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve 0 sütunundaki öğeyi ayarlar. |
| [getMatrix01()](#getMatrix01--) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve birinci sütunundaki öğeyi alır. |
| [setMatrix01(float value)](#setMatrix01-float-) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve birinci sütunundaki öğeyi ayarlar. |
| [getMatrix02()](#getMatrix02--) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve ikinci sütunundaki öğeyi alır. |
| [setMatrix02(float value)](#setMatrix02-float-) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve ikinci sütunundaki öğeyi ayarlar. |
| [getMatrix03()](#getMatrix03--) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve üçüncü sütunundaki öğeyi alır. |
| [setMatrix03(float value)](#setMatrix03-float-) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve üçüncü sütunundaki öğeyi ayarlar. |
| [getMatrix04()](#getMatrix04--) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve dördüncü sütunundaki öğeyi alır. |
| [setMatrix04(float value)](#setMatrix04-float-) | Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve dördüncü sütunundaki öğeyi ayarlar. |
| [getMatrix10()](#getMatrix10--) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0 (sıfır) sütunundaki öğeyi alır. |
| [setMatrix10(float value)](#setMatrix10-float-) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0 (sıfır) sütunundaki öğeyi ayarlar. |
| [getMatrix11()](#getMatrix11--) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve birinci sütunundaki öğeyi alır. |
| [setMatrix11(float value)](#setMatrix11-float-) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve birinci sütunundaki öğeyi ayarlar. |
| [getMatrix12()](#getMatrix12--) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve ikinci sütunundaki öğeyi alır. |
| [setMatrix12(float value)](#setMatrix12-float-) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve ikinci sütunundaki öğeyi ayarlar. |
| [getMatrix13()](#getMatrix13--) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve üçüncü sütunundaki öğeyi alır. |
| [setMatrix13(float value)](#setMatrix13-float-) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve üçüncü sütunundaki öğeyi ayarlar. |
| [getMatrix14()](#getMatrix14--) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve dördüncü sütunundaki öğeyi alır. |
| [setMatrix14(float value)](#setMatrix14-float-) | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve dördüncü sütunundaki öğeyi ayarlar. |
| [getMatrix20()](#getMatrix20--) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0 (sıfır) sütunundaki öğeyi alır. |
| [setMatrix20(float value)](#setMatrix20-float-) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0 (sıfır) sütunundaki öğeyi ayarlar. |
| [getMatrix21()](#getMatrix21--) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve birinci sütunundaki öğeyi alır. |
| [setMatrix21(float value)](#setMatrix21-float-) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve birinci sütunundaki öğeyi ayarlar. |
| [getMatrix22()](#getMatrix22--) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğeyi alır. |
| [setMatrix22(float value)](#setMatrix22-float-) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğeyi ayarlar. |
| [getMatrix23()](#getMatrix23--) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğeyi alır. |
| [setMatrix23(float value)](#setMatrix23-float-) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğeyi ayarlar. |
| [getMatrix24()](#getMatrix24--) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğeyi alır. |
| [setMatrix24(float value)](#setMatrix24-float-) | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğeyi ayarlar. |
| [getMatrix30()](#getMatrix30--) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0 (sıfır) sütunundaki öğeyi alır. |
| [setMatrix30(float value)](#setMatrix30-float-) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0 (sıfır) sütunundaki öğeyi ayarlar. |
| [getMatrix31()](#getMatrix31--) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve birinci sütunundaki öğeyi alır. |
| [setMatrix31(float value)](#setMatrix31-float-) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve birinci sütunundaki öğeyi ayarlar. |
| [getMatrix32()](#getMatrix32--) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğeyi alır. |
| [setMatrix32(float value)](#setMatrix32-float-) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğeyi ayarlar. |
| [getMatrix33()](#getMatrix33--) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğeyi alır. |
| [setMatrix33(float value)](#setMatrix33-float-) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğeyi ayarlar. |
| [getMatrix34()](#getMatrix34--) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğeyi alır. |
| [setMatrix34(float value)](#setMatrix34-float-) | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğeyi ayarlar. |
| [getMatrix40()](#getMatrix40--) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0 (sıfır) sütunundaki öğeyi alır. |
| [setMatrix40(float value)](#setMatrix40-float-) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0 (sıfır) sütunundaki öğeyi ayarlar. |
| [getMatrix41()](#getMatrix41--) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğeyi alır. |
| [setMatrix41(float value)](#setMatrix41-float-) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğeyi ayarlar. |
| [getMatrix42()](#getMatrix42--) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğeyi alır. |
| [setMatrix42(float value)](#setMatrix42-float-) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğeyi ayarlar. |
| [getMatrix43()](#getMatrix43--) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğeyi alır. |
| [setMatrix43(float value)](#setMatrix43-float-) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğeyi ayarlar. |
| [getMatrix44()](#getMatrix44--) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğeyi alır. |
| [setMatrix44(float value)](#setMatrix44-float-) | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğeyi ayarlar. |
| [get_Item(int row, int column)](#get-Item-int-int-) | `Aspose.Imaging.ColorMatrix` içinde belirtilen satır ve sütundaki öğeyi alır. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | `Aspose.Imaging.ColorMatrix` içinde belirtilen satır ve sütundaki öğeyi ayarlar. |
| [getMatrix()](#getMatrix--) | Matris değerlerini alır. |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


`Aspose.Imaging.ColorMatrix` sınıfının yeni bir örneğini başlatır.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Belirtilen `newColorMatrix` matrisindeki öğeleri kullanarak `Aspose.Imaging.ColorMatrix` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorMatrix | float[][] | Yeni `Aspose.Imaging.ColorMatrix` için öğelerin değerleri. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


Matris boyutundaki öğe sayısı.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


Matris boyutlarının sayısı.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


Matris içindeki toplam öğe sayısı.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve 0 sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve 0. sütunundaki öğe.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve 0 sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve 0. sütunundaki öğe. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve birinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve birinci sütunundaki öğe.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve birinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve birinci sütunundaki öğe. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve ikinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve ikinci sütunundaki öğe.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve ikinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve ikinci sütunundaki öğe. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve üçüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve üçüncü sütunundaki öğe.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve üçüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve üçüncü sütunundaki öğe. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve dördüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve dördüncü sütunundaki öğe.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in 0 (sıfır) satır ve dördüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in 0. satır ve dördüncü sütunundaki öğe. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0 (sıfır) sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0. sütunundaki öğe.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0 (sıfır) sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve 0. sütunundaki öğe. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve birinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve birinci sütunundaki öğe.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve birinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve ilk sütunundaki öğe. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve ikinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve ikinci sütunundaki öğe.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve ikinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve ikinci sütunundaki öğe. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve üçüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve üçüncü sütunundaki öğe.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve üçüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve üçüncü sütunundaki öğe. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve dördüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve dördüncü sütunundaki öğe.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in birinci satır ve dördüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ilk satır ve dördüncü sütunundaki öğe. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0 (sıfır) sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0. sütunundaki öğe.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0 (sıfır) sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve 0. sütunundaki öğe. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve birinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ilk sütunundaki öğe.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve birinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ilk sütunundaki öğe. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğe.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve ikinci sütunundaki öğe. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğe.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve üçüncü sütunundaki öğe. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğe.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in ikinci satır ve dördüncü sütunundaki öğe. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0 (sıfır) sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0. sütunundaki öğe.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0 (sıfır) sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve 0. sütunundaki öğe. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve birinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ilk sütunundaki öğe.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve birinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ilk sütunundaki öğe. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğe.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve ikinci sütunundaki öğe. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğe.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve üçüncü sütunundaki öğe. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğe.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in üçüncü satır ve dördüncü sütunundaki öğe. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0 (sıfır) sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0. sütunundaki öğe.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0 (sıfır) sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve 0. sütunundaki öğe. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğe.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve birinci sütunundaki öğe. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğe.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve ikinci sütunundaki öğe. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğe.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve üçüncü sütunundaki öğe. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğeyi alır.

**Returns:**
float - Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğe.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu `Aspose.Imaging.ColorMatrix`'in dördüncü satır ve dördüncü sütunundaki öğe. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


`Aspose.Imaging.ColorMatrix` içinde belirtilen satır ve sütundaki öğeyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satır | int | Satır numarası. |
| sütun | int | Sütun numarası. |

**Returns:**
float - Belirtilen satır ve sütundaki öğe.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


`Aspose.Imaging.ColorMatrix` içinde belirtilen satır ve sütundaki öğeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satır | int | Satır numarası. |
| sütun | int | Sütun numarası. |
| değer | float | Değer |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Matris değerlerini alır.

**Returns:**
float[][] - Matris değerleri dizisi.
