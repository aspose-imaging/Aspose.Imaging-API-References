---
title: "TgaImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们针对 TARGA Truevision Advanced Raster Adapter 格式定制的 API 操作 TGA 栅格图像文件，实现无缝加载和自定义。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

使用我们的 API 操作 TGA 栅格图像文件，该 API 针对 TARGA（Truevision Advanced Raster Adapter）格式进行定制，实现无缝加载和自定义。轻松更新作者、时间戳、图像 ID 和软件版本等公共属性，同时使用不同的每像素位数设置、Alpha 通道和颜色透明度。此外，您还可以将 TGA 图像导出为其他流行的栅格格式，确保项目的兼容性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | 使用提供的文件路径初始化一个新的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 对象以加载图像内容。 |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | 通过提供光栅图像对象创建 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 类的新实例。 |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | 使用流加载图像来初始化 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 检索每像素位数值，提供有关图像颜色深度的关键信息。 |
| [getBytesPerPixel()](#getBytesPerPixel--) | 获取每像素字节数值，表示图像中每个像素占用的内存量。 |
| [hasAlpha()](#hasAlpha--) | 检索一个布尔值，指示 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否包含 alpha 通道，以实现透明效果。 |
| [isGrayScale()](#isGrayScale--) | 获取一个布尔值，指示 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否为灰度图像。 |
| [getWidth()](#getWidth--) | 检索此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例所表示图像的宽度。 |
| [getHeight()](#getHeight--) | 获取此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例所封装图像的高度。 |
| [getFileFormat()](#getFileFormat--) | 获取此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例所表示图像文件格式的关键信息。 |
| [hasColorMap()](#hasColorMap--) | 检索此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例是否包含颜色映射表。 |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | 获取 gamma 值的分子部分，这对于图像的准确颜色表示至关重要。 |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | 检索 gamma 值的分母部分，这是决定图像颜色表示的关键因素。 |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | 检索像素纵横比的分子组件，它影响图像中像素的视觉比例。 |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | 检索像素纵横比的分母部分，这是决定图像中像素视觉比例的关键因素。 |
| [getXOrigin()](#getXOrigin--) | 获取图像左下角的绝对水平坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。 |
| [setXOrigin(int value)](#setXOrigin-int-) | 设置图像左下角的绝对水平坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。 |
| [getYOrigin()](#getYOrigin--) | 获取图像左下角的绝对垂直坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。 |
| [setYOrigin(int value)](#setYOrigin-int-) | 设置图像左下角的绝对垂直坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。 |
| [getImageId()](#getImageId--) | 获取与图像关联的唯一标识符。 |
| [setImageId(String value)](#setImageId-java.lang.String-) | 设置与图像关联的唯一标识符。 |
| [getAuthorComments()](#getAuthorComments--) | 检索或设置图像作者提供的注释。 |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | 检索或设置图像作者提供的注释。 |
| [getAuthorName()](#getAuthorName--) | 检索或设置与图像关联的作者名称。 |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | 检索或设置与图像关联的作者名称。 |
| [getDateTimeStamp()](#getDateTimeStamp--) | 获取日期/时间戳。 |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | 设置日期/时间戳。 |
| [getJobNameOrId()](#getJobNameOrId--) | 检索或设置与图像关联的作业名称或 ID。 |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | 检索或设置与图像关联的作业名称或 ID。 |
| [getJobTime()](#getJobTime--) | 检索或设置指示与图像关联的作业时间的时间戳。 |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | 检索或设置指示与图像关联的作业时间的时间戳。 |
| [getTransparentColor()](#getTransparentColor--) | 检索或设置与图像关联的关键颜色。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | 检索或设置与图像关联的关键颜色。 |
| [hasTransparentColor()](#hasTransparentColor--) | 检索或设置一个布尔值，指示图像是否包含透明颜色。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 检索或设置一个布尔值，指示图像是否包含透明颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | 检索或设置图像的背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 检索或设置图像的背景颜色。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 检索或设置一个值，指示图像是否包含背景颜色。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 检索或设置一个值，指示图像是否包含背景颜色。 |
| [getSoftwareVersion()](#getSoftwareVersion--) | 检索或设置与图像关联的软件版本。 |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | 检索或设置与图像关联的软件版本。 |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | 检索或设置与图像关联的软件版本的字母部分。 |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | 检索或设置与图像关联的软件版本的字母部分。 |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | 检索或设置与图像关联的软件版本的数字部分。 |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | 检索或设置与图像关联的软件版本的数字部分。 |
| [getSoftwareId()](#getSoftwareId--) | 管理与图像关联的软件标识 (ID)，允许最多 40 个 ASCII 字符。 |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | 管理与图像关联的软件标识 (ID)，允许最多 40 个 ASCII 字符。 |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | 在比较过程中，对两个 TGA 图像执行相等比较，考虑第一和第二图像。 |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | 对两个 TGA 图像执行不相等比较，评估第一和第二图像。 |
| [deepClone()](#deepClone--) | 生成当前实例的副本，创建一个克隆原始所有属性和特性的新对象。 |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | 复制另一个 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 对象的属性，创建一个具有相同属性的新实例。 |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | 在相等比较中，方法评估当前 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例是否等于作为参数提供的第二个图像。 |
| [equals(Object other)](#equals-java.lang.Object-) | 该方法在当前 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例与作为参数提供的另一个对象之间执行相等比较。 |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | "rotateFlip" 方法使图像能够进行旋转和翻转操作。 |
| [hashCode()](#hashCode--) | 检索当前实例的哈希码。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 将图像裁剪到指定区域。 |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | 通过指定左、右、上、下边界的偏移量来裁剪图像。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 在保持所需尺寸和宽高比的同时，使用特定设置调整图像大小。 |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | 使用指定的缩放类型调整图像大小，该类型决定了缩放操作的执行方式。 |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | 将图像围绕中心按指定角度旋转，同时保持缩放比例并保留背景颜色。 |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


使用提供的文件路径初始化一个新的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 对象以加载图像内容。此构造函数高效地初始化图像实例，允许无缝访问 TGA 图像文件，简化在应用程序工作流中的集成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像的路径。 |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


通过提供光栅图像对象创建 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 类的新实例。此构造函数有助于将现有光栅图像直接集成到 TGA 图像格式中，简化转换过程，以提升在软件系统中的兼容性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


使用流加载图像来初始化 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 类的新实例。此构造函数允许无缝集成来自流的图像数据，促进在软件应用中高效处理和处理 TGA 图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


检索每像素位数值，提供有关图像色彩深度的关键信息。此属性是了解图像细节层次和色彩丰富度的重要指标，帮助开发者优化处理算法和资源分配，以实现高效的图像操作和渲染任务。

**Returns:**
int - 每像素位数。
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


获取每像素字节数值，表示图像中每个像素占用的内存量。此属性是内存管理和优化的重要指标，帮助开发者高效分配资源并处理图像数据。

**Returns:**
int - 每像素字节数。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


检索一个布尔值，以指示 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否包含 alpha 通道，从而实现透明效果。此属性提供处理图像合成和渲染的关键信息，帮助开发者实现多样的视觉效果和合成操作。

**Returns:**
boolean - 表示此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否具有 alpha 通道的值。
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


获取一个布尔值，以指示 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否为灰度图像。此属性对于区分彩色和灰度图像至关重要，帮助开发者根据图像的色彩特性采用适当的处理和渲染技术。

**Returns:**
boolean - 表示此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 是否为灰度的值。
### getWidth() {#getWidth--}
```
public int getWidth()
```


检索此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例所表示的图像宽度。此属性为开发者提供有关图像尺寸的关键信息，促进在软件应用中进行各种图像操作和处理任务。

**Returns:**
int - 此图像的像素宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例所封装的图像高度。此属性为开发者提供有关图像垂直尺寸的关键细节，支持在软件解决方案中无缝集成和操作图像。

**Returns:**
int - 此图像的像素高度。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取关于此实例的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 所表示图像的文件格式的关键信息。了解文件格式对于兼容性检查以及确保软件系统内的无缝集成至关重要，从而实现图像的高效处理和操作。

**Returns:**
long - 关于此实例的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 所表示图像的文件格式的关键信息。
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


检索此 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例是否包含颜色映射表。了解颜色映射表的存在对于准确解释和操作图像的颜色数据至关重要。

**Returns:**
boolean - 表示此图像是否具有颜色映射表的值。
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


获取伽马值的分子部分，这对于图像中准确的颜色表现至关重要。在没有伽马校正的图像中，此值应为 1.0。理解并使用该值对于保持颜色保真度并确保图像渲染的准确性至关重要。

**Returns:**
int - 伽马值的分子部分，这对于图像中准确的颜色表现至关重要。
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


检索伽马值的分母部分，这是决定图像颜色表现的关键因素。对于缺少伽马校正的图像，此值应为 1.0，以确保准确的颜色渲染。理解并利用该参数对于维护颜色保真度并实现精确的图像可视化至关重要。

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


获取像素宽高比的分子组件，它会影响图像中像素的视觉比例。理解并操作该值对于在图像渲染和处理时实现准确的像素表示和宽高比至关重要。

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


获取像素宽高比的分母部分，这是决定图像中像素视觉比例的关键因素。该值对于在各种图像渲染和处理操作中保持准确的像素表示和宽高比、确保高质量的视觉输出至关重要。

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


获取图像左下角的绝对水平坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。

**Returns:**
int - 绝对水平坐标，表示图像左下角在显示设备上（原点位于屏幕左下）的位置。
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


设置图像左下角的绝对水平坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 绝对水平坐标，表示图像左下角在显示设备上（原点位于屏幕左下）的位置。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


获取图像左下角的绝对垂直坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。

**Returns:**
int - 绝对垂直坐标，表示图像左下角在显示设备上（原点位于屏幕左下）的位置。
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


设置图像左下角的绝对垂直坐标，该坐标基于原点位于屏幕左下方的显示设备（例如 TARGA 系列）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 绝对垂直坐标，表示图像左下角在显示设备上（原点位于屏幕左下）的位置。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


获取与图像关联的唯一标识符。此 ID 用作在系统或应用程序中识别和区分图像的参考点。通过设置或获取 Image ID，您可以有效管理和跟踪图像，促进有序的图像管理和检索过程。

此可选字段包含图像的标识信息。该字段的最大长度为 255 字节。

**Returns:**
java.lang.String - 与图像关联的唯一标识符。
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


设置与图像关联的唯一标识符。此 ID 用作在系统或应用程序中识别和区分图像的参考点。通过设置或获取 Image ID，您可以有效管理和跟踪图像，促进有序的图像管理和检索过程。

此可选字段包含图像的标识信息。该字段的最大长度为 255 字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 与图像关联的唯一标识符。 |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


检索或设置图像作者提供的注释。这些注释通常包含有价值的信息，如描述、标注或图像的其他上下文。通过访问或修改 Author Comments 属性，开发者可以增强图像的元数据，为用户提供有关内容或创建的有价值的见解和上下文。此字段为 ASCII，长度为 324 字节，组织为四行每行 80 个字符，后跟空字符终止符。

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


检索或设置图像作者提供的注释。这些注释通常包含有价值的信息，如描述、标注或图像的其他上下文。通过访问或修改 Author Comments 属性，开发者可以增强图像的元数据，为用户提供有关内容或创建的有价值的见解和上下文。此字段为 ASCII，长度为 324 字节，组织为四行每行 80 个字符，后跟空字符终止符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


检索或设置与图像关联的作者名称。此属性允许开发者访问或修改作者名称元数据，提供有关图像创建者的有价值信息。通过使用 Author Name 属性，用户可以轻松识别创建或贡献该图像的个人，提升整体元数据并为观众提供有价值的上下文。该字段总计 40 个 ASCII 字符用于存放名称。如果使用此字段，应包含创建图像的人的姓名（作者）。

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


检索或设置与图像关联的作者名称。此属性允许开发者访问或修改作者名称元数据，提供有关图像创建者的有价值信息。通过使用 Author Name 属性，用户可以轻松识别创建或贡献该图像的个人，提升整体元数据并为观众提供有价值的上下文。该字段总计 40 个 ASCII 字符用于存放名称。如果使用此字段，应包含创建图像的人的姓名（作者）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 作者名称。 |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


获取日期/时间戳。此字段定义图像保存时的日期和时间值。尽管操作系统通常会为文件添加时间和日期戳，但提供此功能是因为操作系统在文件复制时可能会更改时间和日期戳。使用此区域，可确保日期和时间记录保持未修改的区域。

**Returns:**
java.util.Date - 日期/时间戳。
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


设置日期/时间戳。此字段定义图像保存时的日期和时间值。尽管操作系统通常会对文件进行时间和日期标记，但提供此功能是因为如果文件被复制，操作系统可能会更改时间和日期戳。使用此区域，可确保日期和时间记录保持未修改的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期/时间戳。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


检索或设置与图像关联的作业名称或 ID。此属性使您能够访问或修改与图像关联的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松识别图像所属的项目或任务，从而促进在更大工作流或项目中对图像资产的组织和管理。

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


检索或设置与图像关联的作业名称或 ID。此属性使您能够访问或修改与图像关联的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松识别图像所属的项目或任务，从而促进在更大工作流或项目中对图像资产的组织和管理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


检索或设置指示与图像关联的作业时间的时间戳。此属性允许开发人员访问或修改与图像关联的特定作业或项目的时间元数据。

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


检索或设置指示与图像关联的作业时间的时间戳。此属性允许开发人员访问或修改与图像关联的特定作业或项目的时间元数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


检索或设置与图像关联的关键颜色。此属性允许您访问或修改指定为特定图像处理任务或效果的关键颜色。使用关键颜色属性可让用户应用基于颜色的操作，如色度键控或颜色替换，提升图像操作能力和创意可能性。

关键颜色可以被视为 \\u2018背景颜色\\u2019 或 \\u2018透明颜色\\u2019。这是屏幕上 \\u2018非图像\\u2019 区域的颜色，也是如果在应用程序中擦除时屏幕将被清除到的相同颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


检索或设置与图像关联的关键颜色。此属性允许您访问或修改指定为特定图像处理任务或效果的关键颜色。使用关键颜色属性可让用户应用基于颜色的操作，如色度键控或颜色替换，提升图像操作能力和创意可能性。

关键颜色可以被视为 \\u2018背景颜色\\u2019 或 \\u2018透明颜色\\u2019。这是屏幕上 \\u2018非图像\\u2019 区域的颜色，也是如果在应用程序中擦除时屏幕将被清除到的相同颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 关键颜色。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


检索或设置一个布尔值，指示图像是否包含透明颜色。此属性对于识别图像是否支持透明度至关重要，帮助您实现适当的透明度相关操作处理，如混合、合成或遮罩。

**Returns:**
boolean - 一个指示图像是否具有透明颜色的值。
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


检索或设置一个布尔值，指示图像是否包含透明颜色。此属性对于识别图像是否支持透明度至关重要，帮助您实现适当的透明度相关操作处理，如混合、合成或遮罩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个指示图像是否具有透明颜色的值。 |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


检索或设置图像的背景颜色。此属性允许您指定用于图像背景的颜色，确保一致性并提升视觉呈现效果。它在图像显示在不同颜色背景上或将图像渲染到其他画布时尤为有用。

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


检索或设置图像的背景颜色。此属性允许您指定用于图像背景的颜色，确保一致性并提升视觉呈现效果。它在图像显示在不同颜色背景上或将图像渲染到其他画布时尤为有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


检索或设置一个值，指示图像是否包含背景颜色。此属性用于确定图像是否具有与前景内容分离的独特背景颜色。它使您能够根据是否存在背景颜色来自定义图像处理或渲染。

**Returns:**
boolean - 一个指示图像是否具有背景颜色的值。
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


检索或设置一个值，指示图像是否包含背景颜色。此属性用于确定图像是否具有与前景内容分离的独特背景颜色。它使您能够根据是否存在背景颜色来自定义图像处理或渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个指示图像是否具有背景颜色的值。 |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


检索或设置与图像关联的软件版本。版本字符串的接受长度通常为 3 到 4 个字符。此属性有助于跟踪用于创建或处理图像的软件，并可为图像处理和兼容性检查提供有价值的上下文。

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


检索或设置与图像关联的软件版本。版本字符串的接受长度通常为 3 到 4 个字符。此属性有助于跟踪用于创建或处理图像的软件，并可为图像处理和兼容性检查提供有价值的上下文。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


检索或设置与图像关联的软件版本的字母组件。此属性表示软件版本字符串中的附加细节，可用于更细致的版本区分。

**Returns:**
char - 软件版本字母部分。
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


检索或设置与图像关联的软件版本的字母组件。此属性表示软件版本字符串中的附加细节，可用于更细致的版本区分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char | 软件版本字母部分。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


检索或设置与图像关联的软件版本的数字组件。此属性表示软件版本字符串的数值部分，提供有关用于创建或修改图像的软件版本的重要信息。

**Returns:**
int - 软件版本数字部分。
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


检索或设置与图像关联的软件版本的数字组件。此属性表示软件版本字符串的数值部分，提供有关用于创建或修改图像的软件版本的重要信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 软件版本数字部分。 |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


管理与图像关联的软件标识（ID），最多可容纳 40 个 ASCII 字符。此属性用于唯一标识在创建或处理图像时使用的软件，为组织和信息目的提供有价值的元数据。

**Returns:**
java.lang.String - 软件 ID。
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


管理与图像关联的软件标识（ID），最多可容纳 40 个 ASCII 字符。此属性用于唯一标识在创建或处理图像时使用的软件，为组织和信息目的提供有价值的元数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 软件 ID。 |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


对两个 TGA 图像执行相等比较，考虑比较过程中涉及的第一张和第二张图像。此方法有助于直接评估图像是否相等，确保在图像处理工作流中进行准确的分析和决策。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 参与比较的第一张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 参与比较的第二张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |

**Returns:**
boolean - 比较结果。
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


对两个 TGA 图像执行非相等比较，评估比较中涉及的第一张和第二张图像。此方法有助于识别图像之间的差异或不一致，从而在图像处理任务中实现精确的分析和决策。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 参与比较的第一张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 参与比较的第二张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |

**Returns:**
boolean - 比较结果。
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


生成当前实例的副本，创建一个克隆原始所有属性和特性的新的对象。此方法有助于创建完全相同的拷贝，确保数据完整性并在不影响原始对象的情况下保留当前实例的状态。

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


复制另一个 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 对象的属性，创建一个具有相同属性的新实例。此操作确保数据完整性并促进图像属性的复制，而不更改源对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 其他 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


在相等比较中，方法评估当前的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例是否等于作为参数提供的第二张图像。此操作有助于确定两个 TGA 图像是否相同，支持图像处理和比较任务。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | 参与比较的第二张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |

**Returns:**
boolean - 比较结果。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


该方法在当前的 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) 实例与作为参数提供的另一个对象之间执行相等比较。具体而言，它评估当前图像的属性是否与第二个对象的属性匹配，帮助在图像处理工作流中确定它们的等价性以进行比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | java.lang.Object | 参与比较的第二张 [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)。 |

**Returns:**
boolean - 比较结果。
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


“rotateFlip” 方法启用对图像的旋转和翻转操作。它提供多功能的图像方向操作，允许用户根据需求执行旋转和翻转，从而在软件应用中促进高效的图像处理任务。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | int | 旋转翻转类型。 |

### hashCode() {#hashCode--}
```
public int hashCode()
```


检索当前实例的哈希码。但需注意，此哈希码可能不适合作为键使用，特别是因为 TgaImage 类的实例不是不可变的。

**Returns:**
int - 此实例的哈希码。
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


将图像裁剪到指定区域。此方法允许您定义图像中要保留的矩形区域，丢弃其余部分。此操作有助于聚焦图像的特定内容或去除不需要的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


通过指定左、右、上、下边界的位移来裁剪图像。此方法允许您通过在水平和垂直轴上独立移动边界来修剪图像。通过调整这些位移，您可以精确控制保留图像的哪些部分，从而有效地将其裁剪到所需的尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | int | 左位移。 |
| rightShift | int | 右位移。 |
| topShift | int | 上位移。 |
| bottomShift | int | 下位移。 |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


在应用特定设置以保持所需尺寸和宽高比的同时调整图像大小。通过自定义图像设置，您可以有效地调整图像大小，同时确保最佳的视觉质量以及与不同显示设备或应用程序的兼容性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小的设置。 |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


使用指定的调整大小类型来调整图像的尺寸，该类型决定了调整大小操作的执行方式。此方法提供了根据不同算法或技术对图像进行调整的灵活性。通过选择合适的调整大小类型，您可以根据具体需求或偏好，在图像质量和计算效率之间实现所需的平衡。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新的宽度。 |
| newHeight | int | 新的高度。 |
| resizeType | int | 调整大小类型。 |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


围绕图像中心以指定角度旋转图像，同时保持调整大小的比例并保留背景颜色。此方法实现了精确的图像操作，确保旋转后保持视觉平衡并与指定的背景颜色保持一致。它非常适用于需要围绕中心精确旋转的任务，例如方向校正或艺术调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度，以度为单位。正值将顺时针旋转。 |
| resizeProportionally | boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅 `` 图像内容被旋转。 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景的颜色。 |

