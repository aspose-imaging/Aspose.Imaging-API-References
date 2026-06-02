---
title: "接口 IMaskingSession"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Masking.IMaskingSession 接口。遮罩会话。"
type: docs
weight: 10970
url: /zh/net/aspose.imaging.masking/imaskingsession/
---
## IMaskingSession interface

遮罩会话

```csharp
public interface IMaskingSession : IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Decompose](../../aspose.imaging.masking/imaskingsession/decompose/)() | 执行第一次粗略分解操作 |
| [DecomposeAsync](../../aspose.imaging.masking/imaskingsession/decomposeasync/)() | 创建可执行第一次粗略分解操作的异步任务 |
| [ImproveDecomposition](../../aspose.imaging.masking/imaskingsession/improvedecomposition/)(IMaskingArgs) | 执行再训练分解操作 |
| [ImproveDecompositionAsync](../../aspose.imaging.masking/imaskingsession/improvedecompositionasync/)(IMaskingArgs) | 创建可执行再训练分解操作的异步任务 |
| [Save](../../aspose.imaging.masking/imaskingsession/save/#save)(Stream) | 将会话状态保存到指定的流。 |
| [Save](../../aspose.imaging.masking/imaskingsession/save/#save_1)(string) | 将会话状态保存到指定的文件。 |

## 示例

将遮罩会话保存到文件，以便长时间会话以及在其他环境中恢复会话的可能性。

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// 掩码导出选项
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// 使用 GraphCut 聚类。
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// 背景颜色将为橙色。
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// 首次启动会话并保存到文件
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// 从文件恢复遮罩会话
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // 创建 ImageMasking 类的实例。
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // 对图像进行视觉分析并设置属于分离对象的点。
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // 显式转移导出选项，因为它不可序列化
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### 另请参见

* namespace [Aspose.Imaging.Masking](../../aspose.imaging.masking/)
* assembly [Aspose.Imaging](../../)


