---
title: "EmfPlusSave"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSave enregistre l'état graphique identifié par un index spécifié sur une pile d'états graphiques enregistrés."
type: docs
weight: 51
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

L'enregistrement EmfPlusSave enregistre l'état graphique, identifié par un indice spécifié, sur une pile d'états graphiques enregistrés.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSave`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtient ou définit un entier non signé de 32 bits qui spécifie un niveau à associer à l’état graphique. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie un niveau à associer à l’état graphique. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSave`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un niveau à associer à l’état graphique. La valeur du niveau peut être utilisée par un enregistrement EmfPlusRestore subséquent (section 2.3.7.4) pour récupérer l’état graphique.

Valeur : l'indice de la pile.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un niveau à associer à l’état graphique. La valeur du niveau peut être utilisée par un enregistrement EmfPlusRestore subséquent (section 2.3.7.4) pour récupérer l’état graphique.

Valeur : l'indice de la pile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

