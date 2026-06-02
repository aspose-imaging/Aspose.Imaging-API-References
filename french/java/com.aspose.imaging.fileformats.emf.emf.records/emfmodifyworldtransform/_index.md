---
title: "EmfModifyWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_MODIFYWORLDTRANSFORM modifie la transformation de l'espace monde actuel vers l'espace page dans le contexte du dispositif de lecture."
type: docs
weight: 73
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

L'enregistrement EMR\_MODIFYWORLDTRANSFORM modifie la transformation de l'espace monde actuel vers l'espace page dans le contexte de périphérique de lecture.

Pour plus d'informations concernant les transformations et les espaces de coordonnées, voir [MSDN-WRLDPGSPC]. Voir la section 2.3.12 pour la spécification des autres types d'enregistrements de transformation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Initialise une nouvelle instance de la classe `EmfModifyWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Obtient ou définit un entier non signé de 32 bits qui indique comment la transformation spécifiée dans Xform est utilisée. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Obtient ou définit un entier non signé de 32 bits qui indique comment la transformation spécifiée dans Xform est utilisée. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfModifyWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Initialise une nouvelle instance de la classe `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Obtient ou définit un entier non signé de 32 bits qui indique comment la transformation spécifiée dans Xform est utilisée. Cette valeur DOIT appartenir à l'énumération ModifyWorldTransformMode (section 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique comment la transformation spécifiée dans Xform est utilisée. Cette valeur DOIT appartenir à l'énumération ModifyWorldTransformMode (section 2.1.24).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

