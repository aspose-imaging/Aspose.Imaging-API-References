---
title: "EmfRecord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de base pour les enregistrements EMF Tous les enregistrements EMF DOIVENT avoir une longueur qui est un multiple de 4 octets."
type: docs
weight: 106
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Classe de base pour les enregistrements EMF. Tous les enregistrements EMF DOIVENT avoir une longueur qui est un multiple de 4 octets. Cela est illustré dans les structures génériques des types d’enregistrements EMF précédents en incluant des champs AlignmentPadding le cas échéant à la fin de ces structures. Le contenu des champs AlignmentPadding DOIT toujours être ignoré. Par souci de concision, ces champs ne sont pas affichés dans chaque définition d’enregistrement EMF individuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Initialise une nouvelle instance de la classe `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | Initialise une nouvelle instance de la classe `EmfRecord`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient le type. |
| [setType(int value)](#setType-int-) | Définit le type. |
| [getSize()](#getSize--) | Obtient la taille de l’enregistrement |
| [setSize(int value)](#setSize-int-) | Définit la taille de l’enregistrement |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Initialise une nouvelle instance de la classe `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfRecord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Initialise une nouvelle instance de la classe `EmfRecord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type d’enregistrement. |

### getType() {#getType--}
```
public int getType()
```


Obtient le type.

**Returns:**
int - Le type.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Définit le type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le type. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtient la taille de l’enregistrement

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Définit la taille de l’enregistrement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

