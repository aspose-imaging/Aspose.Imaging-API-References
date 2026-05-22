---
title: "EmfPlusCustomLineCapOptionalData Classe"
type: docs
weight: 280
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---

**Summary:** The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData__1) | Initialise une nouvelle instance de la classe EmfPlusCustomLineCapOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_data | [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath/) | r/w | Obtient ou définit l'objet optionnel EmfPlusFillPath (section 2.2.2.17) qui spécifie le chemin de remplissage d'un cap de ligne graphique personnalisé<br/>            . Ce champ DOIT être présent si le drapeau CustomLineCapDataFillPath est défini dans les CustomLineCapDataFlags<br/>            du champ de l'objet EmfPlusCustomLineCapData. |
| outline_data | [EmfPlusLinePath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath/) | r/w | Obtient ou définit l'objet optionnel EmfPlusLinePath (section 2.2.2.26) <br/>            qui spécifie le chemin de contour d'un cap de ligne graphique personnalisé. Ce champ DOIT être présent si le drapeau CustomLineCapDataLinePath est défini dans les CustomLineCapDataFlags <br/>            du champ de l'objet EmfPlusCustomLineCapData. |


### Constructor: EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData__1}


```
 EmfPlusCustomLineCapOptionalData() 
```

Initialise une nouvelle instance de la classe EmfPlusCustomLineCapOptionalData

