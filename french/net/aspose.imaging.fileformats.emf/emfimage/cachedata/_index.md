---
title: CacheData
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Met en cache les données et garantit quaucun chargement de données supplémentaire ne sera effectué à partir du sous-jacentDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 90
url: /fr/net/aspose.imaging.fileformats.emf/emfimage/cachedata/
---
## EmfImage.CacheData method

Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Exemples

Cet exemple montre comment charger une image EMF à partir d'un fichier et répertorier tous ses enregistrements.

```csharp
[C#]

string dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est un moyen unifié de charger tous les types d'images, y compris WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Données de cache pour charger tous les enregistrements.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // La clé est un type d'enregistrement, la valeur est le nombre d'enregistrements de ce type dans l'image WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Collecte des statistiques 
    foreach (Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord obj in emfImage.Records)
    {
        System.Type objType = obj.GetType();
        if (!types.ContainsKey(objType))
        {
            types.Add(objType, 1);
        }
        else
        {
            types[objType]++;
        }
    }

    // Imprimer les statistiques
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//La sortie peut ressembler à ceci :
//Le nombre total d'enregistrements : 1188
// Nombre de types d'enregistrement
//----------------------------------------------
//EmfMetafileHeader : 1
//EmfSetBkMode : 1
//EmfSetTextAlign : 1
//EmfSetRop2 : 1
//EmfSetWorldTransform : 1
//EmfExtSelectClipRgn : 1
//EmfCreateBrushIndirect : 113
//EmfSelectObjet : 240
//EmfCreatePen : 116
//EmfSetPolyFillMode : 1
//EmfBeginPath : 120
//EmfMoveToEx : 122
//EmfPolyBezierTo16 : 36
//EmfLigneVers : 172
//EmfFermeFigure : 14
//EmfEndPath : 120
//EmfStrokeAndFillPath : 113
//EmfStrokePath : 7
//EmfSetTextColor : 2
//EmfExtCreateFontIndirectW : 2
//EmfExtTextOutW : 2
//EmfStretchBlt : 1
//EmfEof : 1
```

### Voir également

* class [EmfImage](../../emfimage)
* espace de noms [Aspose.Imaging.FileFormats.Emf](../../emfimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
