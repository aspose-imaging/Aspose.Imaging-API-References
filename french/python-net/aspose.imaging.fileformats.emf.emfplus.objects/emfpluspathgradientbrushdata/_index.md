---
title: "EmfPlusPathGradientBrushData Classe"
type: docs
weight: 500
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Initialise une nouvelle instance de la classe EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Obtient ou définit la frontière du pinceau à dégradé de chemin, qui est spécifiée soit par un chemin, soit par un spline cardinal fermé. <br/>            Si le drapeau BrushDataPath est défini dans le champ BrushDataFlags, ce champ DOIT contenir un objet EmfPlusBoundaryPathData (section 2.2.2.6) ; <br/>            sinon, ce champ DOIT contenir un objet EmfPlusBoundaryPointData (section 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData.<br/>            Cette valeur DOIT être composée des drapeaux BrushData (section 2.1.2.1). Les drapeaux suivants sont pertinents pour un pinceau à dégradé de chemin : |
| center_argb_32_color | int | r/w | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du <br/>            pinceau à dégradé de chemin, qui est la couleur qui apparaît au point central du pinceau. <br/>            La couleur du pinceau change progressivement de la couleur de la frontière <br/>            à la couleur centrale au fur et à mesure qu'elle se déplace de la frontière vers le point central. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit l'objet EmfPlusARGB (section 2.2.2.1) qui spécifie la couleur centrale du pinceau à dégradé de chemin, <br/>            qui est la couleur qui apparaît au point central du pinceau. La couleur du<br/>            pinceau change progressivement de la couleur de la frontière à la couleur centrale à mesure qu'elle se déplace<br/>            de la frontière vers le point central. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Obtient ou définit un objet optionnel EmfPlusPathGradientBrushOptionalData (section 2.2.2.30) qui <br/>            spécifie des données supplémentaires pour le pinceau à dégradé de chemin. <br/>            Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags. |
| surrounding_argb_32_colors | int[] | r/w | Obtient ou définit un tableau de SurroundingColorCount objets EmfPlusARGB <br/>            qui spécifient les couleurs pour des points discrets sur la frontière du pinceau. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie<br/>            s'il faut peindre la zone en dehors de la frontière du pinceau. Lors du dessin <br/>            en dehors de la frontière, le mode d'enroulement spécifie comment le dégradé de couleur est répété |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Initialise une nouvelle instance de la classe EmfPlusPathGradientBrushData

