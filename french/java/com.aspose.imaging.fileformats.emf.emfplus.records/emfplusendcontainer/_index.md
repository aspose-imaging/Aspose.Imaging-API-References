---
title: "EmfPlusEndContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusEndContainer ferme un conteneur d'état graphique qui avait été précédemment ouvert par une opération de début de conteneur."
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

L'enregistrement EmfPlusEndContainer ferme un conteneur d'état graphique qui avait été précédemment ouvert par une opération de début de conteneur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusEndContainer`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un conteneur d'état graphique. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un conteneur d'état graphique. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusEndContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un conteneur d'état graphique. L'index DOIT correspondre à la valeur associée à un conteneur d'état graphique ouvert par un enregistrement EmfPlusBeginContainer (section 2.3.7.1) ou EmfPlusBeginContainerNoParams (section 2.3.7.2).

Valeur : l'indice de la pile.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un conteneur d'état graphique. L'index DOIT correspondre à la valeur associée à un conteneur d'état graphique ouvert par un enregistrement EmfPlusBeginContainer (section 2.3.7.1) ou EmfPlusBeginContainerNoParams (section 2.3.7.2).

Valeur : l'indice de la pile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

