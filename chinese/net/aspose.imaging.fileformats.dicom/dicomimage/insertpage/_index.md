---
title: "DicomImage.InsertPage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此直观的方法在指定索引处向图像的页面列表插入新页面。对于希望在多页图像中精确控制页面排列、确保内容组织无缝并可自定义的开发者而言，这是理想的选择。"
type: docs
weight: 220
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/insertpage/
---
## DicomImage.InsertPage method

使用此直观方法在图像的页面列表中指定索引处插入新页面。非常适合希望对多页图像的页面排列进行精确控制，确保图像内容的无缝组织和自定义的开发者。

```csharp
public DicomPage InsertPage(int pageIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageIndex | Int32 | 页面的索引。 |

### 返回值

新创建的 [`DicomPage`](../../dicompage/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *pageIndex* 超出范围。 |

## 示例

创建多页 Dicom 图像。

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // 使用矢量图形绘制内容
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // 在后面添加几页，使其更暗
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // 在主页面前添加几页，使其更亮
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // 将创建的多页图像保存到输出文件
    image.Save("MultiPage.dcm");
}
```

### 另请参见

* class [DicomPage](../../dicompage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


