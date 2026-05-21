---
title: "EmfColorSpace"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ColorSpace 枚举用于指定何时打开或关闭颜色校对以及何时删除转换。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

ColorSpace 枚举用于指定何时开启或关闭颜色校样，以及何时删除变换。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | 将颜色映射到目标设备的色域。 |
| [CS_DISABLE](#CS-DISABLE) | 禁用颜色校对。 |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | 如果已为目标配置文件启用颜色管理，则禁用它并删除串联的转换。 |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


将颜色映射到目标设备的色域。这会启用颜色校对。所有后续对播放设备上下文的绘制命令将以目标设备上显示的方式渲染颜色。

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


禁用颜色校对。

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


如果已为目标配置文件启用颜色管理，则禁用它并删除串联的转换。

