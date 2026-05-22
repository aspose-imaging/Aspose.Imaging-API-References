---
title: "Image.Create"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Image 方法。使用指定的创建选项创建新图像"
type: docs
weight: 10
url: /zh/net/aspose.imaging/image/create/
---
## Create(ImageOptionsBase, int, int) {#create_1}

使用指定的创建选项创建新图像。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 图像选项。 |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

### 返回值

新创建的图像。

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(ImageOptionsBase, int, int, int[]) {#create_2}

从提供的像素数组创建一个 [`RasterImage`](../../rasterimage/) 实例。验证指定的宽度和高度是否匹配像素数据的尺寸。此方法只能在库处于 Licensed 模式时使用。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 用于创建 [`RasterImage`](../../rasterimage/) 的选项。 |
| width | Int32 | [`RasterImage`](../../rasterimage/) 的宽度。 |
| height | Int32 | [`RasterImage`](../../rasterimage/) 的高度。 |
| 像素 | Int32[] | 用于填充图像的像素值数组。 |

### 返回值

一个使用提供的像素数据填充的 [`RasterImage`](../../rasterimage/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImageCreateException](../../../aspose.imaging.coreexceptions/imagecreateexception/) | 如果图像尺寸与像素数组的大小不匹配，或者由于指定的 *imageOptions* 导致图像创建失败，亦或在库未处于 Licensed 模式时调用此方法，则会抛出异常。 |

### 另请参见

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[]) {#create_3}

使用指定的图像作为页面创建新图像

```csharp
public static Image Create(Image[] images)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | Image[] | 这些图像。 |

### 返回值

Image 作为 IMultipageImage

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(MultipageCreateOptions) {#create}

创建指定的多页创建选项。

```csharp
public static Image Create(MultipageCreateOptions multipageCreateOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| multipageCreateOptions | MultipageCreateOptions | 多页创建选项。 |

### 返回值

多页图像

### 另请参见

* class [MultipageCreateOptions](../../../aspose.imaging.imageoptions/multipagecreateoptions/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[], bool) {#create_6}

创建包含指定文件的多页图像。

```csharp
public static Image Create(string[] files, bool throwExceptionOnLoadError)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| files | String[] | 这些文件。 |
| throwExceptionOnLoadError | Boolean | 如果设置为 `true` [在加载错误时抛出异常]。 |

### 返回值

多页图像

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(string[]) {#create_5}

创建包含指定文件的多页图像。

```csharp
public static Image Create(string[] files)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| files | String[] | 这些文件。 |

### 返回值

多页图像

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Create(Image[], bool) {#create_4}

使用指定的图像作为页面创建新图像。

```csharp
public static Image Create(Image[] images, bool disposeImages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | Image[] | 这些图像。 |
| disposeImages | Boolean | 如果设置为 `true` [释放图像]。 |

### 返回值

Image 作为 IMultipageImage

### 另请参见

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


