---
title: "EmfCommentPublicRecordType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les types d'enregistrement EMR_COMMENT_PUBLIC spécifient des extensions au traitement EMF."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

Les types d'enregistrements EMR\_COMMENT\_PUBLIC spécifient des extensions du traitement EMF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme spécifiant des données publiques. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme spécifiant des données publiques. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement de commentaire public. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement de commentaire public. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme spécifiant des données publiques. La valeur 0x43494447, qui est la chaîne ASCII "CIDG", identifie ceci comme un enregistrement EMR\_COMMENT\_PUBLIC.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtient ou définit un entier non signé de 32 bits qui identifie cet enregistrement de commentaire comme spécifiant des données publiques. La valeur 0x43494447, qui est la chaîne ASCII "CIDG", identifie ceci comme un enregistrement EMR\_COMMENT\_PUBLIC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement de commentaire public. Cette valeur DOIT être l'une des valeurs listées dans le tableau précédent, qui sont spécifiées dans l'énumération EmrComment (section 2.1.10), sauf si des types d'enregistrements de commentaires publics supplémentaires ont été implémentés sur le serveur d'impression.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Obtient ou définit un entier non signé de 32 bits qui identifie le type d'enregistrement de commentaire public. Cette valeur DOIT être l'une des valeurs listées dans le tableau précédent, qui sont spécifiées dans l'énumération EmrComment (section 2.1.10), sauf si des types d'enregistrements de commentaires publics supplémentaires ont été implémentés sur le serveur d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

