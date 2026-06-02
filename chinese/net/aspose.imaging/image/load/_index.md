---
title: "Image.Load"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。加载指定文件路径或 URL 的新图像。如果 filePath 是文件路径，方法仅打开该文件。如果 filePath 是 URL，方法下载文件，将其存储为临时文件并打开它。"
type: docs
weight: 20
url: /zh/net/aspose.imaging/image/load/
---
## Load(string, LoadOptions) {#load_3}

从指定的文件路径或 URL 加载新图像。如果 *filePath* 是文件路径，方法仅打开该文件。如果 *filePath* 是 URL，方法会下载文件，将其存储为临时文件，然后打开它。

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于加载图像的文件路径或 URL。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

已加载的图像。

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(string) {#load_2}

从指定的文件路径或 URL 加载新图像。如果 *filePath* 是文件路径，方法仅打开该文件。如果 *filePath* 是 URL，方法会下载文件，将其存储为临时文件，然后打开它。

```csharp
public static Image Load(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于加载图像的文件路径或 URL。 |

### 返回值

已加载的图像。

## 示例

此示例演示如何使用指定的文件路径将现有 Image 文件加载到 Aspose.Imaging.Image 实例中。

```csharp
[C#]

//创建 Image 实例并使用磁盘位置的现有图像文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    //进行一些图像处理
}
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

从指定的流加载新图像。

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

已加载的图像。

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Load(Stream) {#load}

从指定的流加载新图像。

```csharp
public static Image Load(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |

### 返回值

已加载的图像。

## 示例

此示例演示如何使用 System.IO.Stream 对象加载现有 Image 文件

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.bmp", System.IO.FileMode.Open))
{
    //创建 Image 类的实例，并通过调用 Load 方法使用 FileStream 对象加载现有文件
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(stream))
    {
        //进行一些图像处理。
    }
}
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


