---
title: "EmfPlusTranslateWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusTranslateWorldTransform effectue une translation sur la transformation de l'espace monde actuel."
type: docs
weight: 72
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusTranslateWorldTransform effectue une translation sur la transformation de l'espace monde actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusTranslateWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtient une valeur indiquant si [post multiplied matrix]. |
| [getDx()](#getDx--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la distance horizontale. |
| [setDx(float value)](#setDx-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la distance horizontale. |
| [getDy()](#getDy--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la valeur de la distance verticale. |
| [setDy(float value)](#setDy-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la valeur de la distance verticale. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusTranslateWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtient une valeur indiquant si [post multiplied matrix]. Si défini, la matrice de transformation doit être post‑multipliée. Si non défini, elle doit être pré‑multipliée.

Valeur : `true` si [post multiplied matrix] ; sinon, `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la distance horizontale. La translation est effectuée en construisant une nouvelle matrice de transformation du monde à partir des champs dx et dy.

Valeur : le dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la distance horizontale. La translation est effectuée en construisant une nouvelle matrice de transformation du monde à partir des champs dx et dy.

Valeur : le dx.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la valeur de la distance verticale.

Valeur : le dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui définit la valeur de la distance verticale.

Valeur : le dy.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

