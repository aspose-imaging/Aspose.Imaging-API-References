---
title: "EmfPlusSetWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetWorldTransform définit la transformation du monde selon les valeurs d'une matrice de transformation spécifiée."
type: docs
weight: 68
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusSetWorldTransform définit la transformation du monde selon les valeurs d'une matrice de transformation spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la nouvelle transformation mondiale courante. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la nouvelle transformation mondiale courante. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la nouvelle transformation mondiale courante.

Valeur : les données de la matrice.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Obtient ou définit un objet EmfPlusTransformMatrix (section 2.2.2.47) qui définit la nouvelle transformation mondiale courante.

Valeur : les données de la matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

