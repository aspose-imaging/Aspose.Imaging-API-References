---
title: "LoadOptions.ProgressEventHandler"
second_title: "Aspose.Imaging for .NET API 参考"
description: "LoadOptions 属性。获取或设置进度事件处理程序"
type: docs
weight: 60
url: /zh/net/aspose.imaging/loadoptions/progresseventhandler/
---
## LoadOptions.ProgressEventHandler property

获取或设置进度事件处理程序。

```csharp
public ProgressEventHandler ProgressEventHandler { get; set; }
```

### Property Value

进度事件处理程序。

## 示例

以下示例展示了如何打印加载/导出操作的进度事件信息。

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // 使用单独的操作进度事件处理程序进行加载/导出操作的示例
    using (var image = Aspose.Imaging.Image.Load(fileName, new Aspose.Imaging.LoadOptions { ProgressEventHandler = ProgressCallback }))
    {
        image.Save(fileName + ".psd",
                   new Aspose.Imaging.ImageOptions.PsdOptions() { ProgressEventHandler = ExportProgressCallback });
    }
}

private void ProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("{0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

private void ExportProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("Export event {0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

// STDOUT 日志可能如下所示：
//初始化 : 1/4
//预处理 : 2/4
//处理 : 3/4
//完成 : 4/4
//导出事件 初始化 : 1/4
//导出事件 预处理 : 2/4
//导出事件 处理 : 3/4
//导出事件 相对进度 : 1/1
//相对进度 : 1/1
//导出事件 完成 : 4/4
```

### 另请参见

* delegate [ProgressEventHandler](../../progresseventhandler/)
* class [LoadOptions](../)
* namespace [Aspose.Imaging](../../loadoptions/)
* assembly [Aspose.Imaging](../../../)


