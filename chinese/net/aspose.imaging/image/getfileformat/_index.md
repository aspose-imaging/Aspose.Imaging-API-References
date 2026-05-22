---
title: "Image.GetFileFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。获取文件格式"
type: docs
weight: 350
url: /zh/net/aspose.imaging/image/getfileformat/
---
## GetFileFormat(string) {#getfileformat_1}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着指定的图像可以被加载。使用其中一个 CanLoad 方法重载来确定文件是否可以被加载。

## 示例

此示例展示了如何在不从文件加载整个图像的情况下确定图像格式。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用文件的绝对路径
Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(dir + "sample.gif");
System.Console.WriteLine("The file format is {0}", format);
```

### 另请参见

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着指定的图像可以被加载。使用其中一个 CanLoad 方法重载来确定流是否可以被加载。

## 示例

此示例展示了如何在不从文件流加载整个图像的情况下确定图像格式。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用文件流
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}

// 以下数据不是有效的图像流，因此 GetFileFormat 返回 FileFormat.Undefined。
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}
```

### 另请参见

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


