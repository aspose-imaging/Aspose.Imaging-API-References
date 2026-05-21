---
title: "StretchMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该枚举指定位图拉伸模式，定义系统如何将位图的行或列与现有像素合并。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

该 [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) 枚举指定位图拉伸模式，定义系统如何将位图的行或列与现有像素合并。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | 使用已消除像素和现有像素的颜色值执行布尔 AND 操作。 |
| [WhiteOnBlack](#WhiteOnBlack) | 使用已消除像素和现有像素的颜色值执行布尔 OR 操作。 |
| [ColorOnColor](#ColorOnColor) | 删除像素。 |
| [HalfTone](#HalfTone) | 将像素从源矩形映射到目标矩形中的像素块。 |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


使用已消除像素和现有像素的颜色值执行布尔 AND 操作。如果位图是单色位图，此模式会以牺牲白色像素为代价保留黑色像素。

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


使用已消除像素和现有像素的颜色值执行布尔 OR 操作。如果位图是单色位图，此模式会以牺牲黑色像素为代价保留白色像素。

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


删除像素。 此模式会删除所有被消除的像素行，而不尝试保留其信息。

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


将像素从源矩形映射到目标矩形中的像素块。 目标像素块的平均颜色近似于源像素的颜色。

