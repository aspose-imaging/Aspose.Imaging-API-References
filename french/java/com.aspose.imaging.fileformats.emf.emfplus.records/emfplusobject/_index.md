---
title: "EmfPlusObject"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusObject spécifie un objet à utiliser dans les opérations graphiques."
type: docs
weight: 42
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

L'enregistrement EmfPlusObject spécifie un objet à utiliser dans les opérations graphiques. La définition de l'objet peut s'étendre sur plusieurs enregistrements, ce qui est indiqué par la valeur du champ Flags.

L'enregistrement EmfPlusObject est générique ; il est utilisé pour tous les types d'objets. Les valeurs spécifiques à certains types d'objets sont contenues dans le champ ObjectData. Un modèle conceptuel de gestion des objets graphiques est décrit dans Managing Graphics Objects (section 3.1.2).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusObject`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isContinuable()](#isContinuable--) | Obtient ou définit une valeur indiquant si cette instance est continuable. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Obtient ou définit une valeur indiquant si cette instance est continuable. |
| [getObjectType()](#getObjectType--) | Obtient ou définit le type de l'objet. |
| [setObjectType(byte value)](#setObjectType-byte-) | Obtient ou définit le type de l'objet. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'identifiant de l'objet. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'identifiant de l'objet. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Obtient ou définit la taille totale de l'objet. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Obtient ou définit la taille totale de l'objet. |
| [getObjectData()](#getObjectData--) | Obtient ou définit un tableau d'octets contenant les données pour le type d'objet spécifié dans le champ Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Obtient ou définit un tableau d'octets contenant les données pour le type d'objet spécifié dans le champ Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusObject`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Obtient ou définit une valeur indiquant si cette instance est continuable. Indique que la définition de l'objet se poursuit dans l'enregistrement EmfPlusObject suivant. Ce drapeau n'est jamais défini dans l'enregistrement final qui définit l'objet.

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est continuable. Indique que la définition de l'objet se poursuit dans l'enregistrement EmfPlusObject suivant. Ce drapeau n'est jamais défini dans l'enregistrement final qui définit l'objet.

Valeur : `true` si cette instance est compressée ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Obtient ou définit le type de l'objet.

Valeur : le type de l'objet.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Obtient ou définit le type de l'objet.

Valeur : le type de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'identifiant de l'objet. L'index dans la table d'objets EMF+ à associer à l'objet créé par cet enregistrement. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'identifiant de l'objet. L'index dans la table d'objets EMF+ à associer à l'objet créé par cet enregistrement. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Obtient ou définit la taille totale de l'objet. Si l'enregistrement est continuable, lorsque le bit de continuation est activé, ce champ sera présent. Les objets continus possèdent plusieurs enregistrements EMF+ commençant par EmfPlusContineudObjectRecord. Chaque EmfPlusContinuedObjectRecord contiendra un TotalObjectSize. Une fois le nombre d'octets indiqué par TotalObjectSize lu, l'enregistrement EMF+ suivant ne sera plus considéré comme faisant partie de l'objet continu.

Valeur : la taille totale de l'objet.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Obtient ou définit la taille totale de l'objet. Si l'enregistrement est continuable, lorsque le bit de continuation est activé, ce champ sera présent. Les objets continus possèdent plusieurs enregistrements EMF+ commençant par EmfPlusContineudObjectRecord. Chaque EmfPlusContinuedObjectRecord contiendra un TotalObjectSize. Une fois le nombre d'octets indiqué par TotalObjectSize lu, l'enregistrement EMF+ suivant ne sera plus considéré comme faisant partie de l'objet continu.

Valeur : la taille totale de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Obtient ou définit un tableau d'octets contenant les données pour le type d'objet spécifié dans le champ Flags. Le contenu et le format des données peuvent varier selon chaque type d'objet. Consultez les définitions individuelles des objets dans la section 2.2.1 pour plus d'informations.

Valeur : les données de l'objet.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Obtient ou définit un tableau d'octets contenant les données pour le type d'objet spécifié dans le champ Flags. Le contenu et le format des données peuvent varier selon chaque type d'objet. Consultez les définitions individuelles des objets dans la section 2.2.1 pour plus d'informations.

Valeur : les données de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

