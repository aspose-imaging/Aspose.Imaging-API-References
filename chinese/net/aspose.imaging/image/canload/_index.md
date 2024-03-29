---
title: CanLoad
second_title: Aspose.Imaging for .NET API 参考
description: 判断是否可以从指定的文件路径加载图片
type: docs
weight: 260
url: /zh/net/aspose.imaging/image/canload/
---
## CanLoad(string) {#canload_2}

判断是否可以从指定的文件路径加载图片。

```csharp
public static bool CanLoad(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

`真的`是否可以从指定文件加载图像；否则，`错误的` .

### 例子

此示例确定是否可以从文件加载图像。

```csharp
[C#]

// 使用文件的绝对路径
bool canLoad = Aspose.Imaging.Image.CanLoad(@"c:\temp\sample.gif");
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## CanLoad(string, LoadOptions) {#canload_3}

确定是否可以从指定的文件路径加载图像，并且可以选择使用指定的打开选项。

```csharp
public static bool CanLoad(string filePath, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`真的`是否可以从指定文件加载图像；否则，`错误的` .

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## CanLoad(Stream) {#canload}

确定是否可以从指定流中加载图像。

```csharp
public static bool CanLoad(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载的流。 |

### 返回值

`真的`是否可以从指定的流中加载图像；否则，`错误的` .

### 例子

此示例确定是否可以从文件流中加载图像。

```csharp
[C#]

string dir = "c:\\temp\\";

bool canLoad;

// 使用文件流
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}

// 下面的数据不是有效的图片流，所以 CanLoad 返回 false。
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

---

## CanLoad(Stream, LoadOptions) {#canload_1}

确定是否可以从指定的流加载图像，并且可以选择使用指定的*loadOptions* .

```csharp
public static bool CanLoad(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要从中加载的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`真的`是否可以从指定的流中加载图像；否则，`错误的` .

### 也可以看看

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* 命名空间 [Aspose.Imaging](../../image)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
