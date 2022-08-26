---
title: EmfPlusStringFormat
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet EmfPlusStringFormat spécifie la disposition du texte les manipulations daffichage et lidentification de la langue
type: docs
weight: 5780
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

L'objet EmfPlusStringFormat spécifie la disposition du texte, les manipulations d'affichage et l'identification de la langue

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Obtient ou définit un objet EmfPlusLanguageIdentifier qui spécifie la langue à utiliser pour les chiffres numériques dans la chaîne. Par exemple, si cette chaîne contient des chiffres arabes, ce champ DOIT contenir un identifiant de langue qui spécifie une langue arabe |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment substituer des chiffres numériques dans la chaîne en fonction d'un environnement local ou d'une langue. Cette valeur DOIT être définie dans l'énumération StringDigitSubstitution (section 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le nombre d'espaces entre le début d'une ligne de texte et le premier taquet de tabulation |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie le type de traitement qui est effectué sur une chaîne lorsqu'un préfixe de raccourci clavier (c'est-à-dire une esperluette) est rencontré. Fondamentalement, ce champ spécifie s'il faut afficher les préfixes de raccourci clavier qui se rapportent au texte. La valeur DOIT être définie dans l'énumération HotkeyPrefix (section 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Obtient ou définit un objet EmfPlusLanguageIdentifier (section 2.2.2.23) qui spécifie la langue à utiliser pour la chaîne |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la longueur de l'espace à ajouter à la position de départ d'une chaîne. La valeur par défaut est 1/6 de pouce ; pour les polices typographiques, la valeur par défaut est 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment aligner la chaîne verticalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie le nombre d'objets EmfPlusCharacterRange (section 2.2.2.8) définis dans le champ StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie comment aligner la chaîne horizontalement dans le rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringAlignment (section 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Obtient ou définit un objet EmfPlusStringFormatData (section 2.2.2.44) qui spécifie des données de mise en page de texte facultatives. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie les options de mise en page du texte pour le formatage, le découpage et la gestion des polices. Cette valeur DOIT être composée de StringFormat flags (section 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Obtient ou définit un entier signé 32 bits qui spécifie le nombre de taquets de tabulation définis dans le champ StringFormatData. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie le ratio de l'espace horizontal alloué à chaque caractère dans une chaîne spécifiée à la largeur définie par la police du caractère . Les grandes valeurs pour cette propriété spécifient un espace ample entre les caractères ; les valeurs inférieures à 1 peuvent produire chevauchement de caractères. La valeur par défaut est 1,03 ; pour les polices typographic , la valeur par défaut est 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits qui spécifie la longueur de l'espace à laisser après une chaîne. Le default est de 1/6 pouce ; pour les polices typographiques, la valeur par défaut est 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Gets ou sets spécifie comment couper les caractères d'une chaîne qui est trop grande pour tenir dans un rectangle de mise en page. Cette valeur DOIT être définie dans l'énumération StringTrimming (section 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Obtient ou définit la version. |

### Voir également

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
