---
title: EmfPlusPenOptionalData
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet EmfPlusPenOptionalData spécifie des données facultatives pour un stylet graphique
type: docs
weight: 5680
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

L'objet EmfPlusPenOptionalData spécifie des données facultatives pour un stylet graphique

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Obtient ou définit l'objet EmfPlusCompoundLineData facultatif (section 2.2.2.9) qui spécifie un tableau de valeurs à virgule flottante qui définissent la ligne composée d'un stylo, qui est composée de lignes parallèles et d'espaces. Ce champ DOIT être présent si l'indicateur PenDataCompoundLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Obtient ou définit l'objet optionnel EmfPlusCustomEndCapData (section 2.2.2.11) qui définit la forme d'extrémité personnalisée, qui est la forme à utiliser à la fin d'une ligne tracée avec ce stylo. Il peut s'agir de formes variées, telles qu'un carré, un cercle ou un losange. Ce champ DOIT être présent si l'indicateur PenDataCustomEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Obtient ou définit l'objet EmfPlusCustomStartCapData facultatif (section 2.2.2.15) qui définit la forme de début personnalisée, qui est la forme à utiliser au début d'une ligne tracée avec ce stylo. Il peut s'agir de n'importe quel de différentes formes, comme un carré, un cercle ou un losange. Ce champ DOIT être présent si l'indicateur PenDataCustomStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie la forme de aux deux extrémités de chaque tiret dans une ligne en pointillés. Ce champ DOIT être présent si l'indicateur PenDataDashedLineCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération DashedLineCapType (section 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Obtient ou définit l'objet EmfPlusDashedLineData facultatif (section 2.2.2.16) qui spécifie la longueur des tirets et des espaces dans une ligne pointillée personnalisée. Ce champ DOIT être présent si l'indicateur PenDataDashedLine est défini dans le champ PenDataFlags de l'objet EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits facultative qui spécifie la distance entre le début d'une ligne et le début du premier espace dans un motif de ligne en pointillés. Ce champ DOIT être présent si l'indicateur PenDataDashedLineOffset est défini dans le champ PenDataFlags de l'objet EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie le shape pour la fin d'une ligne dans le champ CustomEndCapData. Ce champ DOIT être présent si l'indicateur PenDataEndCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie comment joindre deux lignes dessinées par le même stylet et dont les extrémités se rejoignent. Ce champ DOIT être présent si l'indicateur PenDataJoin est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineJoinType (section 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie le style utilisé pour les lignes dessinées avec cet objet stylo. Ce champ DOIT être présent si l'indicateur PenDataLineStyle est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineStyle (section 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Obtient ou définit une valeur à virgule flottante 32 bits facultative qui spécifie la limite de mitre , qui est le rapport maximal autorisé entre la longueur de mitre et la largeur de ligne . La longueur en onglet est la distance entre l'intersection des murs linéaires à l'intérieur du joint et l'intersection des murs linéaires à l'extérieur du joint. La longueur de l'onglet peut être grande lorsque l'angle entre deux lignes est petit. Ce champ DOIT être présent si l'indicateur PenDataMiterLimit est défini dans le champ PenDataFlags de l'objet EmfPlusPenData. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie la distribution de la largeur du stylo par rapport aux coordonnées de la ligne tracée. Ce champ DOIT être présent si l'indicateur PenDataNonCenter est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération PenAlignment (section 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Obtient ou définit un entier signé 32 bits facultatif qui spécifie la forme pour le début d'une ligne dans le champ CustomStartCapData. Ce champ DOIT être présent si l'indicateur PenDataStartCap est défini dans le champ PenDataFlags de l'objet EmfPlusPenData, et la valeur DOIT être définie dans l'énumération LineCapType (section 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Obtient ou définit un objet EmfPlusTransformMatrix facultatif (section 2.2.2.47) qui spécifie une transformation de l'espace univers en espace périphérique pour le stylet. Ce champ DOIT être présent si l'indicateur PenDataTransform est défini dans le champ PenDataFlags de l'objet EmfPlusPenData . |

### Voir également

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
