---
title: "FeatheringSettings"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "羽化设置类。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

羽化设置类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | 初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取羽化大小。 |
| [setSize(int value)](#setSize-int-) | 设置羽化大小。 |
| [getMode()](#getMode--) | 获取羽化算法模式。 |
| [setMode(int value)](#setMode-int-) | 设置羽化算法模式。 |

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

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


初始化一个新的 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 类实例。

### getSize() {#getSize--}
```
public final int getSize()
```


获取羽化大小。

值：羽化画笔的大小（像素）。

**Returns:**
int - 羽化大小。
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


设置羽化大小。

值：羽化画笔的大小（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 羽化大小。 |

### getMode() {#getMode--}
```
public final int getMode()
```


获取羽化算法模式。

值：羽化算法模式。

**Returns:**
int - 羽化算法模式。
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


设置羽化算法模式。

值：羽化算法模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 羽化算法模式。 |

