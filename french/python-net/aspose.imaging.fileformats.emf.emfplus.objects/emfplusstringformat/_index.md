---
title: "Classe EmfPlusStringFormat"
type: docs
weight: 650
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Initialise une nouvelle instance de la classe EmfPlusStringFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la<br/>            langue à utiliser pour les chiffres numériques dans la chaîne.<br/>            Par exemple, si cette chaîne contient des chiffres arabes,<br/>            ce champ DOIT contenir un identifiant de langue qui<br/>            spécifie une langue arabe |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment substituer<br/>            les chiffres numériques dans la chaîne selon une locale ou une langue.<br/>            Cette valeur DOIT être définie dans l'énumération StringDigitSubstitution<br/>            (section 2.1.1.30). |
| first_tab_offset | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre<br/>            d'espaces entre le début d'une ligne de texte et<br/>            le premier arrêt de tabulation |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Obtient ou définit un entier signé 32 bits qui spécifie le type de<br/>            traitement effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est‑à‑dire, un esperluette) est rencontré.<br/>            En gros, ce champ indique s'il faut afficher<br/>            les préfixes de raccourci clavier liés au texte.<br/>            La valeur DOIT être définie dans l'énumération HotkeyPrefix<br/>            (section 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23)<br/>            qui spécifie la langue à utiliser pour la chaîne |
| leading_margin | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la longueur<br/>            de l'espace à ajouter à la position de départ d'une chaîne.<br/>            La valeur par défaut est 1/6 pouce ; pour les polices typographiques, la<br/>            valeur par défaut est 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Obtient ou définit un entier non signé 32 bits qui spécifie comment<br/>            aligner la chaîne verticalement dans le rectangle de mise en page.<br/>            Cette valeur DOIT être définie dans l'énumération StringAlignment. |
| range_count | int | r/w | Obtient ou définit un entier signé 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange<br/>            (section 2.2.2.8) définis dans le champ StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Obtient ou définit un entier non signé 32 bits qui spécifie comment<br/>            aligner la chaîne horizontalement dans le rectangle de mise en page.<br/>            Cette valeur DOIT être définie dans l'énumération StringAlignment<br/>            (section 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44)<br/>            qui spécifie des données de mise en page de texte optionnelles. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Obtient ou définit un entier non signé 32 bits qui spécifie les options de mise en page du texte<br/>            pour le formatage, le rognage et la gestion des polices.<br/>            Cette valeur DOIT être composée des indicateurs StringFormat<br/>            (section 2.1.2.8). |
| tabstop_count | int | r/w | Obtient ou définit un entier signé 32 bits qui spécifie le nombre d'arrêts de tabulation<br/>            définis dans le champ StringFormatData. |
| tracking | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le rapport<br/>            de l'espace horizontal attribué à chaque caractère d'une<br/>            chaîne spécifiée par rapport à la largeur définie par la police du<br/>            caractère. Des valeurs élevées pour cette propriété indiquent un espace généreux<br/>            entre les caractères ; des valeurs inférieures à 1 peuvent provoquer<br/>            un chevauchement des caractères. La valeur par défaut est 1,03 ; pour les polices typographiques,<br/>            la valeur par défaut est 1,00. |
| trailing_margin | float | r/w | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la longueur<br/>            de l'espace à laisser après une chaîne. La valeur par défaut<br/>            est 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Obtient ou définit la façon de couper les caractères d'une chaîne qui est<br/>            trop grande pour tenir dans un rectangle de mise en page. Cette valeur<br/>            DOIT être définie dans l'énumération StringTrimming (section 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtient ou définit la version. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Initialise une nouvelle instance de la classe EmfPlusStringFormat

