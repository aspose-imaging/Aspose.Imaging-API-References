---
title: "EmfResizePalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_RESIZEPALETTE augmente ou diminue la taille d'un objet LogPalette existant section 2.2.17."
type: docs
weight: 108
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_RESIZEPALETTE augmente ou diminue la taille d'un objet LogPalette existant (section 2.2.17).

La nouvelle taille de l'objet LogPalette DOIT être reflétée dans le champ NumberOfEntries de cette structure.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfResizePalette`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette dans la table d'objets EMF (section 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette dans la table d'objets EMF (section 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfResizePalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette dans la table d'objets EMF (section 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette dans la table d'objets EMF (section 3.1.1.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

