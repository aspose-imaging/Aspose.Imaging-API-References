---
title: EmfPointEnum
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération Point est utilisée pour spécifier comment un point doit être utilisé dans un appel de dessin.
type: docs
weight: 2790
url: /fr/net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

L'énumération Point est utilisée pour spécifier comment un point doit être utilisé dans un appel de dessin.

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | Un type PT_LINETO ou PT_BEZIERTO peut être combiné avec cette valeur en utilisant l'opérateur binaire OU pour indiquer que le point correspondant est le dernier point d'une figure et que la figure est fermée |
| PT_LINETO | `2` | Spécifie qu'une ligne doit être tracée de la position actuelle à ce point, qui devient alors la nouvelle position actuelle |
| PT_BEZIERTO | `4` | Spécifie que ce point est un point de contrôle ou un point final pour une courbe de Bézier. |
| PT_MOVETO | `6` | Spécifie que ce point commence une figure disjointe. Ce point devient la nouvelle position actuelle. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
