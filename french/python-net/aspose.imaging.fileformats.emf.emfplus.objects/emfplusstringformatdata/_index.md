---
title: "Classe EmfPlusStringFormatData"
type: docs
weight: 660
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | Initialise une nouvelle instance de la classe EmfPlusStringFormatData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | Obtient ou définit un tableau optionnel de RangeCount EmfPlusCharacterRange <br/>            objets qui spécifient la plage de positions de caractères <br/>            au sein d'une chaîne de texte. La région de délimitation est définie<br/>            par la zone d'affichage occupée par un groupe <br/>            de caractères spécifiés par la plage de caractères.<br/>            Ce champ DOIT être présent si la valeur du champ RangeCount<br/>            dans l'objet EmfPlusStringFormat est supérieure à 0. |
| tab_stops | float[] | r/w | Obtient ou définit un tableau optionnel de valeurs à virgule flottante qui spécifient <br/>            les emplacements optionnels des tabulations pour cet objet. Chaque valeur de tabulation <br/>            représente le nombre d'espaces entre les tabulations ou, pour la première tabulation, le nombre d'espaces <br/>            entre le début d'une ligne de texte et la première tabulation. <br/>            Ce champ DOIT être présent si la valeur du champ TabStopCount <br/>            dans l'objet EmpPlusStringFormat est supérieure à 0. |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

Initialise une nouvelle instance de la classe EmfPlusStringFormatData

