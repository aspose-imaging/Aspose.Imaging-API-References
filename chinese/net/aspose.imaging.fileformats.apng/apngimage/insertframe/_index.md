---
title: "ApngImage.InsertFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ApngImage 方法。使用此直观方法轻松在指定位置向帧集合中插入新帧。非常适合希望对多帧图像动画中帧的排列进行精确控制的开发者。新帧将根据当前图像的大小创建"
type: docs
weight: 230
url: /zh/net/aspose.imaging.fileformats.apng/apngimage/insertframe/
---
## InsertFrame(int) {#insertframe}

使用此直观方法轻松在指定位置向帧集合插入新帧。非常适合希望对多帧图像动画中帧的排列进行精确控制的开发者。新帧将根据当前图像的尺寸创建。

```csharp
public ApngFrame InsertFrame(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 索引。 |

### 返回值

新创建的 APNG 帧。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* 小于 0，或 *index* 大于 [`PageCount`](../pagecount/)。 |

### 另请参见

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage) {#insertframe_1}

在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。

```csharp
public void InsertFrame(int index, RasterImage frameImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 索引。 |
| frameImage | RasterImage | 帧图像。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* 小于 0，或 *index* 大于 [`PageCount`](../pagecount/)。 |
| ArgumentNullException | frameImage 为 null。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## InsertFrame(int, RasterImage, uint) {#insertframe_2}

在指定索引处向自身帧集合插入新帧。新帧的内容将从指定图像填充。

```csharp
public void InsertFrame(int index, RasterImage frameImage, uint frameTime)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 索引。 |
| frameImage | RasterImage | 帧图像。 |
| frameTime | UInt32 | 帧持续时间（毫秒）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* 小于 0，或 *index* 大于 [`PageCount`](../pagecount/)。 |
| ArgumentNullException | frameImage 为 null。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


