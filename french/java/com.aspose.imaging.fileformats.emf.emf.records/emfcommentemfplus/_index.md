---
title: "EmfCommentEmfPlus"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT_EMFPLUS contient des enregistrements EMF intégrés."
type: docs
weight: 27
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

L'enregistrement EMR\_COMMENT\_EMFPLUS contient des enregistrements EMF+ intégrés. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCommentEmfPlus`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMF+. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMF+. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Obtient ou définit un tableau d'octets qui contient un ou plusieurs enregistrements EMF+ ([MS-EMFPLUS] section 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Obtient ou définit un tableau d'octets qui contient un ou plusieurs enregistrements EMF+ ([MS-EMFPLUS] section 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCommentEmfPlus`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMF+ . La valeur 0x2B464D45, qui est la chaîne ASCII "+FME", identifie ceci comme un enregistrement EMR\_COMMENT\_EMFPLUS.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme contenant des enregistrements EMF+ . La valeur 0x2B464D45, qui est la chaîne ASCII "+FME", identifie ceci comme un enregistrement EMR\_COMMENT\_EMFPLUS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Obtient ou définit un tableau d'octets qui contient un ou plusieurs enregistrements EMF+ ([MS-EMFPLUS] section 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Obtient ou définit un tableau d'octets qui contient un ou plusieurs enregistrements EMF+ ([MS-EMFPLUS] section 2.3.1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

