---
title: "Classe EmfPlusCustomLineCapData"
type: docs
weight: 270
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Initialise une nouvelle instance de la classe EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur de l'énumération LineCap (section 2.1.1.18) <br/>            sur laquelle le cap de ligne personnalisé est basé. |
| base_inset | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie la distance entre le début <br/>            du cap de ligne et la fin de la ligne. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini à {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Obtient ou définit un objet optionnel EmfPlusCustomLineCapOptionalData (section 2.2.2.14)<br/>             qui spécifie des données supplémentaires pour le cap de ligne graphique personnalisé. L<br/>            e contenus spécifiques de ce champ sont déterminés <br/>            par la valeur du champ CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap qui indique quel <br/>            cap de ligne doit être utilisé à la fin de la ligne à tracer. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit un objet EmfPlusPointF qui n'est pas actuellement utilisé. Il DOIT être défini à {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineJoin <br/>            (section 2.1.1.19), qui indique comment joindre deux lignes tracées par<br/>             le même stylo et dont les extrémités se rencontrent. À l'intersection des deux extrémités de ligne, <br/>            une jointure de ligne rend la connexion plus continue. |
| stroke_miter_limit | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui contient la limite de l'épaisseur<br/>             de la jointure sur un coin en onglet en définissant le rapport maximal autorisé<br/>             entre la longueur de l'onglet et la largeur de la ligne. |
| stroke_start_cap | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la valeur dans l'énumération LineCap qui indique le <br/>            cap de ligne utilisé au début de la ligne à tracer |
| width_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur par lequel <br/>             mettre à l'échelle le cap de ligne personnalisé par rapport à la largeur du stylo EmfPlusPen <br/>            (section 2.2.1.7) utilisé pour tracer les lignes. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Initialise une nouvelle instance de la classe EmfPlusCustomLineCapData

