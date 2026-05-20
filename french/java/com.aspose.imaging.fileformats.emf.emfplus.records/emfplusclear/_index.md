---
title: "EmfPlusClear"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusClear efface l'espace de coordonnées de sortie et l'initialise avec une couleur d'arrière-plan et de la transparence."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

L'enregistrement EmfPlusClear efface l'espace de coordonnées de sortie et l'initialise avec une couleur d'arrière-plan et de la transparence.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusClear`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Obtient ou définit la couleur. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Obtient ou définit la couleur. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusClear`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Obtient ou définit la couleur. Un objet EmfPlusARGB (section 2.2.2.1) qui définit la couleur à appliquer à l'écran. Toutes les couleurs sont spécifiées en [IEC-RGB], sauf indication contraire.

Valeur: la couleur.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Obtient ou définit la couleur. Un objet EmfPlusARGB (section 2.2.2.1) qui définit la couleur à appliquer à l'écran. Toutes les couleurs sont spécifiées en [IEC-RGB], sauf indication contraire.

Valeur: la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

