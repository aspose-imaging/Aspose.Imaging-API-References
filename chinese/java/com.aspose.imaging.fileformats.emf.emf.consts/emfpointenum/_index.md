---
title: "EmfPointEnum"
second_title: "Aspose.Imaging for Java API 参考"
description: "Point 枚举用于指定在绘图调用中点的使用方式。"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

Point 枚举用于指定在绘图调用中点的使用方式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | 可以使用位运算符 OR 将 PT\_LINETO 或 PT\_BEZIERTO 类型与此值组合，以指示相应的点是图形中的最后一点且图形已闭合 |
| [PT_LINETO](#PT-LINETO) | 指定从当前坐标绘制一条线到此点，随后此点成为新的当前坐标 |
| [PT_BEZIERTO](#PT-BEZIERTO) | 指定此点是贝塞尔曲线的控制点或结束点。 |
| [PT_MOVETO](#PT-MOVETO) | 指定此点开始一个不相连的图形。 |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


可以使用位运算符 OR 将 PT\_LINETO 或 PT\_BEZIERTO 类型与此值组合，以指示相应的点是图形中的最后一点且图形已闭合

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


指定从当前坐标绘制一条线到此点，随后此点成为新的当前坐标

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


指定此点是贝塞尔曲线的控制点或结束点。

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


指定此点开始一个不相连的图形。此点成为新的当前坐标。

