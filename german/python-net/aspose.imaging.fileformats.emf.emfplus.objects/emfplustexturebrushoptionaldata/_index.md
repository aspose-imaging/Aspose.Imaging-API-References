---
title: "EmfPlusTextureBrushOptionalData Klasse"
type: docs
weight: 690
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Initialisiert eine neue Instanz der EmfPlusTextureBrushOptionalData Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Liest oder setzt ein optionales EmfPlusImage-Objekt (Abschnitt 2.2.1.4), das die<br/>            Pinseltextur angibt. Dieses Feld MUSS vorhanden sein, wenn die Größe des <br/>            EmfPlusObject-Datensatzes (Abschnitt 2.3.5.1), der diesen Texturpinsel definiert, <br/>            groß genug ist, um ein EmfPlusImage-Objekt zusätzlich zu den erforderlichen Feldern des EmfPlusTextureBrushData-Objekts <br/>            und optional einem EmfPlusTransformMatrix-Objekt aufzunehmen. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47) <br/>            das eine Welt-zu-Geräte-Raum-Transformation für den<br/>            Texturpinsel angibt. Dieses Feld MUSS vorhanden sein, wenn das BrushDataTransform-<br/>            Flag im BrushDataFlags-Feld des EmfPlusTextureBrushData-Objekts gesetzt ist. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Initialisiert eine neue Instanz der EmfPlusTextureBrushOptionalData Klasse

