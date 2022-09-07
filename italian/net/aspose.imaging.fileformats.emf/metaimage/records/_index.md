---
title: Records
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta i record.
type: docs
weight: 10
url: /it/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Ottiene o imposta i record.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### Valore della proprietà

I record.

### Esempi

Questo esempio mostra come caricare un'immagine WMF da un file ed elencare tutti i suoi record.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Memorizza i dati nella cache per caricare tutti i record.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // La chiave è un tipo di record, il valore è il numero di record di quel tipo nell'immagine WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Raccogli le statistiche 
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

    // Stampa le statistiche
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//L'output potrebbe essere simile a questo:
//Il numero totale di record: 613
//Conteggio tipo di record
//-----------------------------------------------
//WmfSetBkMode: 1
//WmfSetTextAlign: 1
//WmfSetRop2: 1
//WmfSetWindowOrg: 1
//WmfSetWindowExt: 1
//WmfCreateBrushInDirect: 119
//WmfSelectObject: 240
//WmfCreatePenInDirect: 119
//WmfSetPolyFillMode: 1
//WmfPolyPolygon: 114
//WmfPolyLine: 7
//WmfSetTextColor: 2
//WmfCreateFontInDirect: 2
//WmfExtTextOut: 2
//WmfDibStrechBlt: 1
//WmfE di: 1
```

Questo esempio mostra come caricare un'immagine EMF da un file ed elencare tutti i suoi record.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Memorizza i dati nella cache per caricare tutti i record.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // La chiave è un tipo di record, il valore è il numero di record di quel tipo nell'immagine WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Raccogli le statistiche 
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

    // Stampa le statistiche
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//L'output potrebbe essere simile a questo:
//Il numero totale di record: 1188
//Conteggio tipo di record
//-----------------------------------------------
//EmfMetafileHeader: 1
//Modalità EmfSetBk: 1
//EmfSetTextAlign: 1
//EmfSetRop2: 1
//EmfSetWorldTransform: 1
//EmfExtSelectClipRgn: 1
//EmfCreateBrushIndirect: 113
//EmfSelectObject: 240
//EmfCreatePen: 116
//Modalità EmfSetPolyFill: 1
//Percorso EmfBegin: 120
//EmfMoveToEx: 122
//EmfPolyBezierTo16: 36
//EmfLineA: 172
//EmfCloseFigura: 14
//EmfEndPath: 120
//EmfStrokeAndFillPath: 113
//EmfStrokePath: 7
//EmfSetTextColor: 2
//EmfExtCreateFontIndirectW: 2
//EmfExtTextOutW: 2
//EmfStretchBlt: 1
//EmfE di: 1
```

### Guarda anche

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
