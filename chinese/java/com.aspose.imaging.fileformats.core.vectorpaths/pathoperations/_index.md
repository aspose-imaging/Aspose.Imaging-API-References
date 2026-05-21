---
title: "PathOperations"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "路径形状的布尔运算操作。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.core.vectorpaths/pathoperations/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PathOperations extends System.Enum
```

路径形状组合（布尔运算）的操作。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ExcludeOverlappingShapes](#ExcludeOverlappingShapes) | 排除重叠形状（XOR 操作）。 |
| [CombineShapes](#CombineShapes) | 合并形状（OR 操作）。 |
| [SubtractFrontShape](#SubtractFrontShape) | 减去前置形状（NOT 操作）。 |
| [IntersectShapeAreas](#IntersectShapeAreas) | 相交形状区域（AND 操作）。 |
### ExcludeOverlappingShapes {#ExcludeOverlappingShapes}
```
public static final int ExcludeOverlappingShapes
```


排除重叠形状（XOR 操作）。

### CombineShapes {#CombineShapes}
```
public static final int CombineShapes
```


合并形状（OR 操作）。这是 Photoshop 中的默认值。

### SubtractFrontShape {#SubtractFrontShape}
```
public static final int SubtractFrontShape
```


减去前置形状（NOT 操作）。

### IntersectShapeAreas {#IntersectShapeAreas}
```
public static final int IntersectShapeAreas
```


相交形状区域（AND 操作）。

