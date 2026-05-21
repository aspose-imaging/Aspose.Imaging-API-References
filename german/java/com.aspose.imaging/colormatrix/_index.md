---
title: "ColorMatrix"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert eine 5 x 5-Matrix, die die Koordinaten für den RGBA-Raum enthält."
type: docs
weight: 26
url: /de/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definiert eine 5 x 5-Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der [ImageAttributes](../../com.aspose.imaging/imageattributes)-Klasse passen Bildfarben mithilfe einer Farbmatrix an. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initialisiert eine neue Instanz der `Aspose.Imaging.ColorMatrix`‑Klasse. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initialisiert eine neue Instanz der `Aspose.Imaging.ColorMatrix`‑Klasse unter Verwendung der Elemente in der angegebenen Matrix `newColorMatrix`. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | Die Anzahl der Elemente in der Matrixdimension. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | Die Anzahl der Matrixdimensionen. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | Die Gesamtzahl der Elemente in der Matrix. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Liefert das Element in Zeile 0 (null) und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix00(float value)](#setMatrix00-float-) | Setzt das Element in Zeile 0 (null) und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix01()](#getMatrix01--) | Liefert das Element in Zeile 0 (null) und erster Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix01(float value)](#setMatrix01-float-) | Setzt das Element in Zeile 0 (null) und erster Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix02()](#getMatrix02--) | Liefert das Element in Zeile 0 (null) und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix02(float value)](#setMatrix02-float-) | Setzt das Element in Zeile 0 (null) und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix03()](#getMatrix03--) | Liefert das Element in Zeile 0 (null) und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix03(float value)](#setMatrix03-float-) | Setzt das Element in Zeile 0 (null) und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix04()](#getMatrix04--) | Liefert das Element in Zeile 0 (null) und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix04(float value)](#setMatrix04-float-) | Setzt das Element in Zeile 0 (null) und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix10()](#getMatrix10--) | Liefert das Element in der ersten Zeile und Spalte 0 (null) dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix10(float value)](#setMatrix10-float-) | Setzt das Element in der ersten Zeile und Spalte 0 (null) dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix11()](#getMatrix11--) | Liefert das Element in der ersten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix11(float value)](#setMatrix11-float-) | Setzt das Element in der ersten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix12()](#getMatrix12--) | Liefert das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix12(float value)](#setMatrix12-float-) | Setzt das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix13()](#getMatrix13--) | Liefert das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix13(float value)](#setMatrix13-float-) | Setzt das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix14()](#getMatrix14--) | Liefert das Element in der ersten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [setMatrix14(float value)](#setMatrix14-float-) | Setzt das Element in der ersten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix20()](#getMatrix20--) | Ruft das Element in der zweiten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix20(float value)](#setMatrix20-float-) | Setzt das Element in der zweiten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix21()](#getMatrix21--) | Ruft das Element in der zweiten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix21(float value)](#setMatrix21-float-) | Setzt das Element in der zweiten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix22()](#getMatrix22--) | Ruft das Element in der zweiten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix22(float value)](#setMatrix22-float-) | Setzt das Element in der zweiten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix23()](#getMatrix23--) | Ruft das Element in der zweiten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix23(float value)](#setMatrix23-float-) | Setzt das Element in der zweiten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix24()](#getMatrix24--) | Ruft das Element in der zweiten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix24(float value)](#setMatrix24-float-) | Setzt das Element in der zweiten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix30()](#getMatrix30--) | Ruft das Element in der dritten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix30(float value)](#setMatrix30-float-) | Setzt das Element in der dritten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix31()](#getMatrix31--) | Ruft das Element in der dritten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix31(float value)](#setMatrix31-float-) | Setzt das Element in der dritten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix32()](#getMatrix32--) | Ruft das Element in der dritten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix32(float value)](#setMatrix32-float-) | Setzt das Element in der dritten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix33()](#getMatrix33--) | Ruft das Element in der dritten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix33(float value)](#setMatrix33-float-) | Setzt das Element in der dritten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix34()](#getMatrix34--) | Ruft das Element in der dritten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix34(float value)](#setMatrix34-float-) | Setzt das Element in der dritten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix40()](#getMatrix40--) | Ruft das Element in der vierten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix40(float value)](#setMatrix40-float-) | Setzt das Element in der vierten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix41()](#getMatrix41--) | Ruft das Element in der vierten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix41(float value)](#setMatrix41-float-) | Setzt das Element in der vierten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Ruft das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix42(float value)](#setMatrix42-float-) | Setzt das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix43()](#getMatrix43--) | Ruft das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix43(float value)](#setMatrix43-float-) | Setzt das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [getMatrix44()](#getMatrix44--) | Ruft das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix` ab. |
| [setMatrix44(float value)](#setMatrix44-float-) | Setzt das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Ruft das Element in der angegebenen Zeile und Spalte der `Aspose.Imaging.ColorMatrix` ab. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Setzt das Element in der angegebenen Zeile und Spalte der `Aspose.Imaging.ColorMatrix`. |
| [getMatrix()](#getMatrix--) | Ruft die Matrixwerte ab. |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initialisiert eine neue Instanz der `Aspose.Imaging.ColorMatrix`‑Klasse.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initialisiert eine neue Instanz der `Aspose.Imaging.ColorMatrix`‑Klasse unter Verwendung der Elemente in der angegebenen Matrix `newColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | float[][] | Die Werte der Elemente für die neue `Aspose.Imaging.ColorMatrix`. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


Die Anzahl der Elemente in der Matrixdimension.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


Die Anzahl der Matrixdimensionen.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


Die Gesamtzahl der Elemente in der Matrix.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Liefert das Element in Zeile 0 (null) und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in Zeile 0 und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Setzt das Element in Zeile 0 (null) und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in Zeile 0 und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Liefert das Element in Zeile 0 (null) und erster Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in Zeile 0 und erster Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Setzt das Element in Zeile 0 (null) und erster Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in Zeile 0 und erster Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Liefert das Element in Zeile 0 (null) und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in Zeile 0 und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Setzt das Element in Zeile 0 (null) und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in Zeile 0 und zweiter Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Liefert das Element in Zeile 0 (null) und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in Zeile 0 und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Setzt das Element in Zeile 0 (null) und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in Zeile 0 und dritter Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Liefert das Element in Zeile 0 (null) und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in Zeile 0 und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Setzt das Element in Zeile 0 (null) und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in Zeile 0 und vierter Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Liefert das Element in der ersten Zeile und Spalte 0 (null) dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in erster Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Setzt das Element in der ersten Zeile und Spalte 0 (null) dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in erster Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Liefert das Element in der ersten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in erster Zeile und erster Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Setzt das Element in der ersten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Liefert das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Setzt das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Liefert das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Setzt das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Liefert das Element in der ersten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Das Element in der ersten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Setzt das Element in der ersten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der ersten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Ruft das Element in der zweiten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der zweiten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Setzt das Element in der zweiten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Ruft das Element in der zweiten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der zweiten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Setzt das Element in der zweiten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Ruft das Element in der zweiten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der zweiten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Setzt das Element in der zweiten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Ruft das Element in der zweiten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der zweiten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Setzt das Element in der zweiten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Ruft das Element in der zweiten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der zweiten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Setzt das Element in der zweiten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der zweiten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Ruft das Element in der dritten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der dritten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Setzt das Element in der dritten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Ruft das Element in der dritten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der dritten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Setzt das Element in der dritten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Ruft das Element in der dritten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der dritten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Setzt das Element in der dritten Zeile und zweiten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Ruft das Element in der dritten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der dritten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Setzt das Element in der dritten Zeile und dritten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Ruft das Element in der dritten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der dritten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Setzt das Element in der dritten Zeile und vierten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der dritten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Ruft das Element in der vierten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der vierten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Setzt das Element in der vierten Zeile und 0 (null) Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und Spalte 0 dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Ruft das Element in der vierten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der vierten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Setzt das Element in der vierten Zeile und ersten Spalte dieses `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und ersten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Ruft das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Setzt das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und zweiten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Ruft das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Setzt das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und dritten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Ruft das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix` ab.

**Returns:**
float - Das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Setzt das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Das Element in der vierten Zeile und vierten Spalte dieser `Aspose.Imaging.ColorMatrix`. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Ruft das Element in der angegebenen Zeile und Spalte der `Aspose.Imaging.ColorMatrix` ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |

**Returns:**
float - Das Element in der angegebenen Zeile und Spalte.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Setzt das Element in der angegebenen Zeile und Spalte der `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeile | int | Die Zeilennummer. |
| Spalte | int | Die Spaltennummer. |
| Wert | float | Der Wert |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Ruft die Matrixwerte ab.

**Returns:**
float[][] - Das Array der Matrixwerte.
