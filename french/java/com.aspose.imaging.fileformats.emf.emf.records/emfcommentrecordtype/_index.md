---
title: "EmfCommentRecordType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les types d’enregistrements de commentaire définissent des formats permettant de spécifier des enregistrements d’insertion de données privées arbitraires dans d’autres formats de métafichier et d’ajouter de nouvelles commandes ou des commandes à usage spécial."
type: docs
weight: 32
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Les types d'enregistrements de commentaire définissent des formats pour spécifier des données privées arbitraires, intégrer des enregistrements dans d'autres formats de métafichier, et ajouter de nouvelles commandes ou des commandes à usage spécial.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDataSize()](#getDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit. |
| [setDataSize(int value)](#setDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit l'identifiant du commentaire. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit l'identifiant du commentaire. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit. Il NE DOIT PAS inclure la taille de lui‑même ni la taille du champ AlignmentPadding, le cas échéant.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, des champs CommentIdentifier et CommentRecordParm dans le champ RecordBuffer qui suit. Il NE DOIT PAS inclure la taille de lui‑même ni la taille du champ AlignmentPadding, le cas échéant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

