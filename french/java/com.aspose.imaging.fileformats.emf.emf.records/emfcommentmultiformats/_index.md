---
title: "EmfCommentMultiFormats"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COMMENT_MULTIFORMATS spécifie une image dans plusieurs formats graphiques."
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

L'enregistrement EMR\_COMMENT\_MULTIFORMATS spécifie une image dans plusieurs formats graphiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCommentMultiFormats`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie, en coordonnées logiques. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie, en coordonnées logiques. |
| [getAFormats()](#getAFormats--) | Obtient ou définit un tableau de longueur CountFormats de formats graphiques, spécifiés par des objets EmrFormat (section 2.2.4), par ordre de préférence. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Obtient ou définit un tableau de longueur CountFormats de formats graphiques, spécifiés par des objets EmrFormat (section 2.2.4), par ordre de préférence. |
| [getFormatData()](#getFormatData--) | Obtient ou définit un tableau d'octets de longueur variable contenant les données d'image pour tous les formats graphiques présents dans cet enregistrement. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Obtient ou définit un tableau d'octets de longueur variable contenant les données d'image pour tous les formats graphiques présents dans cet enregistrement. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCommentMultiFormats`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie, en coordonnées logiques.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de sortie, en coordonnées logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Obtient ou définit un tableau de longueur CountFormats de formats graphiques, spécifiés par des objets EmrFormat (section 2.2.4), par ordre de préférence.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Obtient ou définit un tableau de longueur CountFormats de formats graphiques, spécifiés par des objets EmrFormat (section 2.2.4), par ordre de préférence.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Obtient ou définit un tableau d'octets de longueur variable contenant les données d'image pour tous les formats graphiques présents dans cet enregistrement. La taille des données pour chaque image est fournie par le champ DataSize de l'objet EmrFormat correspondant. Ainsi, la taille totale de ce champ est la somme des valeurs DataSize de tous les objets EmrFormat. Le format graphique des données pour chaque image est spécifié par le champ Signature de l'objet EmrFormat correspondant.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Obtient ou définit un tableau d'octets de longueur variable contenant les données d'image pour tous les formats graphiques présents dans cet enregistrement. La taille des données pour chaque image est fournie par le champ DataSize de l'objet EmrFormat correspondant. Ainsi, la taille totale de ce champ est la somme des valeurs DataSize de tous les objets EmrFormat. Le format graphique des données pour chaque image est spécifié par le champ Signature de l'objet EmrFormat correspondant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[][] |  |

