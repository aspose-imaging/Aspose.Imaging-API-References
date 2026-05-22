---
title: "Image.CanLoad"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。确定是否可以从指定的文件路径加载图像"
type: docs
weight: 340
url: /zh/net/aspose.imaging/image/canload/
---
## CanLoad(string) {#canload_2}

确定是否可以从指定的文件路径加载图像。

```csharp
public static bool CanLoad(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

`true` 如果可以从指定的文件加载图像；否则为 `false`。

## 示例

此示例确定图像是否可以从文件加载。

```csharp
[C#]

// 使用文件的绝对路径
bool canLoad = Aspose.Imaging.Image.CanLoad(@"c:\temp\sample.gif");
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(string, LoadOptions) {#canload_3}

确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。

```csharp
public static bool CanLoad(string filePath, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`true` 如果可以从指定的文件加载图像；否则为 `false`。

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream) {#canload}

确定是否可以从指定的流加载图像。

```csharp
public static bool CanLoad(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要加载的流。 |

### 返回值

`true` 如果可以从指定的流加载图像；否则为 `false`。

## 示例

此示例确定图像是否可以从文件流加载。

```csharp
[C#]

string dir = "c:\\temp\\";

bool canLoad;

// 使用文件流
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}

// 以下数据不是有效的图像流，因此 CanLoad 返回 false。
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    canLoad = Aspose.Imaging.Image.CanLoad(stream);
}
```

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## CanLoad(Stream, LoadOptions) {#canload_1}

确定是否可以从指定的流加载图像，并可选地使用指定的 *loadOptions*。

```csharp
public static bool CanLoad(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要加载的流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

`true` 如果可以从指定的流加载图像；否则为 `false`。

### 另请参见

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


