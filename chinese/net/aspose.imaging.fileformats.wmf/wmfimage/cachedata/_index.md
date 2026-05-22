---
title: "WmfImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfImage 方法。高效缓存数据，消除从底层 DataStreamContainer 进行额外加载的需求。利用此方法通过存储和访问本地数据缓存来优化性能并最小化资源使用。"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.wmf/wmfimage/cachedata/
---
## WmfImage.CacheData method

高效缓存数据，消除从底层 [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 进行额外加载的需求。利用此方法通过存储和访问本地数据缓存来优化性能并最小化资源使用。

```csharp
public override void CacheData()
```

### 异常

| 异常 | 条件 |
| --- | --- |
| NotImplementedException |  |

## 示例

此示例展示了如何从文件加载 WMF 图像并列出其所有记录。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // 缓存数据以加载所有记录。
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // 键是记录类型，值是该类型在 WMF 图像中的记录数量。
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // 收集统计信息
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
//记录的总数: 613
//记录类型                              数量
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

### 另请参见

* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


