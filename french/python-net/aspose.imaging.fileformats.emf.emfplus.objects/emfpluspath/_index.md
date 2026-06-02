---
title: "Classe EmfPlusPath"
type: docs
weight: 490
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Initialise une nouvelle instance de la classe EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Obtient ou définit le nombre de points du chemin <br/>            Un entier non signé de 32 bits qui spécifie comment interpréter les points et les types de points associés définis par cet objet |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. <br/>            Le type des objets dans ce tableau est indiqué par le drapeau R dans le champ PathPointFlags |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit un tableau de points de chemin<br/>            Un tableau de PathPointCount points qui spécifient le chemin. Le type des objets dans ce tableau est indiqué par le champ PathPointFlags, comme suit :<br/>            Si le drapeau P est activé, les points sont des positions relatives spécifiées par des objets EmfPlusPointR (section 2.2.2.37).<br/>            Si le drapeau P est désactivé et que le drapeau C est activé, les points sont des positions absolues spécifiées par des objets EmfPlusPoint (section 2.2.2.35).<br/>            Si le drapeau P est désactivé et que le drapeau C est désactivé, les points sont des positions absolues spécifiées par des objets EmfPlusPointF (section 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtient ou définit la version. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Initialise une nouvelle instance de la classe EmfPlusPath

