---
title: "EmfPolyBezier"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_POLYBEZIER spécifie une ou plusieurs courbes de Bézier."
type: docs
weight: 85
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

L'enregistrement EMR\_POLYBEZIER spécifie une ou plusieurs courbes de Bézier.

Les courbes de Bézier cubiques sont définies à l'aide des points d'extrémité et des points de contrôle spécifiés par le champ aPoints. La première courbe est tracée du premier point au quatrième point, en utilisant le deuxième et le troisième points comme points de contrôle. Chaque courbe suivante dans la séquence nécessite exactement trois points supplémentaires : le point final de la courbe précédente est utilisé comme point de départ, les deux points suivants de la séquence sont des points de contrôle, et le troisième est le point final. Les courbes de Bézier cubiques DOIVENT être tracées à l'aide du stylo actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Initialise une nouvelle instance de la classe `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPolyBezier`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Initialise une nouvelle instance de la classe `EmfPolyBezier`.

