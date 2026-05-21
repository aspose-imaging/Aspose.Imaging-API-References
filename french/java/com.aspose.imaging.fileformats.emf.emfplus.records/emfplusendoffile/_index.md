---
title: "EmfPlusEndOfFile"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusEndOfFile spécifie la fin des données EMF dans le métafichier."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusEndOfFile extends EmfPlusControlRecordType
```

L'enregistrement EmfPlusEndOfFile spécifie la fin des données EMF+ dans le métafichier.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusEndOfFile(EmfPlusRecord source)](#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusEndOfFile`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
| [setFlags(short value)](#setFlags-short-) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
### EmfPlusEndOfFile(EmfPlusRecord source) {#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndOfFile(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusEndOfFile`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DOIT être mis à zéro et DOIT être ignoré à la réception.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DOIT être mis à zéro et DOIT être ignoré à la réception.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

