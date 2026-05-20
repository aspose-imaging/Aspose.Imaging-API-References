---
title: "EmfPlusSerializableObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSerializableObject définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données."
type: docs
weight: 53
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

L'enregistrement EmfPlusSerializableObject définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSerializableObject`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
| [setFlags(short value)](#setFlags-short-) | Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. |
| [getObjectGuid()](#getObjectGuid--) | Obtient ou définit la valeur de représentation du paquet GUID ([MS-DTYP] section 2.3.4.2) pour l'effet d'image. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Obtient ou définit la valeur de représentation du paquet GUID ([MS-DTYP] section 2.3.4.2) pour l'effet d'image. |
| [getBufferSize()](#getBufferSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets du champ Buffer aligné sur 32 bits. |
| [setBufferSize(int value)](#setBufferSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets du champ Buffer aligné sur 32 bits. |
| [getBuffer()](#getBuffer--) | Obtient ou définit un tableau de BufferSize octets contenant le bloc de paramètres d'effets d'image sérialisés qui correspond au GUID dans le champ ObjectGUID. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Obtient ou définit un tableau de BufferSize octets contenant le bloc de paramètres d'effets d'image sérialisés qui correspond au GUID dans le champ ObjectGUID. |
| [getImageEffect()](#getImageEffect--) | Obtient ou définit l'effet d'image. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Obtient ou définit l'effet d'image. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSerializableObject`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DEVRAIT être mis à zéro et DOIT être ignoré à la réception.

Valeur : les indicateurs.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Obtient ou définit un entier non signé de 16 bits qui n'est pas utilisé. Ce champ DEVRAIT être mis à zéro et DOIT être ignoré à la réception.

Valeur : les indicateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Obtient ou définit la valeur de représentation du paquet GUID ([MS-DTYP] section 2.3.4.2) pour l'effet d'image. Cela DOIT correspondre à l'un des identifiants ImageEffects (section 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Obtient ou définit la valeur de représentation du paquet GUID ([MS-DTYP] section 2.3.4.2) pour l'effet d'image. Cela DOIT correspondre à l'un des identifiants ImageEffects (section 2.1.3.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets du champ Buffer aligné sur 32 bits.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille en octets du champ Buffer aligné sur 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Obtient ou définit un tableau de BufferSize octets contenant le bloc de paramètres d'effets d'image sérialisés qui correspond au GUID dans le champ ObjectGUID. Cela DOIT être l'un des objets Image Effects (section 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Obtient ou définit un tableau de BufferSize octets contenant le bloc de paramètres d'effets d'image sérialisés qui correspond au GUID dans le champ ObjectGUID. Cela DOIT être l'un des objets Image Effects (section 2.2.3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Obtient ou définit l'effet d'image.

Valeur: l'effet d'image.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Obtient ou définit l'effet d'image.

Valeur: l'effet d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

