---
title: "DisposalMethod"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指示图形显示后应如何处理。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.gif/disposalmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DisposalMethod extends System.Enum
```

指示图形显示后应如何处理。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 未指定处理方式。 |
| [Preserve](#Preserve) | 不要处理。 |
| [Restore](#Restore) | 恢复为背景颜色。 |
| [Previuos](#Previuos) | 恢复到先前状态。 |
| [Undefined](#Undefined) | 未定义的值。 |
### None {#None}
```
public static final int None
```


未指定处理方式。

### Preserve {#Preserve}
```
public static final int Preserve
```


不要处理。图形保持原位。

### Restore {#Restore}
```
public static final int Restore
```


恢复为背景颜色。图形占用的区域必须恢复为背景颜色。

### Previuos {#Previuos}
```
public static final int Previuos
```


恢复到先前状态。解码器需要将图形覆盖的区域恢复为渲染图形之前的内容。

### Undefined {#Undefined}
```
public static final int Undefined
```


未定义的值。

