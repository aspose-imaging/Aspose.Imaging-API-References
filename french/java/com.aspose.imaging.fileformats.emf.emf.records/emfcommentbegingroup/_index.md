---
title: "EmfCommentBeginGroup"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT_BEGINGROUP spécifie le début d'un groupe d'enregistrements de dessin."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

L'enregistrement EMR\_COMMENT\_BEGINGROUP spécifie le début d'un groupe d'enregistrements de dessin.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCommentBeginGroup`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie en coordonnées logiques. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie en coordonnées logiques. |
| [getNDescription()](#getNDescription--) | Obtient ou définit le nombre de caractères Unicode dans la chaîne de description optionnelle qui suit. |
| [setNDescription(int value)](#setNDescription-int-) | Obtient ou définit le nombre de caractères Unicode dans la chaîne de description optionnelle qui suit. |
| [getDescription()](#getDescription--) | Obtient ou définit une chaîne Unicode optionnelle terminée par un caractère nul qui décrit ce groupe d'enregistrements. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Obtient ou définit une chaîne Unicode optionnelle terminée par un caractère nul qui décrit ce groupe d'enregistrements. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCommentBeginGroup`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie en coordonnées logiques.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie en coordonnées logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Obtient ou définit le nombre de caractères Unicode dans la chaîne de description optionnelle qui suit.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Obtient ou définit le nombre de caractères Unicode dans la chaîne de description optionnelle qui suit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtient ou définit une chaîne Unicode optionnelle terminée par un caractère nul qui décrit ce groupe d'enregistrements.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Obtient ou définit une chaîne Unicode optionnelle terminée par un caractère nul qui décrit ce groupe d'enregistrements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

