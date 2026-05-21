---
title: "EmfSetRop2"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETROP2 définit un mode d'opération raster binaire."
type: docs
weight: 137
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

L'enregistrement EMR\_SETROP2 définit un mode d'opération raster binaire.

Les modes de mélange d'opération raster binaire définissent comment combiner les couleurs source et destination lors du dessin avec le crayon actuel. Les modes de mélange sont des codes d'opération raster binaire, représentant toutes les fonctions booléennes possibles de deux variables, en utilisant les opérations binaires AND, OR et XOR (ou exclusif), ainsi que l'opération unaire NOT. Le mode de mélange est destiné uniquement aux appareils raster ; il n'est pas disponible pour les appareils vectoriels.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | Initialise une nouvelle instance de la classe `EmfSetRop2`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'opération raster et DOIT appartenir à l'énumération WMF Binary Raster Op ([MS-WMF] section 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'opération raster et DOIT appartenir à l'énumération WMF Binary Raster Op ([MS-WMF] section 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetRop2`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Initialise une nouvelle instance de la classe `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'opération raster et DOIT appartenir à l'énumération WMF Binary Raster Op ([MS-WMF] section 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'opération raster et DOIT appartenir à l'énumération WMF Binary Raster Op ([MS-WMF] section 2.1.1.2).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

