---
title: "Classe EmfText"
type: docs
weight: 260
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfText()](#EmfText__1) | Initialise une nouvelle instance de la classe EmfText |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| caractères | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de caractères dans la chaîne |
| dx_buffer | int[] | r/w | Obtient ou définit le tampon optionnel d'espacement des caractères<br/>            UndefinedSpace2 (variable) : un nombre optionnel d'octets inutilisés. Le champ OutputDx n'est pas requis pour <br/>            suivre immédiatement la partie précédente de cette structure.<br/>            OutputDx (variable) : un tableau d'entiers non signés de 32 bits qui spécifient l'espacement de sortie entre <br/>            les origines des cellules de caractères adjacentes en unités logiques. L'emplacement de ce champ est indiqué par <br/>            la valeur de offDx en octets depuis le début de cet enregistrement. Si l'espacement est défini, ce champ contient <br/>            le même nombre de valeurs que de caractères dans la chaîne de sortie. Si le champ Options de l'objet EmrText <br/>            contient le drapeau ETO_PDY, alors ce tampon contient deux fois plus de valeurs que le nombre de caractères dans <br/>            la chaîne de sortie, un décalage horizontal et un décalage vertical pour chacun, dans cet ordre. Si ETO_RTLREADING est spécifié, <br/>            les caractères sont disposés de droite à gauche au lieu de gauche à droite. Aucune autre option n'affecte l'interprétation de ce champ. |
| glyph_index_buffer | int[] | r/w | Obtient ou définit le tampon optionnel d'index de glyphes.<br/>            Si les options contiennent le drapeau ETO_GLYPH_INDEX, alors les codes des caractères dans une chaîne de texte de sortie sont en fait des index<br/>            des glyphes de caractères dans une police TrueType (énumération ExtTextOutOptions 2.1.11). Les index de glyphes sont spécifiques à la police,<br/>            ainsi, pour afficher correctement les caractères lors de la lecture, la police utilisée DOIT être identique à celle utilisée pour<br/>            générer les index. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment utiliser le rectangle indiqué dans le champ <br/>            Rectangle. Ce champ peut être une combinaison de plusieurs valeurs de l'énumération ExtTextOutOptions <br/>            (section 2.1.11). |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL optionnel ([MS-WMF] section 2.2.2.19) qui définit un rectangle de découpage <br/>            et/ou d'opacification en unités logiques. Ce rectangle est appliqué à la sortie de texte <br/>            effectuée par l'enregistrement contenant. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL ([MS-WMF] section 2.2.2.15) qui spécifie les coordonnées du <br/>            point de référence utilisé pour positionner la chaîne. Le point de référence est défini par le dernier <br/>            enregistrement EMR_SETTEXTALIGN (section 2.3.11.25). Si aucun enregistrement de ce type n'a été défini, <br/>            l'alignement par défaut est TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Obtient ou définit le tampon de chaîne de caractères<br/>            UndefinedSpace1 (variable) : un nombre optionnel d'octets inutilisés. <br/>            Le champ OutputString n'est pas requis pour suivre immédiatement la partie précédente de cette structure.<br/>            OutputString (variable) : un tableau de caractères qui spécifient la chaîne à sortir. <br/>            L'emplacement de ce champ est indiqué par la valeur de offString en octets depuis le début de cet enregistrement. <br/>            Le nombre de caractères est indiqué par la valeur de Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Initialise une nouvelle instance de la classe EmfText

