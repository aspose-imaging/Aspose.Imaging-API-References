---
title: "EmfColorCorrectPalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COLORCORRECTPALETTE spécifie comment corriger les entrées d'un objet palette logique en utilisant les valeurs WCS 1.0."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

L'enregistrement EMR\_COLORCORRECTPALETTE spécifie comment corriger les entrées d'un objet palette logique en utilisant les valeurs WCS 1.0.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfColorCorrectPalette`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Obtient un entier non signé de 32 bits qui spécifie l'index d'un objet palette logique (section 2.2.17) dans la table d'objets EMF (section 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Définit un entier non signé de 32 bits qui spécifie l'index d'un objet palette logique (section 2.2.17) dans la table d'objets EMF (section 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Obtient un entier non signé de 32 bits qui spécifie l'index de la première entrée à corriger. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à corriger. |
| [getNPalEntries()](#getNPalEntries--) | Obtient un entier non signé de 32 bits qui spécifie le nombre d'entrées de palette à corriger. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Définit un entier non signé de 32 bits qui spécifie le nombre d'entrées de palette à corriger. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfColorCorrectPalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Obtient un entier non signé de 32 bits qui spécifie l'index d'un objet palette logique (section 2.2.17) dans la table d'objets EMF (section 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Définit un entier non signé de 32 bits qui spécifie l'index d'un objet palette logique (section 2.2.17) dans la table d'objets EMF (section 3.1.1.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Obtient un entier non signé de 32 bits qui spécifie l'index de la première entrée à corriger.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Définit un entier non signé de 32 bits qui spécifie l'index de la première entrée à corriger.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Obtient un entier non signé de 32 bits qui spécifie le nombre d'entrées de palette à corriger.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Définit un entier non signé de 32 bits qui spécifie le nombre d'entrées de palette à corriger.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

