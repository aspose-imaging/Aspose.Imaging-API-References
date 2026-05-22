---
title: "Classe EmfColorAdjustment"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | Initialise une nouvelle instance de la classe EmfColorAdjustment |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la n‑ième puissance pour le <br/>            bleu primaire des couleurs source. Cette valeur DOIT être dans la plage de 2 500 à 65 000. <br/>            Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| luminosité | int | r/w | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. <br/>            Cette valeur DOIT être dans la plage de –100 à 100.<br/>            Une valeur de zéro signifie que l'ajustement de la luminosité NE DOIT PAS être effectué. |
| colorfullness | int | r/w | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de saturation à appliquer à l'objet source. <br/>            Cette valeur DOIT être dans la plage de –100 à 100. <br/>            Une valeur de zéro signifie que l'ajustement de la saturation NE DOIT PAS être effectué |
| contraste | int | r/w | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. <br/>            Cette valeur DOIT être dans la plage de –100 à 100. Une valeur de zéro signifie que l'ajustement du contraste NE DOIT PAS être effectué. |
| green_gamma | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la n‑ième puissance pour le vert <br/>            primaire des couleurs source. Cette valeur DOIT être dans la plage de 2 500 à 65 000. <br/>            Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source lumineuse standard sous laquelle le <br/>            image est visualisée, à partir de l'énumération Illuminant (section 2.1.19). |
| red_gamma | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma à la n‑ième puissance pour le <br/>            rouge primaire des couleurs source. Cette valeur DOIT être dans la plage de 2 500 à 65 000.<br/>            Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| red_green_tint | int | r/w | Obtient ou définit un entier signé de 16 bits qui spécifie la quantité d'ajustement de teinte rouge ou verte à appliquer à l'objet source. Cette valeur DOIT être dans la plage de –100 à 100. <br/>            Les nombres positifs ajustent vers le rouge et les nombres négatifs ajustent vers le vert. <br/>            Une valeur de zéro signifie que l'ajustement de la teinte NE DOIT PAS être effectué |
| reference_black | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence noire pour les couleurs source. <br/>            Toutes les couleurs plus sombres que celle-ci sont traitées comme noires. <br/>            Cette valeur DOIT être dans la plage de zéro à 4 000 |
| reference_white | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la référence blanche pour les couleurs source. <br/>            Toutes les couleurs plus claires que celle-ci sont traitées comme blanches. <br/>            Cette valeur DOIT être dans la plage de 6 000 à 10 000. |
| size | int | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie la taille en octets de cet objet. Cette valeur DOIT être 0x0018. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Obtient ou définit un entier non signé de 16 bits qui spécifie comment préparer l'image de sortie. Ce champ peut être <br/>            défini sur NULL ou sur toute combinaison de valeurs de l'énumération ColorAdjustment (section 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

Initialise une nouvelle instance de la classe EmfColorAdjustment

