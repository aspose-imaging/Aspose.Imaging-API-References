---
title: "EmfPlusTextureBrushOptionalData Class"
type: docs
weight: 690
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Initierar en ny instans av EmfPlusTextureBrushOptionalData-klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Hämtar eller anger ett valfritt EmfPlusImage-objekt (sektion 2.2.1.4) som specificerar<br/>            borsttexturen. Detta fält MÅSTE vara närvarande om storleken på <br/>            EmfPlusObject-posten (sektion 2.3.5.1) som definierar denna textur<br/>            borst är tillräckligt stor för att rymma ett EmfPlusImage-objekt <br/>            utöver de obligatoriska fälten i EmfPlusTextureBrushData-objektet <br/>            och eventuellt ett EmfPlusTransformMatrix-objekt. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (sektion 2.2.2.47) <br/>            som specificerar en transform från världsrummet till enhetsrummet för<br/>            texturborsten. Detta fält MÅSTE vara närvarande om BrushDataTransform-<br/>            flaggan är satt i BrushDataFlags-fältet i EmfPlusTextureBrushData-objektet. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Initierar en ny instans av EmfPlusTextureBrushOptionalData-klassen.

