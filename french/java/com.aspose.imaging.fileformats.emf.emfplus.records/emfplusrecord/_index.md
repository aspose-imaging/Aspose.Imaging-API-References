---
title: "EmfPlusRecord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type d'enregistrement de base Emf."
type: docs
weight: 46
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Le type d'enregistrement de base Emf+.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Initialise une nouvelle instance de la classe `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusRecord`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| [getFlags()](#getFlags--) | Obtient un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [setFlags(short value)](#setFlags-short-) | Définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [getSize()](#getSize--) | Obtient un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [setSize(int value)](#setSize-int-) | Définit un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [getDataSize()](#getDataSize--) | Obtient un entier non signé de 32 bits qui DOIT définir le nombre d'octets de données 32-bit\u2013aligned du champ RecordData qui suit. |
| [setDataSize(int value)](#setDataSize-int-) | Définit un entier non signé de 32 bits qui DOIT définir le nombre d'octets de données 32-bit\u2013aligned du champ RecordData qui suit. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Initialise une nouvelle instance de la classe `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusRecord`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getType() {#getType--}
```
public short getType()
```


Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtient un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement.

**Returns:**
short - Les drapeaux.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short | Les indicateurs. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtient un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement.

**Returns:**
int - La taille.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Définit un entier non signé de 32 bits qui spécifie le nombre d'octets alignés sur 32 bits de l'enregistrement complet, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La taille. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtient un entier non signé de 32 bits qui DOIT définir le nombre d'octets de données alignés sur 32-bit\\u2013 dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets.

**Returns:**
int - La taille des données.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Définit un entier non signé de 32 bits qui DOIT définir le nombre d'octets de données alignés sur 32-bit\\u2013 dans le champ RecordData qui suit. Ce nombre n'inclut pas l'en-tête d'enregistrement de 12 octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La taille des données. |

