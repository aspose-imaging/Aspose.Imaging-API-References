---
title: "EmfSelectObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SELECTOBJECT ajoute un objet graphique au contexte de périphérique de lecture du métafichier actuel."
type: docs
weight: 116
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

L'enregistrement EMR\_SELECTOBJECT ajoute un objet graphique au contexte de périphérique de lecture du métafichier actuel. L'objet est spécifié soit par son indice dans la table d'objets EMF (section 3.1.1.1), soit par sa valeur provenant de l'énumération StockObject (section 2.1.31).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | Initialise une nouvelle instance de la classe `EmfSelectObject`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké provenant de l'énumération `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké provenant de l'énumération `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfSelectObject`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Initialise une nouvelle instance de la classe `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké provenant de l'énumération `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké provenant de l'énumération `Consts.EmfStockObject`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

