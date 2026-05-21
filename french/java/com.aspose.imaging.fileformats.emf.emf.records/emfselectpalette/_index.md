---
title: "EmfSelectPalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_SELECTPALETTE spécifie une palette logique pour le contexte de périphérique de lecture."
type: docs
weight: 117
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_SELECTPALETTE spécifie une palette logique pour le contexte de dispositif de lecture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSelectPalette`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet LogPalette (section 2.2.17) dans la table d'objets EMF, soit la valeur DEFAULT\_PALETTE, qui est l'index d'une palette d'objet stockée de l'énumération StockObject (section 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet LogPalette (section 2.2.17) dans la table d'objets EMF, soit la valeur DEFAULT\_PALETTE, qui est l'index d'une palette d'objet stockée de l'énumération StockObject (section 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSelectPalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet LogPalette (section 2.2.17) dans la table d'objets EMF, soit la valeur DEFAULT\_PALETTE, qui est l'index d'une palette d'objet stockée de l'énumération StockObject (section 2.1.31).

Cette valeur NE DOIT PAS être zéro ou l'index de tout autre objet stock.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie soit l'index d'un objet LogPalette (section 2.2.17) dans la table d'objets EMF, soit la valeur DEFAULT\_PALETTE, qui est l'index d'une palette d'objet stockée de l'énumération StockObject (section 2.1.31).

Cette valeur NE DOIT PAS être zéro ou l'index de tout autre objet stock.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

