---
title: "ColorMatrix"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden."
type: docs
weight: 26
url: /sv/java/com.aspose.imaging/colormatrix/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden. Flera metoder i klassen [ImageAttributes](../../com.aspose.imaging/imageattributes) justerar bildfärger genom att använda en färgmatris. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Initierar en ny instans av klassen `Aspose.Imaging.ColorMatrix`. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Initierar en ny instans av klassen `Aspose.Imaging.ColorMatrix` med elementen i den angivna matrisen `newColorMatrix`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MATRIX_DIMENSION_ELEMENTS_COUNT](#MATRIX-DIMENSION-ELEMENTS-COUNT) | Antalet element i matrisens dimension. |
| [MATRIX_DIMENSIONS_COUNT](#MATRIX-DIMENSIONS-COUNT) | Antalet matrisdimensioner. |
| [MATRIX_TOTAL_ELEMENTS_COUNT](#MATRIX-TOTAL-ELEMENTS-COUNT) | Det totala antalet element i matrisen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMatrix00()](#getMatrix00--) | Hämtar elementet på rad 0 (noll) och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix00(float value)](#setMatrix00-float-) | Sätter elementet på rad 0 (noll) och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix01()](#getMatrix01--) | Hämtar elementet på rad 0 (noll) och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix01(float value)](#setMatrix01-float-) | Sätter elementet på rad 0 (noll) och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix02()](#getMatrix02--) | Hämtar elementet på rad 0 (noll) och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix02(float value)](#setMatrix02-float-) | Sätter elementet på rad 0 (noll) och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix03()](#getMatrix03--) | Hämtar elementet på rad 0 (noll) och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix03(float value)](#setMatrix03-float-) | Sätter elementet på rad 0 (noll) och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix04()](#getMatrix04--) | Hämtar elementet på rad 0 (noll) och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix04(float value)](#setMatrix04-float-) | Sätter elementet på rad 0 (noll) och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix10()](#getMatrix10--) | Hämtar elementet på första raden och kolumn 0 (noll) i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix10(float value)](#setMatrix10-float-) | Sätter elementet på första raden och kolumn 0 (noll) i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix11()](#getMatrix11--) | Hämtar elementet på första raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix11(float value)](#setMatrix11-float-) | Sätter elementet på första raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix12()](#getMatrix12--) | Hämtar elementet på första raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix12(float value)](#setMatrix12-float-) | Sätter elementet på första raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix13()](#getMatrix13--) | Hämtar elementet på första raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix13(float value)](#setMatrix13-float-) | Sätter elementet på första raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix14()](#getMatrix14--) | Hämtar elementet på första raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix14(float value)](#setMatrix14-float-) | Ställer in elementet på den första raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix20()](#getMatrix20--) | Hämtar elementet på den andra raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix20(float value)](#setMatrix20-float-) | Ställer in elementet på den andra raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix21()](#getMatrix21--) | Hämtar elementet på den andra raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix21(float value)](#setMatrix21-float-) | Ställer in elementet på den andra raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix22()](#getMatrix22--) | Hämtar elementet på den andra raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix22(float value)](#setMatrix22-float-) | Ställer in elementet på den andra raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix23()](#getMatrix23--) | Hämtar elementet på den andra raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix23(float value)](#setMatrix23-float-) | Ställer in elementet på den andra raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix24()](#getMatrix24--) | Hämtar elementet på den andra raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix24(float value)](#setMatrix24-float-) | Ställer in elementet på den andra raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix30()](#getMatrix30--) | Hämtar elementet på den tredje raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix30(float value)](#setMatrix30-float-) | Ställer in elementet på den tredje raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix31()](#getMatrix31--) | Hämtar elementet på den tredje raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix31(float value)](#setMatrix31-float-) | Ställer in elementet på den tredje raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix32()](#getMatrix32--) | Hämtar elementet på den tredje raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix32(float value)](#setMatrix32-float-) | Ställer in elementet på den tredje raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix33()](#getMatrix33--) | Hämtar elementet på den tredje raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix33(float value)](#setMatrix33-float-) | Ställer in elementet på den tredje raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix34()](#getMatrix34--) | Hämtar elementet på den tredje raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix34(float value)](#setMatrix34-float-) | Ställer in elementet på den tredje raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix40()](#getMatrix40--) | Hämtar elementet på den fjärde raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix40(float value)](#setMatrix40-float-) | Ställer in elementet på den fjärde raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix41()](#getMatrix41--) | Hämtar elementet på den fjärde raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [setMatrix41(float value)](#setMatrix41-float-) | Ställer in elementet på den fjärde raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |
| [getMatrix42()](#getMatrix42--) | Hämtar elementet i den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix42(float value)](#setMatrix42-float-) | Sätter elementet i den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix43()](#getMatrix43--) | Hämtar elementet i den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix43(float value)](#setMatrix43-float-) | Sätter elementet i den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [getMatrix44()](#getMatrix44--) | Hämtar elementet i den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [setMatrix44(float value)](#setMatrix44-float-) | Sätter elementet i den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Hämtar elementet på den angivna raden och kolumnen i `Aspose.Imaging.ColorMatrix`. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Sätter elementet på den angivna raden och kolumnen i `Aspose.Imaging.ColorMatrix`. |
| [getMatrix()](#getMatrix--) | Hämtar matrisvärdena. |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Initierar en ny instans av klassen `Aspose.Imaging.ColorMatrix`.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Initierar en ny instans av klassen `Aspose.Imaging.ColorMatrix` med elementen i den angivna matrisen `newColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | float[][] | Värdena för elementen i den nya `Aspose.Imaging.ColorMatrix`. |

### MATRIX_DIMENSION_ELEMENTS_COUNT {#MATRIX-DIMENSION-ELEMENTS-COUNT}
```
public static final int MATRIX_DIMENSION_ELEMENTS_COUNT
```


Antalet element i matrisens dimension.

### MATRIX_DIMENSIONS_COUNT {#MATRIX-DIMENSIONS-COUNT}
```
public static final int MATRIX_DIMENSIONS_COUNT
```


Antalet matrisdimensioner.

### MATRIX_TOTAL_ELEMENTS_COUNT {#MATRIX-TOTAL-ELEMENTS-COUNT}
```
public static final int MATRIX_TOTAL_ELEMENTS_COUNT
```


Det totala antalet element i matrisen.

### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Hämtar elementet på rad 0 (noll) och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i rad 0 och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Sätter elementet på rad 0 (noll) och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i rad 0 och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Hämtar elementet på rad 0 (noll) och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i rad 0 och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Sätter elementet på rad 0 (noll) och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i rad 0 och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Hämtar elementet på rad 0 (noll) och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i rad 0 och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Sätter elementet på rad 0 (noll) och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i rad 0 och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Hämtar elementet på rad 0 (noll) och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i rad 0 och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Sätter elementet på rad 0 (noll) och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i rad 0 och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Hämtar elementet på rad 0 (noll) och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i rad 0 och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Sätter elementet på rad 0 (noll) och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i rad 0 och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Hämtar elementet på första raden och kolumn 0 (noll) i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i första raden och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Sätter elementet på första raden och kolumn 0 (noll) i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet i första raden och kolumn 0 i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Hämtar elementet på första raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet i första raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Sätter elementet på första raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och den första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Hämtar elementet på första raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den första raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Sätter elementet på första raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Hämtar elementet på första raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den första raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Sätter elementet på första raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Hämtar elementet på första raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den första raden och den fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Ställer in elementet på den första raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den första raden och den fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Hämtar elementet på den andra raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den andra raden och 0 kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Ställer in elementet på den andra raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och 0 kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Hämtar elementet på den andra raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den andra raden och den första kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Ställer in elementet på den andra raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och den första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Hämtar elementet på den andra raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den andra raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Ställer in elementet på den andra raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Hämtar elementet på den andra raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den andra raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Ställer in elementet på den andra raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Hämtar elementet på den andra raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den andra raden och den fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Ställer in elementet på den andra raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den andra raden och den fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Hämtar elementet på den tredje raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den tredje raden och 0 kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Ställer in elementet på den tredje raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och 0 kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Hämtar elementet på den tredje raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den tredje raden och den första kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Ställer in elementet på den tredje raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och den första kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Hämtar elementet på den tredje raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den tredje raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Ställer in elementet på den tredje raden och andra kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och den andra kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Hämtar elementet på den tredje raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den tredje raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.
### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Ställer in elementet på den tredje raden och tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och den tredje kolumnen i detta `Aspose.Imaging.ColorMatrix`. |

### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Hämtar elementet på den tredje raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den tredje raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Ställer in elementet på den tredje raden och fjärde kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den tredje raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Hämtar elementet på den fjärde raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den fjärde raden och 0 kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Ställer in elementet på den fjärde raden och 0 (noll) kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och 0 kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Hämtar elementet på den fjärde raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den fjärde raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Ställer in elementet på den fjärde raden och första kolumnen i detta `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och första kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Hämtar elementet i den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Sätter elementet i den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och andra kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Hämtar elementet i den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Sätter elementet i den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och tredje kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Hämtar elementet i den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Returns:**
float - Elementet på den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.
### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Sätter elementet i den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Elementet på den fjärde raden och fjärde kolumnen i denna `Aspose.Imaging.ColorMatrix`. |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Hämtar elementet på den angivna raden och kolumnen i `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |

**Returns:**
float - Elementet på den angivna raden och kolumnen.
### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Sätter elementet på den angivna raden och kolumnen i `Aspose.Imaging.ColorMatrix`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rad | int | Radnumret. |
| kolumn | int | Kolumnnumret. |
| värde | float | Värdet |

### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Hämtar matrisvärdena.

**Returns:**
float[][] - Matrisens värdearray.
