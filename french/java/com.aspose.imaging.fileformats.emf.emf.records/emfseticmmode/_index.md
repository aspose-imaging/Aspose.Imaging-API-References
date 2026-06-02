---
title: "EmfSetIcmMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETICMMODE spécifie le mode de gestion des couleurs d'image ICM pour les opérations graphiques."
type: docs
weight: 125
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

L'enregistrement EMR\_SETICMMODE spécifie le mode de la gestion des couleurs d'image (ICM) pour les opérations graphiques.

Lorsque le mode ICM est activé, les couleurs spécifiées dans les enregistrements EMF DOIVENT être assorties, tandis que le profil couleur par défaut dans le contexte du dispositif de lecture DOIT être utilisé lors d'un transfert de blocs de bits. Si le profil couleur par défaut n'est pas souhaité, le mode ICM DOIT être désactivé avant d'effectuer le transfert de blocs de bits.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetIcmMode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Obtient ou définit un entier non signé de 32 bits qui indique s'il faut activer ou désactiver ICM, à partir de l'énumération ICMMode (section 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Obtient ou définit un entier non signé de 32 bits qui indique s'il faut activer ou désactiver ICM, à partir de l'énumération ICMMode (section 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetIcmMode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Obtient ou définit un entier non signé de 32 bits qui indique s'il faut activer ou désactiver ICM, à partir de l'énumération ICMMode (section 2.1.18). Cette valeur fait partie de l'état du contexte du dispositif de lecture.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique s'il faut activer ou désactiver ICM, à partir de l'énumération ICMMode (section 2.1.18). Cette valeur fait partie de l'état du contexte du dispositif de lecture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

