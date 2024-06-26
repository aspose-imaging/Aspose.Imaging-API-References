---
title: WmfImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: WmfImage method. Efficiently cache the data eliminating the need for additional loading from the underlying DataStreamContainer. Utilize this method to optimize performance and minimize resource usage within your application by storing and accessing local data cache
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.wmf/wmfimage/cachedata/
---
## WmfImage.CacheData method

Efficiently cache the data, eliminating the need for additional loading from the underlying [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/). Utilize this method to optimize performance and minimize resource usage within your application by storing and accessing local data cache.

```csharp
public override void CacheData()
```

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException |  |

## Examples

This example shows how to load a WMF image from a file and list all of its records.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Cache data to load all records.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // The key is a record type, the value is number of records of that type in the WMF image.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Gather statistics 
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
//The total number of records: 613
//Record Type                              Count
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### See Also

* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


