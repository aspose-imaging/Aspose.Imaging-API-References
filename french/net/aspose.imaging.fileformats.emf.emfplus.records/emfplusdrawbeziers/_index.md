---
title: EmfPlusDrawBeziers
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistrement EmfPlusDrawBeziers spécifie le dessin dune séquence de courbes de Bézier connectées. Lordre des points de données de Bézier est le point de départ le point de contrôle 1 le point de contrôle 2 et le point final. Pour plus dinformations consultez MSDN-DrawBeziers.
type: docs
weight: 5910
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

L'enregistrement EmfPlusDrawBeziers spécifie le dessin d'une séquence de courbes de Bézier connectées. L'ordre des points de données de Bézier est le point de départ, le point de contrôle 1, le point de contrôle 2 et le point final. Pour plus d'informations, consultez [MSDN-DrawBeziers].

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers)(EmfPlusRecord) | Initialise une nouvelle instance du[`EmfPlusDrawBeziers`](../emfplusdrawbeziers) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed) { get; set; } | Obtient ou définit une valeur indiquant si le PointData est compressé. Si défini, PointData spécifie des emplacements absolus dans l'espace de coordonnées avec des coordonnées entières de 16 bits. S'il est clair, PointData spécifie les emplacements absolus dans l'espace de coordonnées avec des coordonnées à virgule flottante 32 bits. Remarque Si l'indicateur relatif (ci-dessous) est défini, cet indicateur est indéfini et DOIT être ignoré. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui DOIT définir le nombre aligné sur 32 bits de octets de données dans le champ RecordData qui suit. Ce numéro n'inclut pas l'en-tête d'enregistrement de 12 octets. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtient ou définit un entier non signé de 16 bits qui contient des informations pour certains enregistrements sur la façon dont l'opération doit être effectuée et sur la structure de l'enregistrement. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. L'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner les courbes de Bézier. La valeur DOIT être de zéro à 63, inclus. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata) { get; set; } | Obtient ou définit le point data Un tableau de points de comptage qui spécifient les points de début, de fin et de contrôle des courbes de Bézier. La coordonnée de fin d'une courbe de Bézier est la coordonnée de départ de la suivante. Les points de contrôle sont utilisés pour produire l'effet Bézier. Le type de données dans ce tableau est spécifié par le champ Flags, comme suit : Type de données Signification Objet EmfPlusPointR (section 2.2.2.37) Si le drapeau P est défini dans le champ Flags , les points spécifient des emplacements relatifs. Objet EmfPlusPointF (section 2.2.2.36) Si les bits P et C sont vides dans le champ Drapeaux, les points spécifient des emplacements absolus. Objet EmfPlusPoint (section 2.2.2.35) Si le bit P est clair et que le bit C est défini dans le champ Drapeaux, les points spécifient des emplacements relatifs. Une courbe de Bézier ne passe pas par ses points de contrôle. Les points de contrôle agissent comme |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative) { get; set; } | Obtient ou définit une valeur indiquant si le PointData est relatif. S'il est défini, chaque élément de PointData spécifie un emplacement dans l'espace de coordonnées qui est relatif à l'emplacement spécifié par l'élément précédent dans le tableau. Dans le cas du premier élément de PointData, un emplacement précédent aux coordonnées (0,0) est supposé. S'il est clair, PointData spécifie les emplacements absolus selon à l'indicateur C. Remarque Si cet indicateur est défini, l'indicateur C (ci-dessus) est indéfini et DOIT être ignoré. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'octets alignés sur 32 bits dans l'enregistrement entier, y compris l'en-tête d'enregistrement de 12 octets et les données spécifiques à l'enregistrement. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtient un entier non signé de 16 bits qui identifie le type d'enregistrement. |

### Voir également

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
