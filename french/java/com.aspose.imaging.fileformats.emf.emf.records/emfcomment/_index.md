---
title: "EmfComment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT contient des données privées arbitraires."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

L'enregistrement EMR\_COMMENT contient des données privées arbitraires. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfComment`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Obtient ou définit un tableau d'octets optionnel qui spécifie les données privées. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Obtient ou définit un tableau d'octets optionnel qui spécifie les données privées. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit l'identifiant du commentaire. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit l'identifiant du commentaire. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfComment`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Obtient ou définit un tableau d'octets optionnel qui spécifie les données privées. Le premier DWORD de ces données NE DOIT PAS être l'une des valeurs d'identifiant de commentaire prédéfinies spécifiées dans la section 2.3.3. Les données privées sont inconnues de l'EMF ; elles ne sont significatives que pour les applications qui connaissent le format des données et la façon de les utiliser. Les enregistrements de données privées EMR\_COMMENT PEUVENT être ignorés.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Obtient ou définit un tableau d'octets optionnel qui spécifie les données privées. Le premier DWORD de ces données NE DOIT PAS être l'une des valeurs d'identifiant de commentaire prédéfinies spécifiées dans la section 2.3.3. Les données privées sont inconnues de l'EMF ; elles ne sont significatives que pour les applications qui connaissent le format des données et la façon de les utiliser. Les enregistrements de données privées EMR\_COMMENT PEUVENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtient ou définit l'identifiant du commentaire.

Valeur : l'identifiant du commentaire.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtient ou définit l'identifiant du commentaire.

Valeur : l'identifiant du commentaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

