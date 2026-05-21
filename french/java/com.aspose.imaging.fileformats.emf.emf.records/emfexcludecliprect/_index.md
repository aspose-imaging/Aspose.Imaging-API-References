---
title: "EmfExcludeClipRect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EXCLUDECLIPRECT spécifie une nouvelle région de découpage qui consiste en la région de découpage existante moins le rectangle spécifié."
type: docs
weight: 50
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

L'enregistrement EMR\_EXCLUDECLIPRECT spécifie une nouvelle région de découpage qui consiste en la région de découpage existante moins le rectangle spécifié. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Initialise une nouvelle instance de la classe `EmfExcludeClipRect`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getClip()](#getClip--) | Obtient un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de découpage en unités logiques. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de découpage en unités logiques. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfExcludeClipRect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Initialise une nouvelle instance de la classe `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Obtient un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de découpage en unités logiques.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie le rectangle de découpage en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

