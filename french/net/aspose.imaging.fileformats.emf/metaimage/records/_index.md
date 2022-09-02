---
title: Records
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit les enregistrements.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Obtient ou définit les enregistrements.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### Valeur de la propriété

Les enregistrements.

### Exemples

Cet exemple montre comment charger une image WMF à partir d'un fichier et répertorier tous ses enregistrements.

```csharp
[C#]

string dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est un moyen unifié de charger tous les types d'images, y compris WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Données de cache pour charger tous les enregistrements.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // La clé est un type d'enregistrement, la valeur est le nombre d'enregistrements de ce type dans l'image WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Collecte des statistiques 
    foreach (Aspose.Imaging.FileFormats.Wmf.Objects.WmfObject obj in wmfImage.Records)
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
//Le nombre total d'enregistrements : 613
// Nombre de types d'enregistrement
//----------------------------------------------
//WmfSetBkMode : 1
// WmfSetTextAlign : 1
//WmfSetRop2 : 1
//WmfSetWindowOrg : 1
//WmfSetWindowExt : 1
//WmfCreateBrushInDirect : 119
//WmfSelectObjet : 240
//WmfCreatePenInDirect : 119
//WmfSetPolyFillMode : 1
//WmfPolyPolygon : 114
//LignePolyWmf : 7
//WmfSetTextColor : 2
//WmfCreateFontInDirect : 2
//WmfExtTextOut : 2
//WmfDibStrechBlt : 1
//WmfEof : 1
```

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

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* espace de noms [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
