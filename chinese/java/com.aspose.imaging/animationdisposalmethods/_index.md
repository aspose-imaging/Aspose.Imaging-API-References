---
title: "AnimationDisposalMethods"
second_title: "Aspose.Imaging for Java API 参考"
description: "指示图形显示后应如何处理。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging/animationdisposalmethods/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnimationDisposalMethods extends System.Enum
```

指示图形显示后应如何处理。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PRESERVE](#PRESERVE) | 不要释放。 |
| [BACKGROUND](#BACKGROUND) | 恢复到背景颜色。 |
| [PREVIOUS](#PREVIOUS) | 恢复到之前的状态。 |
### PRESERVE {#PRESERVE}
```
public static final int PRESERVE
```


不要释放。图形应保持原位。

### BACKGROUND {#BACKGROUND}
```
public static final int BACKGROUND
```


恢复到背景颜色。图形使用的区域必须恢复为背景颜色。

### PREVIOUS {#PREVIOUS}
```
public static final int PREVIOUS
```


恢复到之前的状态。解码器需要将被图形覆盖的区域恢复为渲染图形之前的内容。

