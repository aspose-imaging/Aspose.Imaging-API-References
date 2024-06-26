---
title: EmfImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: EmfImage method. Efficiently cache data and prevent redundant loading from the underlying DataStreamContainer with this method. Enhance performance and streamline data access in your application optimizing resource utilization for improved responsiveness
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.emf/emfimage/cachedata/
---
## EmfImage.CacheData method

Efficiently cache data and prevent redundant loading from the underlying [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) with this method. Enhance performance and streamline data access in your application, optimizing resource utilization for improved responsiveness.

```csharp
public override void CacheData()
```

## Examples

This example shows how to load a EMF image from a file and list all of its records.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Cache data to load all records.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // The key is a record type, the value is number of records of that type in the WMF image.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Gather statistics 
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

    // Print statistics
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//The output may look like this:
//The total number of records: 1188
//Record Type                              Count
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### See Also

* class [EmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../emfimage/)
* assembly [Aspose.Imaging](../../../)


