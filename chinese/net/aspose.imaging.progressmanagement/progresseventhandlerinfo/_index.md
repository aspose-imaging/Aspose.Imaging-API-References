---
title: "类 ProgressEventHandlerInfo"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo 类。此类表示图像加载/保存/导出操作的进度信息，可在外部应用程序中用于向最终用户显示转换进度。"
type: docs
weight: 11360
url: /zh/net/aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度。

```csharp
public class ProgressEventHandlerInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/description/) { get; } | 获取事件的描述 |
| [EventType](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | 获取事件的类型。 |
| [MaxValue](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 获取进度上限值。 |
| [Value](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/value/) { get; } | 获取当前进度值。 |

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

* namespace [Aspose.Imaging.ProgressManagement](../../aspose.imaging.progressmanagement/)
* assembly [Aspose.Imaging](../../)


