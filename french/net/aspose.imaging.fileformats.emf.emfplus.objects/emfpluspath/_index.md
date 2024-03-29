---
title: EmfPlusPath
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet EmfPlusPath spécifie une série de segments de ligne et de courbe qui forment un chemin graphique. Lordre pour les points de données de Bézier est le point de départ le point de contrôle 1 le point de contrôle 2 et le point final. Pour plus dinformations voir MSDN - DrawBeziers.
type: docs
weight: 5610
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
## EmfPlusPath class

L'objet EmfPlusPath spécifie une série de segments de ligne et de courbe qui forment un chemin graphique. L'ordre pour les points de données de Bézier est le point de départ, le point de contrôle 1, le point de contrôle 2 et le point final. Pour plus d'informations, voir [MSDN - DrawBeziers].

```csharp
public sealed class EmfPlusPath : EmfPlusGraphicsObjectType
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPlusPath](emfpluspath)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [PathPointFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointflags) { get; set; } | Obtient ou définit le nombre de points de chemin Un entier non signé 32 bits qui spécifie comment interpréter les points et les types de points associés qui sont définis par cet objet |
| [PathPoints](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints) { get; set; } | Obtient ou définit un tableau de points de chemin Un tableau de points PathPointCount qui spécifient le chemin. Le type d'objets dans ce tableau est spécifié par le champ PathPointFlags, comme suit : Si l'indicateur P est défini, les points sont des emplacements relatifs qui sont spécifiés par les objets EmfPlusPointR (section 2.2.2.37). Si l'indicateur P est clair et le drapeau C est défini, les points sont des emplacements absolus qui sont spécifiés par les objets EmfPlusPoint (section 2.2.2.35). Si le drapeau P est clair et le drapeau C est clair, les points sont des emplacements absolus qui sont spécifiés par les objets EmfPlusPointF (chapitre 2.2.2.36). |
| [PathPointTypes](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointtypes) { get; set; } | Obtient ou définit un tableau qui spécifie comment les points du champ PathPoints sont utilisés pour tracer le chemin. Le type d'objets dans ce tableau est spécifié par le drapeau R dans le champ PathPointFlags |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Obtient ou définit la version. |

### Voir également

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
