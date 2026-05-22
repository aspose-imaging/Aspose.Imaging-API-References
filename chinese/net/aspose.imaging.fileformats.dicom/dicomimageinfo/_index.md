---
title: "类 DicomImageInfo"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Dicom.DicomImageInfo 类。包含来自 Dicom 文件头的所有元信息。"
type: docs
weight: 2510
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---
## DicomImageInfo class

包含来自 Dicom 文件头的所有元信息。

```csharp
public sealed class DicomImageInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsAllocated](../../aspose.imaging.fileformats.dicom/dicomimageinfo/bitsallocated/) { get; } | 获取 "bitsAllocated" 的值。 |
| [BitsStored](../../aspose.imaging.fileformats.dicom/dicomimageinfo/bitsstored/) { get; } | 获取存储位的数量。 |
| [Blues](../../aspose.imaging.fileformats.dicom/dicomimageinfo/blues/) { get; } | 获取蓝色的颜色数组。 |
| [DicomHeaderInfoByBytes](../../aspose.imaging.fileformats.dicom/dicomimageinfo/dicomheaderinfobybytes/) { get; } | 按字节获取 DICOM 头信息。 |
| [DicomInfo](../../aspose.imaging.fileformats.dicom/dicomimageinfo/dicominfo/) { get; } | 获取 DICOM 文件的头信息。 |
| [Greens](../../aspose.imaging.fileformats.dicom/dicomimageinfo/greens/) { get; } | 获取绿色的颜色数组。 |
| [Height](../../aspose.imaging.fileformats.dicom/dicomimageinfo/height/) { get; } | 获取高度。 |
| [IsLittleEndian](../../aspose.imaging.fileformats.dicom/dicomimageinfo/islittleendian/) { get; } | 获取一个值，指示此实例是否为小端序。 |
| [NumberOfFrames](../../aspose.imaging.fileformats.dicom/dicomimageinfo/numberofframes/) { get; } | 获取帧数。 |
| [Offset](../../aspose.imaging.fileformats.dicom/dicomimageinfo/offset/) { get; } | 获取偏移量。 |
| [PhotoInterpretation](../../aspose.imaging.fileformats.dicom/dicomimageinfo/photointerpretation/) { get; } | 获取 "PhotoInterpretation" 的值。 |
| [PixelRepresentation](../../aspose.imaging.fileformats.dicom/dicomimageinfo/pixelrepresentation/) { get; } | 获取像素 "pixelRepresentation" 的值。 |
| [PlanarConfiguration](../../aspose.imaging.fileformats.dicom/dicomimageinfo/planarconfiguration/) { get; } | 获取平面配置。 |
| [Reds](../../aspose.imaging.fileformats.dicom/dicomimageinfo/reds/) { get; } | 获取红色的数组颜色 |
| [RescaleIntercept](../../aspose.imaging.fileformats.dicom/dicomimageinfo/rescaleintercept/) { get; } | 获取 "rescaleIntercept" 的值。 |
| [RescaleSlope](../../aspose.imaging.fileformats.dicom/dicomimageinfo/rescaleslope/) { get; } | 获取 "rescaleSlope" 的值。 |
| [SamplesPerPixel](../../aspose.imaging.fileformats.dicom/dicomimageinfo/samplesperpixel/) { get; } | 获取 "samplesPerPixel" 的值。 |
| [SignedImage](../../aspose.imaging.fileformats.dicom/dicomimageinfo/signedimage/) { get; } | 获取指示是否为 "signedImage" 的值。 |
| [Width](../../aspose.imaging.fileformats.dicom/dicomimageinfo/width/) { get; } | 获取宽度。 |
| [WindowCentre](../../aspose.imaging.fileformats.dicom/dicomimageinfo/windowcentre/) { get; } | 获取窗口中心。 |
| [WindowWidth](../../aspose.imaging.fileformats.dicom/dicomimageinfo/windowwidth/) { get; } | 获取窗口的宽度。 |
| static [ReadonlyTagsList](../../aspose.imaging.fileformats.dicom/dicomimageinfo/readonlytagslist/) { get; } | 只读标签列表。保存图像时，这些标签值将根据实际图像数据重置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddTag](../../aspose.imaging.fileformats.dicom/dicomimageinfo/addtag/)(string, object) | 添加新的 Dicom 标签。 |
| [RemoveTagAt](../../aspose.imaging.fileformats.dicom/dicomimageinfo/removetagat/)(int) | 删除现有标签。 |
| [TryAddTag](../../aspose.imaging.fileformats.dicom/dicomimageinfo/tryaddtag/)(string, object) | 添加新的 Dicom 标签。 |
| [TryRemoveTagAt](../../aspose.imaging.fileformats.dicom/dicomimageinfo/tryremovetagat/)(int) | 删除现有标签。 |
| [TryUpdateTagAt](../../aspose.imaging.fileformats.dicom/dicomimageinfo/tryupdatetagat/)(int, object) | 更新现有标签。 |
| [UpdateTagAt](../../aspose.imaging.fileformats.dicom/dicomimageinfo/updatetagat/)(int, object) | 更新现有标签。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom/)
* assembly [Aspose.Imaging](../../)


