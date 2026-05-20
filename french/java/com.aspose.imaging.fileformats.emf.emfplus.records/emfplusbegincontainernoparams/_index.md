---
title: "EmfPlusBeginContainerNoParams"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusBeginContainerNoParams ouvre un nouveau conteneur d'état graphique."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

L'enregistrement EmfPlusBeginContainerNoParams ouvre un nouveau conteneur d'état graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusBeginContainerNoParams`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusBeginContainerNoParams`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer ultérieur (section 2.3.7.3) pour fermer le conteneur d'état graphique.

Valeur : l'indice de la pile.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer ultérieur (section 2.3.7.3) pour fermer le conteneur d'état graphique.

Valeur : l'indice de la pile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

