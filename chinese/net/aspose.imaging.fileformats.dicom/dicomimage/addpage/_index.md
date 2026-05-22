---
title: "DicomImage.AddPage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此直观方法通过添加新页面来扩展图像集合。适用于希望动态向多页图像追加页面、确保图像内容无缝扩展和组织的开发者。"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/addpage/
---
## AddPage(RasterImage) {#addpage_1}

通过此直观方法添加新页面，扩展您的图像集合。非常适合希望动态向多页图像追加页面的开发者，确保图像内容的无缝扩展和组织。

```csharp
public void AddPage(RasterImage page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | RasterImage | 要添加的页面。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *page* 为 null。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddPage() {#addpage}

使用此简便方法在图像的页面列表末尾追加新页面。非常适合希望动态扩展多页图像的开发者，确保图像内容的无缝集成和组织。

```csharp
public DicomPage AddPage()
```

### 返回值

新创建的 [`DicomPage`](../../dicompage/)。

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


