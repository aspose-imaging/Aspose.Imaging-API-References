---
title: "EmfDeleteObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_DELETEOBJECT supprime un objet graphique spécifié par son indice dans la table d'objets EMF section 3.1.1.1."
type: docs
weight: 43
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

L'enregistrement EMR\_DELETEOBJECT supprime un objet graphique, qui est spécifié par son indice dans la table des objets EMF (section 3.1.1.1).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfDeleteObject`. |
| [EmfDeleteObject()](#EmfDeleteObject--) | Initialise une nouvelle instance de la classe `EmfDeleteObject`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké de l'énumération StockObject. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké de l'énumération StockObject. |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfDeleteObject`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


Initialise une nouvelle instance de la classe `EmfDeleteObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké de l'énumération StockObject.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'indice d'un objet graphique dans la table d'objets EMF, soit l'indice d'un objet stocké de l'énumération StockObject.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

