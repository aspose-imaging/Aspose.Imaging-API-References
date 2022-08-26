---
title: EmfColorAdjustment
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet ColorAdjustment définit les valeurs pour ajuster les couleurs dans les bitmaps source dans les transferts de blocs de bits.
type: docs
weight: 2930
url: /fr/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

L'objet ColorAdjustment définit les valeurs pour ajuster les couleurs dans les bitmaps source dans les transferts de blocs de bits.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la nième valeur de correction gamma de puissance pour le primaire bleu des couleurs source. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Obtient ou définit un entier signé 16 bits qui spécifie la quantité de luminosité à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la luminosité NE DOIT PAS être effectué. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Obtient ou définit un entier signé 16 bits qui spécifie la quantité de couleurs à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage de la couleur NE DOIT PAS être effectué |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Obtient ou définit un entier signé 16 bits qui spécifie la quantité de contraste à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Une valeur de zéro signifie que le réglage du contraste NE DOIT PAS être effectué. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la nième valeur de correction gamma de puissance pour le primaire vert des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui spécifie le type de source de lumière standard sous laquelle l'image est visualisée, à partir de l'énumération Illuminant (section 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la nième valeur de correction gamma de puissance pour la primaire rouge des couleurs sources. Cette valeur DEVRAIT être comprise entre 2 500 et 65 000. Une valeur de 10 000 signifie que la correction gamma NE DOIT PAS être effectuée. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Obtient ou définit un entier signé 16 bits qui spécifie la quantité d'ajustement de teinte rouge ou verte à appliquer à l'objet source. Cette valeur DEVRAIT être comprise entre –100 et 100. Les nombres positifs s'ajustent vers le rouge et les nombres négatifs s'ajustent vers le vert. Une valeur de zéro signifie que le réglage de la teinte NE DOIT PAS être effectué |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la référence noire pour les couleurs source. Toutes les couleurs plus foncées que cela sont traitées comme du noir. Cette valeur DEVRAIT être comprise entre zéro et 4 000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la référence blanche pour les couleurs source. Toutes les couleurs plus claires que cela sont traitées comme du blanc. Cette valeur DEVRAIT être comprise entre 6 000 et 10 000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie la taille en octets de cet objet. Cela DOIT être 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Obtient ou définit un entier non signé 16 bits qui spécifie comment préparer l'image de sortie. Ce champ peut être défini sur NULL ou sur toute combinaison de valeurs dans l'énumération ColorAdjustment (section 2.1.5). |

### Voir également

* class [EmfObject](../emfobject)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
