---
title: "Classe EmfPlusPenData"
type: docs
weight: 550
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Initialise une nouvelle instance de la classe EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Obtient ou définit un objet optionnel EmfPlusPenOptionalData (section 2.2.2.34) <br/>            qui spécifie des données supplémentaires pour l'objet stylo. Le contenu <br/>            spécifique de ce champ est déterminé par la valeur du champ <br/>            PenDataFlags. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ <br/>            OptionalData. Cette valeur DOIT être composée des indicateurs PenData <br/>            (section 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie les unités de mesure <br/>            du stylo. La valeur DOIT provenir de l'énumération UnitType <br/>            (section 2.1.1.33). |
| pen_width | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie la largeur de la <br/>            ligne tracée par le stylo dans les unités spécifiées par le champ PenUnit <br/>            . Si une largeur de zéro est spécifiée, une valeur minimale est utilisée, <br/>            qui est déterminée par les unités. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Initialise une nouvelle instance de la classe EmfPlusPenData

