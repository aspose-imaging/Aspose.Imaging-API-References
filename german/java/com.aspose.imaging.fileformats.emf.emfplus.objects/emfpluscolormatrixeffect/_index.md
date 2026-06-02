---
title: "EmfPlusColorMatrixEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das ColorMatrixEffect-Objekt gibt eine affine Transformation an, die auf ein Bild angewendet wird."
type: docs
weight: 29
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

Das ColorMatrixEffect-Objekt gibt eine affine Transformation an, die auf ein Bild angewendet wird.

Bitmap‑Bilder werden durch EmfPlusBitmap‑Objekte (Abschnitt 2.2.2.2) angegeben. Ein Farbmatrix‑Effekt wird durchgeführt, indem ein Farbvektor mit einem ColorMatrixEffect‑Objekt multipliziert wird. Eine 5x5‑Farbmatrix kann eine lineare Transformation ausführen, einschließlich Spiegelung, Drehung, Scherung oder Skalierung, gefolgt von einer Translation.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Liest oder legt fest die Matrix[N][0] der 5x5‑Farbmatrix. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Liest oder legt fest die Matrix[N][0] der 5x5‑Farbmatrix. |
| [getMatrixN1()](#getMatrixN1--) | Liest oder legt fest die Matrix[N][1] der 5x5‑Farbmatrix. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Liest oder legt fest die Matrix[N][1] der 5x5‑Farbmatrix. |
| [getMatrixN2()](#getMatrixN2--) | Liest oder legt fest die Matrix[N][2] der 5x5‑Farbmatrix. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Liest oder legt fest die Matrix[N][2] der 5x5‑Farbmatrix. |
| [getMatrixN3()](#getMatrixN3--) | Liest oder legt fest die Matrix[N][3] der 5x5‑Farbmatrix. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Liest oder legt fest die Matrix[N][3] der 5x5‑Farbmatrix. |
| [getMatrixN4()](#getMatrixN4--) | Liest oder legt fest die Matrix[N][4] der 5x5‑Farbmatrix. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Liest oder legt fest die Matrix[N][4] der 5x5‑Farbmatrix. |
| [getMatrix()](#getMatrix--) | Liest oder legt fest die Matrix. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Liest oder legt fest die Matrix. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Liest oder legt fest die Matrix[N][0] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Matrix\_0\_0 (4 bytes): Matrix[0][0], der Faktor für die Farbe Rot. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Liest oder legt fest die Matrix[N][0] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Matrix\_0\_0 (4 bytes): Matrix[0][0], der Faktor für die Farbe Rot. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Liest oder legt fest die Matrix[N][1] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], der Faktor für die Farbe Grün. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Liest oder legt fest die Matrix[N][1] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], der Faktor für die Farbe Grün. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Liest oder legt fest die Matrix[N][2] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], der Faktor für die Farbe Blau. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Liest oder legt fest die Matrix[N][2] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], der Faktor für die Farbe Blau. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Liest oder legt fest die Matrix[N][3] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], der Faktor für das Alpha (Transparenz). Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Liest oder legt fest die Matrix[N][3] der 5x5‑Farbmatrix. Diese Zeile wird für Transformationen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], der Faktor für das Alpha (Transparenz). Matrix\_4\_0 (4 bytes): Matrix[4][0]. Dieser Wert MUSS 0.0 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Liest oder schreibt die Matrix[N][4] der 5x5-Farbmatrix. Diese Zeile wird für Farbübersetzungen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_4 (4 Bytes): Matrix[0][4]. Matrix\_1\_4 (4 Bytes): Matrix[1][4]. Matrix\_2\_4 (4 Bytes): Matrix[2][4]. Matrix\_3\_4 (4 Bytes): Matrix[3][4]. Matrix\_4\_4 (4 Bytes): Matrix[4][4]. Dieser Wert SOLLTE 1.0 sein.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Liest oder schreibt die Matrix[N][4] der 5x5-Farbmatrix. Diese Zeile wird für Farbübersetzungen verwendet.

Wert: Die Matrix n1.

Matrix\_0\_4 (4 Bytes): Matrix[0][4]. Matrix\_1\_4 (4 Bytes): Matrix[1][4]. Matrix\_2\_4 (4 Bytes): Matrix[2][4]. Matrix\_3\_4 (4 Bytes): Matrix[3][4]. Matrix\_4\_4 (4 Bytes): Matrix[4][4]. Dieser Wert SOLLTE 1.0 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Liest oder legt fest die Matrix.

Wert: Die Matrix.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Liest oder legt fest die Matrix.

Wert: Die Matrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[][] |  |

