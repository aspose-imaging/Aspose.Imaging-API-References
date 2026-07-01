---
title: "FrameAligner"
second_title: "Aspose.Imaging for Java API 参考"
description: "对齐帧"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.core.photo/framealigner/
---
**Inheritance:**
java.lang.Object
```
public final class FrameAligner
```

对齐帧
## 方法

| 方法 | 描述 |
| --- | --- |
| [process(RasterImage[] images, FrameAlignerOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.FrameAlignerOptions-) | 处理指定的图像。 |

## Example: The example shows how to align a series of images relative to the first one.

``` java
final int imagesCount = 5;
final boolean modify = true;
            
RasterImage[] images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.load("DSC_5715.JPG");
images[1] = (RasterImage)Image.load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.load("manor_plus2ev.jpg");
            
FrameAlignerOptions alignOptions = new FrameAlignerOptions();
alignOptions.setModifyImages(modify);
List<Point> results = FrameAligner.process(images, alignOptions);
            
System.out.println(results.get(0));
System.out.println(results.get(1));
System.out.println(results.get(2));
System.out.println(results.get(3));
System.out.println(results.get(4));
            
int i = 0;
for (RasterImage image : images)
{
    i++;
    String outputFilePath = i + "_result.jpg";
    image.save(outputFilePath);
    image.close();
}
```

### process(RasterImage[] images, FrameAlignerOptions options) {#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.FrameAlignerOptions-}
```
public static List<Point> process(RasterImage[] images, FrameAlignerOptions options)
```


处理指定的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | 图像。 |
| options | [FrameAlignerOptions](../../com.aspose.imaging.fileformats.core.photo/framealigneroptions) | 选项。 |

**Returns:**
java.util.List<com.aspose.imaging.Point> - 图像的偏移列表
