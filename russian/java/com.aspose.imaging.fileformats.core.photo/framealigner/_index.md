---
title: "FrameAligner"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Выравнивание кадров"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.core.photo/framealigner/
---
**Inheritance:**
java.lang.Object
```
public final class FrameAligner
```

Выравнивание кадров
## Методы

| Метод | Описание |
| --- | --- |
| [process(RasterImage[] images, FrameAlignerOptions options)](#process-com.aspose.imaging.RasterImage---com.aspose.imaging.fileformats.core.photo.FrameAlignerOptions-) | Обрабатывает указанные изображения. |

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


Обрабатывает указанные изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [RasterImage\[\]](../../com.aspose.imaging/rasterimage) | Изображения. |
| options | [FrameAlignerOptions](../../com.aspose.imaging.fileformats.core.photo/framealigneroptions) | Параметры. |

**Returns:**
java.util.List<com.aspose.imaging.Point> - Список смещений по изображениям
