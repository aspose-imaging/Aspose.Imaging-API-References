---
title: "EmfIntersectClipRect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_INTERSECTCLIPRECT spécifie une nouvelle région de découpage à partir de l’intersection de la région de découpage actuelle et du rectangle spécifié."
type: docs
weight: 66
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

L’enregistrement EMR\_INTERSECTCLIPRECT spécifie une nouvelle région de découpage à partir de l’intersection de la région de découpage actuelle et du rectangle spécifié. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfIntersectClipRect`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getClip()](#getClip--) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle en unités logiques. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle en unités logiques. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfIntersectClipRect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle en unités logiques.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

