---
title: "EmfStretchMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "StretchMode 枚举用于指定在拉伸或压缩位图时，如何添加或移除颜色数据。"
type: docs
weight: 43
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

StretchMode 枚举用于指定在拉伸或压缩位图时，如何添加或移除颜色数据。
## 字段

| 字段 | 描述 |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | 使用已消除和现有像素的颜色值执行布尔 AND 操作。 |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | 使用已消除和现有像素的颜色值执行布尔 OR 操作。 |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | 删除像素。 |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | 将像素从源矩形映射到目标矩形中的像素块。 |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


使用已消除和现有像素的颜色值执行布尔 AND 操作。如果位图是单色位图，此模式会以牺牲白色像素为代价保留黑色像素。

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


使用已消除和现有像素的颜色值执行布尔 OR 操作。如果位图是单色位图，此模式会以牺牲黑色像素为代价保留白色像素。

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


删除像素。此模式会删除所有已消除的像素线，而不尝试保留其信息。

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


将像素从源矩形映射到目标矩形中的像素块。目标像素块的平均颜色近似于源像素的颜色。

