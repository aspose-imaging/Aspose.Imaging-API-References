---
title: ProgressEventHandlerInfo
second_title: Aspose.Imaging for .NET API 参考
description: 此类表示有关图像加载/保存/导出操作进度的信息 可用于外部应用程序向最终用户显示转换进度
type: docs
weight: 10780
url: /zh/net/aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

此类表示有关图像加载/保存/导出操作进度的信息， 可用于外部应用程序向最终用户显示转换进度

```csharp
public class ProgressEventHandlerInfo
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Description](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/description) { get; } | 获取事件的描述 |
| [EventType](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/eventtype) { get; } | 获取事件的类型。 |
| [MaxValue](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/maxvalue) { get; } | 获取进度值上限。 |
| [Value](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/value) { get; } | 获取当前进度值。 |

### 例子

以下示例显示如何打印有关加载/导出操作的进度事件的信息。

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
//初始化：1/4
//预处理：2/4
//处理：3/4
//完成：4/4
//导出事件初始化：1/4
//导出事件预处理：2/4
//导出事件处理：3/4
//导出事件RelativeProgress : 1/1
//相对进度：1/1
//导出事件完成：4/4
```

### 也可以看看

* 命名空间 [Aspose.Imaging.ProgressManagement](../../aspose.imaging.progressmanagement)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
