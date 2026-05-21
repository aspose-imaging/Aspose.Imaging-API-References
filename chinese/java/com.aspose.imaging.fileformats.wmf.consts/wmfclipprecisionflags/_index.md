---
title: "WmfClipPrecisionFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "ClipPrecision 标志指定剪裁精度，定义如何剪裁部分位于剪裁区域外的字符。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

ClipPrecision 标志指定剪裁精度，定义如何剪裁部分位于剪裁区域外的字符。这些标志可以组合以指定多个选项。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | 指定必须使用默认剪裁。 |
| [Character](#Character) | 不应使用此值。 |
| [Stroke](#Stroke) | 在枚举光栅化、TrueType 和矢量字体时，可能返回此值。 |
| [LhAngles](#LhAngles) | 此值用于控制字体旋转，规则如下：- 如果设置，则所有字体的旋转应由坐标系的方向决定；即方向是左手坐标系还是右手坐标系。 |
| [TtAlways](#TtAlways) | 不应使用此值 [34]。 |
| [DfaDisable](#DfaDisable) | 此值指定应关闭字体关联 [35]。 |
| [Embedded](#Embedded) | 此值指定必须使用字体嵌入来呈现文档内容；嵌入的字体为只读。 |
### Default {#Default}
```
public static final byte Default
```


指定必须使用默认剪裁。

### Character {#Character}
```
public static final byte Character
```


不应使用此值。

### Stroke {#Stroke}
```
public static final byte Stroke
```


在枚举光栅化、TrueType 和矢量字体时，可能返回此值。[33]（Windows NT 3.1、Windows NT 3.5、Windows NT 3.51、Windows NT 4.0、Windows 2000 和 Windows XP：枚举字体时始终返回此值。）

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


此值用于控制字体旋转，规则如下：- 如果设置，则所有字体的旋转应由坐标系的方向决定；即方向是左手坐标系还是右手坐标系。- 如果清除，则设备字体应逆时针旋转，但其他字体的旋转应由坐标系的方向决定。

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


不应使用此值 [34]。此值在以下 Windows 版本中被忽略：- Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


此值指定应关闭字体关联 [35]。此值在 Windows 95、Windows 98 和 Windows Millennium Edition 中不受支持。字体关联在 Windows 2000、Windows XP 和 Windows Server 2003 中被关闭。此值在以下 Windows 版本中被忽略：- Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


此值指定必须使用字体嵌入来呈现文档内容；嵌入的字体为只读。

