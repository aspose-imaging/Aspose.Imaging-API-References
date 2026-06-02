---
title: "EmfSetBrushOrgEx"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETBRUSHORGEX spécifie l'origine du pinceau actuel."
type: docs
weight: 121
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBrushOrgEx extends EmfStateRecordType
```

L'enregistrement EMR\_SETBRUSHORGEX spécifie l'origine du pinceau actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetBrushOrgEx(EmfRecord source)](#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetBrushOrgEx`. |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx--) | Initialise une nouvelle instance de la classe `EmfSetBrushOrgEx`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOrigin()](#getOrigin--) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique l'origine horizontale et verticale du pinceau en unités de dispositif. |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique l'origine horizontale et verticale du pinceau en unités de dispositif. |
### EmfSetBrushOrgEx(EmfRecord source) {#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBrushOrgEx(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetBrushOrgEx`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetBrushOrgEx() {#EmfSetBrushOrgEx--}
```
public EmfSetBrushOrgEx()
```


Initialise une nouvelle instance de la classe `EmfSetBrushOrgEx`.

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique l'origine horizontale et verticale du pinceau en unités de dispositif.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


Obtient ou définit un objet WMF PointL 64 bits, spécifié dans la section 2.2.2.15 de [MS-WMF], qui indique l'origine horizontale et verticale du pinceau en unités de dispositif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

