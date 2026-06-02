---
title: "EmfCommentEmfSpool"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT_EMFSPOOL contient des enregistrements EMFSPOOL intégrés."
type: docs
weight: 28
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

L'enregistrement EMR\_COMMENT\_EMFSPOOL contient des enregistrements EMFSPOOL intégrés. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Initialise une nouvelle instance de la classe `EmfCommentEmfSpool`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMFSPOOL. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMFSPOOL. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement EMR\_COMMENT\_EMFSPOOL. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement EMR\_COMMENT\_EMFSPOOL. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCommentEmfSpool`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Initialise une nouvelle instance de la classe `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMFSPOOL. La valeur 0x00000000 identifie cela comme un enregistrement EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMFSPOOL. La valeur 0x00000000 identifie cela comme un enregistrement EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Obtient ou définit un tableau d'octets de longueur variable qui contient un ou plusieurs enregistrements de définition de police EMFSPOOL ([MS-EMFSPOOL] section 2.2.3.3).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

