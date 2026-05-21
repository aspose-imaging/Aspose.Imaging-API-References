---
title: "EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ModifyWorldTransformMode 枚举定义了使用指定的变换数据来修改当前在回放设备上下文中定义的世界空间到页面空间变换的模式。"
type: docs
weight: 33
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

ModifyWorldTransformMode 枚举定义了使用指定的变换数据来修改当前在回放设备上下文中定义的世界空间到页面空间变换的模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | 使用单位矩阵重置当前变换。 |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | 对当前变换进行相乘。 |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | 对当前变换进行相乘。 |
| [MWT_SET](#MWT-SET) | 执行 EMR\\_SETWORLDTRANSFORM 记录的功能（章节 2.3.12.2）。 |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


使用单位矩阵重置当前变换。在此模式下，指定的变换数据将被忽略。

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


对当前变换进行乘法。在此模式下，指定的变换数据是左乘数，而播放设备上下文中当前定义的变换是右乘数。

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


对当前变换进行乘法。在此模式下，指定的变换数据是右乘数，而播放设备上下文中当前定义的变换是左乘数。

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


执行 EMR\\_SETWORLDTRANSFORM 记录的功能（章节 2.3.12.2）。

