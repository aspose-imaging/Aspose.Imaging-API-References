---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusMultiplyWorldTransform multiplie la transformation de l'espace mondial actuel par une matrice de transformation spécifiée."
type: docs
weight: 41
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusMultiplyWorldTransform multiplie la transformation de l'espace mondial actuel par une matrice de transformation spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusMultiplyWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtient une valeur indiquant si [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la matrice de multiplication. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la matrice de multiplication. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtient une valeur indiquant si [post multiplied matrix]. Si elle est définie, la matrice de transformation doit être post‑multipliée. Si elle est désactivée, elle doit être pré‑multipliée.

Valeur : `true` si [post multiplied matrix] ; sinon, `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la matrice de multiplication.

Valeur : les données de la matrice.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la matrice de multiplication.

Valeur : les données de la matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

