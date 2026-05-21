---
title: "EmfSetColorSpace"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_SETCOLORSPACE définit l’objet d’espace couleur logique actuel pour les opérations graphiques."
type: docs
weight: 123
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_SETCOLORSPACE définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques.

L'objet d'espace colorimétrique logique défini par cet enregistrement DOIT être utilisé dans les opérations de dessin spécifiées par les enregistrements EMF suivants, jusqu'à ce qu'un autre objet d'espace colorimétrique logique soit spécifié par un autre enregistrement EMR\_SETCOLORSPACE, ou que l'objet soit supprimé par un enregistrement EMR\_DELETECOLORSPACE.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetColorSpace`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index d'un objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetColorSpace`.

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

