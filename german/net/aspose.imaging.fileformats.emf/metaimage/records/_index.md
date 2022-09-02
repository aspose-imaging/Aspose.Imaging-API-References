---
title: Records
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Datensätze ab oder legt sie fest.
type: docs
weight: 10
url: /de/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Ruft die Datensätze ab oder legt sie fest.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### Eigentumswert

Die Aufzeichnungen.

### Beispiele

Dieses Beispiel zeigt, wie Sie ein WMF-Bild aus einer Datei laden und alle seine Datensätze auflisten.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden aller Arten von Bildern, einschließlich WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Daten zwischenspeichern, um alle Datensätze zu laden.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // Der Schlüssel ist ein Datensatztyp, der Wert ist die Anzahl der Datensätze dieses Typs im WMF-Bild.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Statistiken sammeln 
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

    // Statistiken drucken
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Datensätze: 613
//Anzahl der Datensatztypen
//----------------------------------------------
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
//WmfPolylinie: 7
//WmfSetTextColor: 2
//WmfCreateFontInDirect: 2
//WmfExtTextOut: 2
//WmfDibStrechBlt: 1
//WmfEof: 1
```

Dieses Beispiel zeigt, wie Sie ein EMF-Bild aus einer Datei laden und alle seine Datensätze auflisten.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden aller Arten von Bildern, einschließlich WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Daten zwischenspeichern, um alle Datensätze zu laden.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // Der Schlüssel ist ein Datensatztyp, der Wert ist die Anzahl der Datensätze dieses Typs im WMF-Bild.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Statistiken sammeln 
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

    // Statistiken drucken
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Datensätze: 1188
//Anzahl der Datensatztypen
//----------------------------------------------
//EmfMetafileHeader: 1
//EmfSetBkMode: 1
//EmfSetTextAlign: 1
//EmfSetRop2: 1
//EmfSetWorldTransform: 1
//EmfExtSelectClipRgn: 1
//EmfCreateBrushIndirekt: 113
//EmfSelectObject: 240
//EmfCreatePen: 116
//EmfSetPolyFillMode: 1
//EmfBeginPath: 120
//EmfMoveToEx: 122
//EmfPolyBezierTo16: 36
//EmfLineTo: 172
//EmfCloseFigure: 14
//EmfEndPath: 120
//EmfStrokeAndFillPath: 113
//EmfStrokePath: 7
//EmfSetTextColor: 2
//EmfExtCreateFontIndirectW: 2
//EmfExtTextOutW: 2
//EmfStretchBlt: 1
//EmfEvon: 1
```

### Siehe auch

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* namensraum [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
