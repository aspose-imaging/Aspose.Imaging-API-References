---
title: "EmfRectangle"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_RECTANGLE dessine un rectangle."
type: docs
weight: 107
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

L'enregistrement EMR\_RECTANGLE dessine un rectangle. Le rectangle est contourné en utilisant le crayon actuel et rempli en utilisant le pinceau actuel.

La position actuelle n'est ni utilisée ni mise à jour par Rectangle. Si un crayon PS\_NULL est utilisé, les dimensions du rectangle sont réduites de 1 pixel en hauteur et de 1 pixel en largeur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | Initialise une nouvelle instance de la classe `EmfRectangle`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBox()](#getBox--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle inclusif-inclusif à dessiner. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfRectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Initialise une nouvelle instance de la classe `EmfRectangle`.

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

