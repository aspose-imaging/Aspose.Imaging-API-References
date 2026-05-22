---
title: "Classe EmfPlusPenOptionalData"
type: docs
weight: 560
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Initialise une nouvelle instance de la classe EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Obtient ou définit l'objet optionnel EmfPlusCompoundLineData (section 2.2.2.9) <br/> qui spécifie un tableau de valeurs à virgule flottante définissant <br/> la ligne composée d'un crayon, constituée de lignes parallèles <br/> et d'espaces. Ce champ DOIT être présent si le <br/> drapeau PenDataCompoundLine est défini dans le champ PenDataFlags <br/> de l'objet EmfPlusPenData |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Obtient ou définit l'objet optionnel EmfPlusCustomEndCapData (section 2.2.2.11) <br/> qui définit la forme du cap d'extrémité personnalisé, c'est‑à‑dire la forme à <br/> utiliser à la fin d'une ligne tracée avec ce stylo. Elle peut être l'une des <br/> diverses formes, telles qu'un carré, un cercle ou un losange. Ce <br/> champ DOIT être présent si le drapeau PenDataCustomEndCap est <br/> défini dans le champ PenDataFlags de l'objet EmfPlusPenData |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Obtient ou définit l'objet optionnel EmfPlusCustomStartCapData (section 2.2.2.15) <br/> qui définit la forme du cap de départ personnalisé, c'est‑à‑dire la forme à <br/> utiliser au début d'une ligne tracée avec ce stylo. Elle peut être l'une des <br/> diverses formes, telles qu'un carré, un cercle ou un losange. <br/> Ce champ DOIT être présent si le drapeau PenDataCustomStartCap est <br/> défini dans le champ PenDataFlags de l'objet EmfPlusPenData |
| dash_offset | float | r/w | Obtient ou définit la valeur flottante optionnelle de 32 bits qui spécifie la <br/> distance du début d'une ligne au début du <br/> premier espace dans un motif de ligne pointillée. Ce champ DOIT être <br/> présent si le drapeau PenDataDashedLineOffset est défini dans le <br/> champ PenDataFlags de l'objet EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Obtient ou définit l'entier signé optionnel de 32 bits qui spécifie la forme pour <br/> les deux extrémités de chaque tiret dans une ligne pointillée. Ce champ DOIT être <br/> présent si le drapeau PenDataDashedLineCap est défini dans le <br/> champ PenDataFlags de l'objet EmfPlusPenData, et la <br/> valeur DOIT être définie dans l'énumération DashedLineCapType <br/> (section 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Obtient ou définit l'objet optionnel EmfPlusDashedLineData (section 2.2.2.16) <br/> qui spécifie les longueurs des tirets et des espaces dans une ligne pointillée personnalisée. Ce champ DOIT être présent si le drapeau PenDataDashedLine <br/> est défini dans le champ PenDataFlags de l'objet EmfPlusPenData<br/> . |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtient ou définit l'entier signé optionnel de 32 bits qui spécifie la forme<br/> pour l'extrémité d'une ligne dans le champ CustomEndCapData. Ce <br/> champ DOIT être présent si le drapeau PenDataEndCap est défini dans le <br/> champ PenDataFlags de l'objet EmfPlusPenData, et la valeur <br/> DOIT être définie dans l'énumération LineCapType |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Obtient ou définit un entier signé optionnel de 32 bits qui spécifie comment joindre<br/> deux lignes tracées par le même stylo et dont les extrémités se rencontrent. <br/> Ce champ DOIT être présent si le drapeau PenDataJoin est défini dans le <br/> champ PenDataFlags de l'objet EmfPlusPenData, et la <br/> valeur DOIT être définie dans l'énumération LineJoinType <br/> (section 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Obtient ou définit l'entier signé optionnel de 32 bits qui spécifie le style <br/> utilisé pour les lignes tracées avec cet objet stylo. Ce champ DOIT <br/> être présent si le drapeau PenDataLineStyle est défini dans le <br/> champ PenDataFlags de l'objet EmfPlusPenData, et la <br/> valeur DOIT être définie dans l'énumération LineStyle <br/> (section 2.1.1.20). |
| miter_limit | float | r/w | Obtient ou définit une valeur flottante 32 bits optionnelle qui spécifie le joint en onglet <br/>            limite, qui est le rapport maximal autorisé entre la longueur du joint en onglet et<br/>            la largeur de la ligne. La longueur du joint en onglet est la distance entre<br/>            l'intersection des parois de la ligne à l'intérieur de la jonction et <br/>            l'intersection des parois de la ligne à l'extérieur de la jonction. <br/>            La longueur du joint en onglet peut être grande lorsque l'angle entre deux <br/>            lignes est petit. Ce champ DOIT être présent si le <br/>            drapeau PenDataMiterLimit est défini dans le champ PenDataFlags <br/>            de l'objet EmfPlusPenData. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Obtient ou définit un entier signé 32 bits optionnel qui spécifie la <br/>            répartition de la largeur du stylo par rapport aux <br/>            coordonnées de la ligne dessinée. Ce champ DOIT <br/>            être présent si le drapeau PenDataNonCenter est défini dans le <br/>            champ PenDataFlags de l'objet EmfPlusPenData, et <br/>            la valeur DOIT être définie dans l'énumération PenAlignment <br/>            (section 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtient ou définit un entier signé 32 bits optionnel qui spécifie la forme du<br/>             début d'une ligne dans le champ CustomStartCapData. <br/>            Ce champ DOIT être présent si le drapeau PenDataStartCap est défini <br/>            dans le champ PenDataFlags de l'objet EmfPlusPenData, et la<br/>             valeur DOIT être définie dans l'énumération LineCapType <br/>            (section 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) <br/>            qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour <br/>            le stylo. Ce champ DOIT être présent si le drapeau PenDataTransform <br/>            est défini dans le champ PenDataFlags de l'objet EmfPlusPenData <br/>            . |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Initialise une nouvelle instance de la classe EmfPlusPenOptionalData

