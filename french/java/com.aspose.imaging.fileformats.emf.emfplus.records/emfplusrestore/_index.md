---
title: "EmfPlusRestore"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusRestore restaure l'état graphique identifié par un index spécifié à partir d'une pile d'états graphiques enregistrés."
type: docs
weight: 49
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

L'enregistrement EmfPlusRestore restaure l'état graphique, identifié par un indice spécifié, à partir d'une pile d'états graphiques enregistrés.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusRestore`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau associé à un état graphique. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau associé à un état graphique. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusRestore`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau associé à un état graphique. La valeur du niveau a été attribuée à l'état graphique par un enregistrement EmfPlusSave précédent (section 2.3.7.5).

Valeur : l'indice de la pile.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le niveau associé à un état graphique. La valeur du niveau a été attribuée à l'état graphique par un enregistrement EmfPlusSave précédent (section 2.3.7.5).

Valeur : l'indice de la pile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

