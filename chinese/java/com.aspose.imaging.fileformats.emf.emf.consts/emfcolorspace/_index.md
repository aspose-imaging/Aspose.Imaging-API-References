---
title: "EmfColorSpace"
second_title: "Aspose.Imaging for Java API 参考"
description: "ColorSpace 枚举用于指定何时开启或关闭颜色校样以及何时删除变换。"
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
| [CS_DISABLE](#CS-DISABLE) | 禁用颜色校样。 |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | 如果为目标配置文件启用了颜色管理，则将其禁用并删除串联的变换。 |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


将颜色映射到目标设备的色域。这会启用颜色校样。所有后续对播放设备上下文的绘制命令都将以目标设备的显示方式渲染颜色。

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


禁用颜色校样。

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


如果为目标配置文件启用了颜色管理，则将其禁用并删除串联的变换。

