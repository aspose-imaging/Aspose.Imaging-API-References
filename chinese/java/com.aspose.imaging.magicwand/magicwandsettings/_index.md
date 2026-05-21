---
title: "MagicWandSettings"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Magic Wand 选择设置类。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Magic Wand 选择设置类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | 初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。 |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | 初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | 获取算法工作区域的边界。 |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | 设置算法工作区域的边界。 |
| [getPoint()](#getPoint--) | 获取算法工作参考点。 |
| [getThreshold()](#getThreshold--) | 获取像素颜色比较的容差水平。 |
| [setThreshold(int value)](#setThreshold-int-) | 设置像素颜色比较的容差水平。 |
| [getContiguousMode()](#getContiguousMode--) | 获取一个值，指示魔棒是否仅定义连续像素。 |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | 设置一个值，指示魔棒是否仅定义连续像素。 |
| [getDirectionalMode()](#getDirectionalMode--) | 获取填充搜索算法的模式：四方向或八方向搜索。 |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | 设置填充搜索算法的模式：四方向或八方向搜索。 |
| [getColorCompareMode()](#getColorCompareMode--) | 获取颜色比较的算法。 |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | 设置颜色比较的算法。 |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | 获取自定义颜色比较算法（如果 `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) 被设置为 [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom)）。 |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | 设置自定义颜色比较算法（如果 `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) 被设置为 [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom)）。 |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // 使用魔棒工具基于像素 (120, 100) 的色调和颜色创建新掩码，自定义阈值为 150。
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // 将掩码应用于图像
            .apply();

    // 保存图像并强制使用透明颜色类型选项
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // 使用魔棒工具基于像素 (845, 128) 的色调和颜色创建新掩码
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // 将现有掩码与由魔棒工具创建的指定掩码合并
            .union(new MagicWandSettings(416, 387))
            // 反转现有掩码
            .invert()
            // 从现有掩码中减去由魔棒工具创建的、具有指定阈值的指定掩码
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // 逐个从现有掩码中减去四个指定的矩形掩码
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // 使用指定设置羽化掩码
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // 将掩码应用于图像
            .apply();

    // 保存图像
    image.save(outputFilePath);
}

```

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 参考点。 |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 参考点的 x 坐标。 |
| y | int | 参考点的 y 坐标。 |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


获取算法工作区域的边界。

值：表示感兴趣区域边界的矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


设置算法工作区域的边界。

值：表示感兴趣区域边界的矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | 算法工作区域的边界。 |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


获取算法工作参考点。

值：`Point` 值。

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


获取像素颜色比较的容差水平。

值：颜色比较的阈值。

**Returns:**
int - 像素颜色比较的容差级别。
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


设置像素颜色比较的容差水平。

值：颜色比较的阈值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 像素颜色比较的容差级别。 |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


获取一个值，指示魔棒是否仅定义连续像素。

值：如果元素已启用则为 `true`；否则为 `false`。默认值为 `true`。

**Returns:**
boolean - 指示魔棒是否仅定义连续像素的值。
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


设置一个值，指示魔棒是否仅定义连续像素。

值：如果元素已启用则为 `true`；否则为 `false`。默认值为 `true`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示魔棒是否仅定义连续像素的值。 |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


获取填充搜索算法的模式：四方向或八方向搜索。

值：填充搜索算法的模式。

**Returns:**
int - 填充搜索算法的模式：四方向或八方向搜索。
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


设置填充搜索算法的模式：四方向或八方向搜索。

值：填充搜索算法的模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 填充搜索算法的模式：四方向或八方向搜索。 |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


获取颜色比较的算法。

值：颜色比较模式。

**Returns:**
int - 颜色比较的算法。
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


设置颜色比较的算法。

值：颜色比较模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 颜色比较的算法。 |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


获取自定义颜色比较算法（如果 `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) 被设置为 [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom)）。

值：颜色比较委托。

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


设置自定义颜色比较算法（如果 `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) 被设置为 [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom)）。

值：颜色比较委托。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | 如果 `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) 设置为 [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom)，则使用自定义颜色比较算法。 |

