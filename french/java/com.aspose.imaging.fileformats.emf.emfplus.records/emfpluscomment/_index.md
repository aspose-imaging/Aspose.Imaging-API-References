---
title: "EmfPlusComment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusComment spécifie des données privées arbitraires."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

L'enregistrement EmfPlusComment spécifie des données privées arbitraires.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusComment`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Obtient ou définit un tableau d'octets de longueur DataSize contenant des données privées. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Obtient ou définit un tableau d'octets de longueur DataSize contenant des données privées. |
| [getFlags()](#getFlags--) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
| [setFlags(short value)](#setFlags-short-) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusComment`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Obtient ou définit un tableau d'octets de longueur DataSize contenant des données privées. octets de données spécifiques à l'enregistrement qui suivent.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Obtient ou définit un tableau d'octets de longueur DataSize contenant des données privées. octets de données spécifiques à l'enregistrement qui suivent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

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

