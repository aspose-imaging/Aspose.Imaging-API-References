---
title: "DjvuImage.FirstPage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 属性。使用此属性访问您的 DjVu 文档的首页。快速检索初始页面，以便高效地开始查看或处理文档。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/firstpage/
---
## DjvuImage.FirstPage property

使用此属性访问 DjVu 文档的首页。快速检索首页，以高效开始查看或处理文档。

```csharp
public DjvuPage FirstPage { get; }
```

### Property Value

第一页。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DjvuImageException](../../../aspose.imaging.coreexceptions.imageformats/djvuimageexception/) | 未找到第一页。 |

## 示例

此示例展示了如何从文件流加载 DJVU 图像并打印页面信息。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DJVU 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

//输出可能如下所示：
//总页数：2
//当前页码：    1
//第一页页码：     1
//最后页页码：      2
//--------------------------------------------------
//页码：     1
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
//--------------------------------------------------
//页码：     2
//页面大小：       { Width = 2481, Height = 3508}
//页面原始格式：RgbIndexed1Bpp，使用的通道数：1
```

### 另请参见

* class [DjvuPage](../../djvupage/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


