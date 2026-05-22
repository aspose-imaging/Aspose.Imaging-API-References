---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.Imaging for .NET API 参考"
description: "FileCreateSource 构造函数。初始化 FileCreateSource 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

初始化 [`FileCreateSource`](../) 类的新实例。

```csharp
public FileCreateSource(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |

## 示例

此示例在磁盘的某个位置创建一个新的 Image 文件，位置由 BmpOptions 实例的 Source 属性指定。如果在 FileCreateSource 的构造函数中未传入第二个参数，则默认要创建的文件的 IsTemporal 属性被设置为 True。IsTemporal 设置为 True 时，执行结束后不会在磁盘上保存文件。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//如果未传入第二个参数，则默认文件的 IsTemporal 被设置为 True
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp");

//创建 Image 的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //进行一些图像处理
}
```

### 另请参见

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

初始化 [`FileCreateSource`](../) 类的新实例。

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |
| isTemporal | Boolean | 如果设置为 `true`，创建的文件将是临时的。 |

## 示例

此示例在磁盘的某个位置创建一个新 Image 文件，位置由 BmpOptions 实例的 Source 属性指定。在创建实际图像之前，设置了 BmpOptions 实例的多个属性。尤其是此情况下指向实际磁盘位置的 Source 属性。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//通过调用 Create 方法创建 Image 实例并使用 BmpOptions 实例进行初始化。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //进行一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 另请参见

* class [FileCreateSource](../)
* namespace [Aspose.Imaging.Sources](../../filecreatesource/)
* assembly [Aspose.Imaging](../../../)


