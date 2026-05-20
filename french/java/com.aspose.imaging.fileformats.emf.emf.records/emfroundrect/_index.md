---
title: "EmfRoundRect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_ROUNDRECT spécifie un rectangle aux coins arrondis."
type: docs
weight: 111
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

L'enregistrement EMR\\_ROUNDRECT spécifie un rectangle aux coins arrondis. Le rectangle est contourné en utilisant le crayon actuel et rempli en utilisant le pinceau actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | Initialise une nouvelle instance de la classe [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBox()](#getBox--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner. |
| [getCorner()](#getCorner--) | Obtient ou définit un objet WMF SizeL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.22, qui indique la largeur et la hauteur, en coordonnées logiques, de l’ellipse utilisée pour dessiner les coins arrondis. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Obtient ou définit un objet WMF SizeL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.22, qui indique la largeur et la hauteur, en coordonnées logiques, de l’ellipse utilisée pour dessiner les coins arrondis. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfRoundRect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Initialise une nouvelle instance de la classe [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Obtient ou définit un objet WMF SizeL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.22, qui indique la largeur et la hauteur, en coordonnées logiques, de l’ellipse utilisée pour dessiner les coins arrondis.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Obtient ou définit un objet WMF SizeL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.22, qui indique la largeur et la hauteur, en coordonnées logiques, de l’ellipse utilisée pour dessiner les coins arrondis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

