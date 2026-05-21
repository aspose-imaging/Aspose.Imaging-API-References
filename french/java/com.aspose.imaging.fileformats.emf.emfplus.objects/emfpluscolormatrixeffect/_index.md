---
title: "EmfPlusColorMatrixEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet ColorMatrixEffect spécifie une transformation affine à appliquer à une image."
type: docs
weight: 29
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolormatrixeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorMatrixEffect extends EmfPlusImageEffectsObjectType
```

L'objet ColorMatrixEffect spécifie une transformation affine à appliquer à une image.

Les images bitmap sont spécifiées par des objets EmfPlusBitmap (section 2.2.2.2). Un effet de matrice de couleur est réalisé en multipliant un vecteur couleur par un objet ColorMatrixEffect. Une matrice de couleur 5×5 peut effectuer une transformation linéaire, incluant la réflexion, la rotation, le cisaillement ou le redimensionnement suivi d'une translation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusColorMatrixEffect()](#EmfPlusColorMatrixEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMatrixN0()](#getMatrixN0--) | Obtient ou définit le Matrix[N][0] de la matrice de couleur 5×5. |
| [setMatrixN0(int[] value)](#setMatrixN0-int---) | Obtient ou définit le Matrix[N][0] de la matrice de couleur 5×5. |
| [getMatrixN1()](#getMatrixN1--) | Obtient ou définit le Matrix[N][1] de la matrice de couleur 5×5. |
| [setMatrixN1(int[] value)](#setMatrixN1-int---) | Obtient ou définit le Matrix[N][1] de la matrice de couleur 5×5. |
| [getMatrixN2()](#getMatrixN2--) | Obtient ou définit le Matrix[N][2] de la matrice de couleur 5×5. |
| [setMatrixN2(int[] value)](#setMatrixN2-int---) | Obtient ou définit le Matrix[N][2] de la matrice de couleur 5×5. |
| [getMatrixN3()](#getMatrixN3--) | Obtient ou définit le Matrix[N][3] de la matrice de couleur 5×5. |
| [setMatrixN3(int[] value)](#setMatrixN3-int---) | Obtient ou définit le Matrix[N][3] de la matrice de couleur 5×5. |
| [getMatrixN4()](#getMatrixN4--) | Obtient ou définit le Matrix[N][4] de la matrice de couleur 5×5. |
| [setMatrixN4(int[] value)](#setMatrixN4-int---) | Obtient ou définit le Matrix[N][4] de la matrice de couleur 5×5. |
| [getMatrix()](#getMatrix--) | Obtient ou définit la matrice. |
| [setMatrix(int[][] value)](#setMatrix-int-----) | Obtient ou définit la matrice. |
### EmfPlusColorMatrixEffect() {#EmfPlusColorMatrixEffect--}
```
public EmfPlusColorMatrixEffect()
```


### getMatrixN0() {#getMatrixN0--}
```
public int[] getMatrixN0()
```


Obtient ou définit le Matrix[N][0] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Matrix\_0\_0 (4 octets) : Matrix[0][0], qui est le facteur pour la couleur rouge. Matrix\_1\_0 (4 octets) : Matrix[1][0]. Matrix\_2\_0 (4 octets) : Matrix[2][0]. Matrix\_3\_0 (4 octets) : Matrix[3][0]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Returns:**
int[]
### setMatrixN0(int[] value) {#setMatrixN0-int---}
```
public void setMatrixN0(int[] value)
```


Obtient ou définit le Matrix[N][0] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Matrix\_0\_0 (4 octets) : Matrix[0][0], qui est le facteur pour la couleur rouge. Matrix\_1\_0 (4 octets) : Matrix[1][0]. Matrix\_2\_0 (4 octets) : Matrix[2][0]. Matrix\_3\_0 (4 octets) : Matrix[3][0]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getMatrixN1() {#getMatrixN1--}
```
public int[] getMatrixN1()
```


Obtient ou définit le Matrix[N][1] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_1 (4 octets) : Matrix[0][1]. Matrix\_1\_1 (4 octets) : Matrix[1][1], qui est le facteur pour la couleur verte. Matrix\_2\_1 (4 octets) : Matrix[2][1]. Matrix\_3\_1 (4 octets) : Matrix[3][1]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Returns:**
int[]
### setMatrixN1(int[] value) {#setMatrixN1-int---}
```
public void setMatrixN1(int[] value)
```


Obtient ou définit le Matrix[N][1] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_1 (4 octets) : Matrix[0][1]. Matrix\_1\_1 (4 octets) : Matrix[1][1], qui est le facteur pour la couleur verte. Matrix\_2\_1 (4 octets) : Matrix[2][1]. Matrix\_3\_1 (4 octets) : Matrix[3][1]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getMatrixN2() {#getMatrixN2--}
```
public int[] getMatrixN2()
```


Obtient ou définit le Matrix[N][2] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_2 (4 octets) : Matrix[0][2]. Matrix\_1\_2 (4 octets) : Matrix[1][2]. Matrix\_2\_2 (4 octets) : Matrix[2][2], qui est le facteur pour la couleur bleue. Matrix\_3\_1 (4 octets) : Matrix[3][1]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Returns:**
int[]
### setMatrixN2(int[] value) {#setMatrixN2-int---}
```
public void setMatrixN2(int[] value)
```


Obtient ou définit le Matrix[N][2] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_2 (4 octets) : Matrix[0][2]. Matrix\_1\_2 (4 octets) : Matrix[1][2]. Matrix\_2\_2 (4 octets) : Matrix[2][2], qui est le facteur pour la couleur bleue. Matrix\_3\_1 (4 octets) : Matrix[3][1]. Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getMatrixN3() {#getMatrixN3--}
```
public int[] getMatrixN3()
```


Obtient ou définit le Matrix[N][3] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_3 (4 octets) : Matrix[0][3]. Matrix\_1\_3 (4 octets) : Matrix[1][3]. Matrix\_2\_3 (4 octets) : Matrix[2][3]. Matrix\_3\_3 (4 octets) : Matrix[3][3], qui est le facteur pour l'alpha (transparence). Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Returns:**
int[]
### setMatrixN3(int[] value) {#setMatrixN3-int---}
```
public void setMatrixN3(int[] value)
```


Obtient ou définit le Matrix[N][3] de la matrice de couleur 5×5. Cette ligne est utilisée pour les transformations.

Valeur : la matrice n1.

Matrix\_0\_3 (4 octets) : Matrix[0][3]. Matrix\_1\_3 (4 octets) : Matrix[1][3]. Matrix\_2\_3 (4 octets) : Matrix[2][3]. Matrix\_3\_3 (4 octets) : Matrix[3][3], qui est le facteur pour l'alpha (transparence). Matrix\_4\_0 (4 octets) : Matrix[4][0]. Cette valeur DOIT être 0,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getMatrixN4() {#getMatrixN4--}
```
public int[] getMatrixN4()
```


Obtient ou définit la Matrix[N][4] de la matrice de couleur 5x5. Cette ligne est utilisée pour les traductions de couleur.

Valeur : la matrice n1.

Matrix\_0\_4 (4 octets): Matrix[0][4]. Matrix\_1\_4 (4 octets): Matrix[1][4]. Matrix\_2\_4 (4 octets): Matrix[2][4]. Matrix\_3\_4 (4 octets): Matrix[3][4]. Matrix\_4\_4 (4 octets): Matrix[4][4]. Cette valeur DOIT être 1.0.

**Returns:**
int[]
### setMatrixN4(int[] value) {#setMatrixN4-int---}
```
public void setMatrixN4(int[] value)
```


Obtient ou définit la Matrix[N][4] de la matrice de couleur 5x5. Cette ligne est utilisée pour les traductions de couleur.

Valeur : la matrice n1.

Matrix\_0\_4 (4 octets): Matrix[0][4]. Matrix\_1\_4 (4 octets): Matrix[1][4]. Matrix\_2\_4 (4 octets): Matrix[2][4]. Matrix\_3\_4 (4 octets): Matrix[3][4]. Matrix\_4\_4 (4 octets): Matrix[4][4]. Cette valeur DOIT être 1.0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getMatrix() {#getMatrix--}
```
public int[][] getMatrix()
```


Obtient ou définit la matrice.

Valeur: la matrice.

**Returns:**
int[][]
### setMatrix(int[][] value) {#setMatrix-int-----}
```
public void setMatrix(int[][] value)
```


Obtient ou définit la matrice.

Valeur: la matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[][] |  |

