---
title: "EmfDeleteColorSpace"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_DELETECOLORSPACE supprime un objet d'espace colorimétrique logique."
type: docs
weight: 42
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_DELETECOLORSPACE supprime un objet d'espace colorimétrique logique.

Un enregistrement EMR\_DELETEOBJECT DOIT être utilisé à la place de EMR\_DELETECOLORSPACE pour supprimer un objet d'espace colorimétrique logique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfDeleteColorSpace`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfDeleteColorSpace`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1).

Cet objet est soit un objet WMF LogColorSpace, soit un objet LogColorSpaceW ([MS-WMF] sections 2.2.2.11 et 2.2.2.12, respectivement).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1).

Cet objet est soit un objet WMF LogColorSpace, soit un objet LogColorSpaceW ([MS-WMF] sections 2.2.2.11 et 2.2.2.12, respectivement).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

