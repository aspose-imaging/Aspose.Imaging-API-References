---
title: "EmfSetPaletteEntries"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETPALETTEENTRIES définit des valeurs de couleur RVB dans une plage d'entrées pour un objet LogPalette existant de la section 2.2.17."
type: docs
weight: 134
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_SETPALETTEENTRIES définit les valeurs de couleur RVB dans une plage d'entrées pour un objet LogPalette existant (section 2.2.17).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetPaletteEntries`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF de la palette. |
| [setIhPal(int value)](#setIhPal-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF de la palette. |
| [getStart()](#getStart--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à définir. |
| [setStart(int value)](#setStart-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à définir. |
| [getNumberofEntries()](#getNumberofEntries--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Obtient ou définit un tableau d'objets LogPaletteEntry (section 2.2.18), d'une longueur NumberOfEntries, qui spécifie les données des entrées de la palette. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Obtient ou définit un tableau d'objets LogPaletteEntry (section 2.2.18), d'une longueur NumberOfEntries, qui spécifie les données des entrées de la palette. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetPaletteEntries`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF de la palette.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF de la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à définir.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à définir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'entrées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Obtient ou définit un tableau d'objets LogPaletteEntry (section 2.2.18), d'une longueur NumberOfEntries, qui spécifie les données des entrées de la palette. Les membres Values ne contiennent aucune valeur.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Obtient ou définit un tableau d'objets LogPaletteEntry (section 2.2.18), d'une longueur NumberOfEntries, qui spécifie les données des entrées de la palette. Les membres Values ne contiennent aucune valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

