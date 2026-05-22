---
title: "EmfPlusTextureBrushOptionalData Classe"
type: docs
weight: 690
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Initialise une nouvelle instance de la classe EmfPlusTextureBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Obtient ou définit un objet EmfPlusImage optionnel (section 2.2.1.4) qui spécifie la<br/>            texture du pinceau. Ce champ DOIT être présent si la taille du <br/>            enregistrement EmfPlusObject (section 2.3.5.1) qui définit ce pinceau de texture <br/>            est suffisamment grande pour contenir un objet EmfPlusImage en <br/>            plus des champs obligatoires de l'objet EmfPlusTextureBrushData <br/>            et éventuellement d'un objet EmfPlusTransformMatrix. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) <br/>            qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le<br/>             pinceau de texture. Ce champ DOIT être présent si le drapeau BrushDataTransform <br/>            est défini dans le champ BrushDataFlags de l'objet EmfPlusTextureBrushData. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Initialise une nouvelle instance de la classe EmfPlusTextureBrushOptionalData

