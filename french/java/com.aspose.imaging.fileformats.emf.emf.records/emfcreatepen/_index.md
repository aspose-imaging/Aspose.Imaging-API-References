---
title: "EmfCreatePen"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATEPEN définit un stylo logique pour les opérations graphiques."
type: docs
weight: 41
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATEPEN définit un stylo logique pour les opérations graphiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | Initialise une nouvelle instance de la classe `EmfCreatePen`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPen()](#getIhPen--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique dans la table d'objets EMF (section 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Obtient ou définit un objet LogPen (section 2.2.19) qui spécifie le style, la largeur et la couleur du stylo logique. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Obtient ou définit un objet LogPen (section 2.2.19) qui spécifie le style, la largeur et la couleur du stylo logique. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreatePen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Initialise une nouvelle instance de la classe `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Obtient ou définit un objet LogPen (section 2.2.19) qui spécifie le style, la largeur et la couleur du stylo logique.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Obtient ou définit un objet LogPen (section 2.2.19) qui spécifie le style, la largeur et la couleur du stylo logique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

