---
title: "EmfPlusColorMatrixEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "ColorMatrixEffect-objektet specificerar en affin transformation som ska tillämpas på en bild."
type: docs
weight: 29
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

ColorMatrixEffect-objektet specificerar en affin transformation som ska tillämpas på en bild.

Bitmap-bilder specificeras av EmfPlusBitmap‑objekt (avsnitt 2.2.2.2). En färgmatriseffekt utförs genom att multiplicera en färgvektor med ett ColorMatrixEffect‑objekt. En 5×5 färgmatris kan utföra en linjär transformation, inklusive reflektion, rotation, skevning eller skalning följt av en translation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Hämtar eller anger Matrix[N][0] i den 5×5 färgmatrisen. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Hämtar eller anger Matrix[N][0] i den 5×5 färgmatrisen. |
| [getMatrixN1()](#getMatrixN1--) | Hämtar eller anger Matrix[N][1] i den 5×5 färgmatrisen. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Hämtar eller anger Matrix[N][1] i den 5×5 färgmatrisen. |
| [getMatrixN2()](#getMatrixN2--) | Hämtar eller anger Matrix[N][2] i den 5×5 färgmatrisen. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Hämtar eller anger Matrix[N][2] i den 5×5 färgmatrisen. |
| [getMatrixN3()](#getMatrixN3--) | Hämtar eller anger Matrix[N][3] i den 5×5 färgmatrisen. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Hämtar eller anger Matrix[N][3] i den 5×5 färgmatrisen. |
| [getMatrixN4()](#getMatrixN4--) | Hämtar eller anger Matrix[N][4] i den 5×5 färgmatrisen. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Hämtar eller anger Matrix[N][4] i den 5×5 färgmatrisen. |
| [getMatrix()](#getMatrix--) | Hämtar eller anger matrisen. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Hämtar eller anger matrisen. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Hämtar eller anger Matrix[N][0] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Matrix\_0\_0 (4 bytes): Matrix[0][0], vilket är faktorn för färgen röd. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Hämtar eller anger Matrix[N][0] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Matrix\_0\_0 (4 bytes): Matrix[0][0], vilket är faktorn för färgen röd. Matrix\_1\_0 (4 bytes): Matrix[1][0]. Matrix\_2\_0 (4 bytes): Matrix[2][0]. Matrix\_3\_0 (4 bytes): Matrix[3][0]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Hämtar eller anger Matrix[N][1] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], vilket är faktorn för färgen grön. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Hämtar eller anger Matrix[N][1] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_1 (4 bytes): Matrix[0][1]. Matrix\_1\_1 (4 bytes): Matrix[1][1], vilket är faktorn för färgen grön. Matrix\_2\_1 (4 bytes): Matrix[2][1]. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Hämtar eller anger Matrix[N][2] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], vilket är faktorn för färgen blå. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Hämtar eller anger Matrix[N][2] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_2 (4 bytes): Matrix[0][2]. Matrix\_1\_2 (4 bytes): Matrix[1][2]. Matrix\_2\_2 (4 bytes): Matrix[2][2], vilket är faktorn för färgen blå. Matrix\_3\_1 (4 bytes): Matrix[3][1]. Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Hämtar eller anger Matrix[N][3] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], vilket är faktorn för alfan (transparens) Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Hämtar eller anger Matrix[N][3] i den 5×5 färgmatrisen. Denna rad används för transformationer.

Värde: Matrisen n1.

Matrix\_0\_3 (4 bytes): Matrix[0][3]. Matrix\_1\_3 (4 bytes): Matrix[1][3]. Matrix\_2\_3 (4 bytes): Matrix[2][3]. Matrix\_3\_3 (4 bytes): Matrix[3][3], vilket är faktorn för alfan (transparens) Matrix\_4\_0 (4 bytes): Matrix[4][0]. Detta värde MÅSTE vara 0.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Hämtar eller anger Matrix[N][4] i den 5x5 färgmatrisen. Denna rad används för färgöversättningar.

Värde: Matrisen n1.

Matrix\_0\_4 (4 byte): Matrix[0][4]. Matrix\_1\_4 (4 byte): Matrix[1][4]. Matrix\_2\_4 (4 byte): Matrix[2][4]. Matrix\_3\_4 (4 byte): Matrix[3][4]. Matrix\_4\_4 (4 byte): Matrix[4][4]. Detta värde SKALL vara 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Hämtar eller anger Matrix[N][4] i den 5x5 färgmatrisen. Denna rad används för färgöversättningar.

Värde: Matrisen n1.

Matrix\_0\_4 (4 byte): Matrix[0][4]. Matrix\_1\_4 (4 byte): Matrix[1][4]. Matrix\_2\_4 (4 byte): Matrix[2][4]. Matrix\_3\_4 (4 byte): Matrix[3][4]. Matrix\_4\_4 (4 byte): Matrix[4][4]. Detta värde SKALL vara 1.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Hämtar eller anger matrisen.

Värde: Matrisen.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Hämtar eller anger matrisen.

Värde: Matrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[][] |  |

