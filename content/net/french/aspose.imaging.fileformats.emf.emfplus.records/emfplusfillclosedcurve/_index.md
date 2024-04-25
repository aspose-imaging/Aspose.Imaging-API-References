---
title: EmfPlusFillClosedCurve
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusFillClosedCurve spécifie le remplissage de lintérieur dune spline cardinale fermée
type: docs
weight: 6060
url: /fr/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

L'enregistrement EmfPlusFillClosedCurve spécifie le remplissage de l'intérieur d'une spline cardinale fermée

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Obtient ou définit l'identifiant du pinceau Un entier non signé 32 bits qui spécifie EmfPlusBrush, dont le contenu est déterminé par le bit S dans le champ Flags. Ce pinceau est utilisé pour remplir l'intérieur de la spline cardinale fermée. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières 16 bits . S'il est clair, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante de 32 bits. ---------------------- Un remplissage "enroulé" l'opération remplit les zones selon la règle "parité paire-impaire". Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée comme suit : tracez une ligne entre le point de test et un point distant de de la courbe. Si cette ligne croise la courbe un nombre impair de fois, le point de test est à l'intérieur de la courbe ; sinon, le point de test est en dehors de la courbe. --------------------- Une opération de remplissage "alterné" remplit les zones selon la règle "non nulle" . Selon cette règle, un point de test peut être déterminé comme étant à l'intérieur ou à l'extérieur d'une courbe fermée comme suit : Tracez une ligne à partir d'un point de test jusqu'à un point distant de de la courbe. Comptez le nombre de fois que la courbe croise la ligne de test de gauche à droite, et comptez le nombre de fois que la courbe croise la ligne de test de droite à gauche. Si ces deux nombres sont identiques, le point de test est en dehors de la courbe ; sinon, le point de test est à l'intérieur de la courbe. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est de couleur. Si défini, BrushId spécifie une couleur en tant qu'objet EmfPlusARGB (section 2.2.2.1). S'il est clair, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1 ) dans la table d'objets EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Obtient ou définit le point data Un tableau de points de comptage qui spécifient les extrémités des lignes qui définissent la spline. Dans une spline cardinale fermée, la courbe continue jusqu'au dernier point du tableau PointData et se connecte au premier point du tableau |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. S'il est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est par rapport à l'emplacement spécifié par l'élément précédent dans le tableau. Dans le cas du premier élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. S'il est clair, PointData spécifie les emplacements absolus en fonction de l'indicateur C. Remarque Si cet indicateur est défini, l'indicateur C (ci-dessus) est indéfini et DOIT être ignoré. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Obtient ou définit la tension Une valeur à virgule flottante 32 bits qui spécifie le degré de courbure de la spline lorsqu'elle passe à travers les points. Une valeur de 0,0 indique que la spline est une séquence de lignes droites . Plus la valeur augmente, plus la courbe devient arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)est enroulé. Ce bit indique comment effectuer l'opération de remplissage. S'il est défini, le remplissage est un remplissage "enroulé". S'il est clair, le remplissage est un remplissage "alternatif". |

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
