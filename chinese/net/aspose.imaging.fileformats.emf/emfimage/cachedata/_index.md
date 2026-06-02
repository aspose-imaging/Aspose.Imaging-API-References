---
title: "EmfImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfImage 方法。使用此方法可高效缓存数据并防止从底层 DataStreamContainer 重复加载。提升性能并简化应用程序中的数据访问，优化资源利用以提高响应速度。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.emf/emfimage/cachedata/
---
## EmfImage.CacheData method

使用此方法可高效缓存数据并防止从底层 [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 重复加载。提升性能并简化应用程序中的数据访问，优化资源利用以提高响应速度。

```csharp
public override void CacheData()
```

## 示例

此示例展示了如何从文件加载 EMF 图像并列出其所有记录。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // 缓存数据以加载所有记录。
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // 键是记录类型，值是该类型在 WMF 图像中的记录数量。
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // 收集统计信息
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

    // 打印统计
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//输出可能如下所示：
//记录总数：1188
//记录类型                              数量
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

### 另请参见

* class [EmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../emfimage/)
* assembly [Aspose.Imaging](../../../)


