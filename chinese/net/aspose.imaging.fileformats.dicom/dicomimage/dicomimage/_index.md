---
title: "DicomImage.DicomImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 构造函数。使用此构造函数并利用 dicomOptions 参数，轻松初始化 DicomImage 类的全新实例。完美适用于希望在项目中快速高效地使用 DicomImage 对象的开发者。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/dicomimage/
---
## DicomImage(DicomOptions, int, int) {#constructor}

使用此构造函数并利用 dicomOptions 参数，轻松初始化 DicomImage 类的全新实例。完美适用于希望在项目中快速高效地使用 [`DicomImage`](../) 对象的开发者。

```csharp
public DicomImage(DicomOptions dicomOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dicomOptions | DicomOptions | dicom 选项。 |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

### 另请参见

* class [DicomOptions](../../../aspose.imaging.imageoptions/dicomoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream, LoadOptions) {#constructor_2}

通过在此构造函数中使用 stream 和 loadOptions 参数，顺利启动 DicomImage 类的新实例。适用于渴望在项目中快速有效地使用 [`DicomImage`](../) 对象的开发者。

```csharp
public DicomImage(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

## 示例

此示例展示了如何从文件流加载 DICOM 图像，以保持在指定的内存限制内。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DICOM 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    // 所有内部缓冲区允许的最大大小为 256KB。
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 256 * 1024;

    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream, loadOptions))
    {
        // 将每个页面保存为单独的 PNG 图像。
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // 根据页索引生成文件名。
            string fileName = string.Format("multiframe.{0}.png", dicomPage.Index);

            // DICOM 页面是栅格图像，因此所有对栅格图像允许的操作都适用于 DICOM 页面。
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 另请参见

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## DicomImage(Stream) {#constructor_1}

通过在此构造函数中使用流参数来创建 DicomImage 类的新实例。非常适合希望以简化方式从项目中的现有数据流初始化 [`DicomImage`](../) 对象的开发者。

```csharp
public DicomImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

## 示例

此示例展示了如何从文件流加载 DICOM 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DICOM 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // 将每页保存为单独的 PNG 图像。                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // 根据页索引生成文件名。
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // DICOM 页面是栅格图像，因此所有对栅格图像允许的操作都适用于 DICOM 页面。
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


