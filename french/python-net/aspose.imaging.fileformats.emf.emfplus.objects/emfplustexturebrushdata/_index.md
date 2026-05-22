---
title: "Classe EmfPlusTextureBrushData"
type: docs
weight: 680
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Initialise une nouvelle instance de la classe EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. <br/>            Cette valeur DOIT être composée des indicateurs BrushData (section 2.1.2.1). <br/>            Les indicateurs suivants sont pertinents pour un pinceau de texture<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Obtient ou définit un objet optionnel EmfPlusTextureBrushOptionalData (section 2.2.2.46) qui <br/>            spécifie des données supplémentaires pour le pinceau de texture. Le contenu spécifique de <br/>            ce champ est déterminé par la valeur du champ BrushDataFlags |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtient ou définit un entier signé de 32 bits provenant de l’énumération WrapMode (section 2.1.1.34) <br/>            qui spécifie comment répéter l’image de texture sur une forme, lorsque l’<br/>            image est plus petite que la zone à remplir. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Initialise une nouvelle instance de la classe EmfPlusTextureBrushData

