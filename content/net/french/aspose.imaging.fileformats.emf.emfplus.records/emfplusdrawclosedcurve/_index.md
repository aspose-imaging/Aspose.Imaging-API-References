---
title: EmfPlusDrawClosedCurve
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusDrawClosedCurve spécifie le dessin dune spline cardinale fermée
type: docs
weight: 5920
url: /fr/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

L'enregistrement EmfPlusDrawClosedCurve spécifie le dessin d'une spline cardinale fermée

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType - Un entier non signé de 16 bits qui identifie ce type d'enregistrement comme EmfPlusDrawClosedCurve à partir de l'énumération RecordType (section 2.1.1.1). La valeur DOIT être 0x4017. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)est compressé. Ce bit indique si le champ PointData spécifie des données compressées. S'il est défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est clair, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante 32 bits Remarque Si l'indicateur relatif (ci-dessous) est défini, cet indicateur est indéfini et DOIT être ignoré |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner la courbe fermée. La valeur DOIT être de zéro à 63, inclus. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Obtient ou définit le point data Un tableau de points de comptage qui spécifient les extrémités des lignes qui définissent la spline. Dans une spline cardinale fermée, la courbe continue jusqu'au dernier point du tableau PointData et se connecte au premier point du tableau. Le type de données dans ce tableau est spécifié par le champ Flags, comme suit : Type de données Signification EmfPlusPointR objet (section 2.2.2.37) Si le drapeau P est défini dans le champ Drapeaux, les points spécifient des emplacements relatifs. Objet EmfPlusPointF (section 2.2.2.36) Si les bits P et C sont définis dans le champ Drapeaux, les points spécifient emplacements absolus. Objet EmfPlusPoint (section 2.2.2.35) Si le bit P est clair et que le bit C est défini dans le champ Drapeaux, les points spécifient des emplacements relatifs. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Obtient ou définit une valeur indiquant si cette[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)est relatif. Ce bit indique si le champ PointData spécifie des emplacements relatifs ou absolus. S'il est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent dans le tableau. Dans le cas du premier élément dans PointData, un emplacement précédent aux coordonnées (0,0) est supposé. S'il est clair, PointData spécifie les emplacements absolus en fonction de l'indicateur C. Remarque Si cet indicateur est défini, l'indicateur compressé (ci-dessus) est indéfini et DOIT être ignoré |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Obtient ou définit la tension Un nombre à virgule flottante de 32 bits qui spécifie le degré de courbure de la spline lorsqu'elle passe par les points. Une valeur de 0 spécifie que la spline est une séquence de lignes droites. Au fur et à mesure que la valeur augmente, la courbe devient plus arrondie. Pour plus d'informations, voir [SPLINE77] et [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
