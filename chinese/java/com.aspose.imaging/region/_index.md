---
title: "Region"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述由矩形和路径组成的图形形状的内部。"
type: docs
weight: 95
url: /zh/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

描述 由矩形和路径组成的图形形状的内部。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Region()](#Region--) | 初始化一个新的 Region。 |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | 从指定的 `T:Aspose.Imaging.RectangleF` 结构初始化一个新的 `T:Aspose.Imaging.Region`。 |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | 从指定的 `T:Aspose.Imaging.Rectangle` 结构初始化一个新的 `T:Aspose.Imaging.Region`。 |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | 使用指定的 `T:Aspose.Imaging.GraphicsPath` 初始化一个新的 `T:Aspose.Imaging.Region`。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此 `com.aspose.imaging.region` 的精确深拷贝。 |
| [makeInfinite()](#makeInfinite--) | 初始化此 `com.aspose.imaging.Region` 为无限内部。 |
| [makeEmpty()](#makeEmpty--) | 初始化此 `com.aspose.imaging.Region` 为空内部。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的交集。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.Rectangle` 结构的交集。 |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.graphicsPath` 的交集。 |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.region` 的交集。 |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的并集。 |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.Rectangle` 结构的并集。 |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.graphicsPath` 的并集。 |
| [union(Region region)](#union-com.aspose.imaging.Region-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.region` 的并集。 |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | 将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的并集减去交集。 |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | 将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.Rectangle` 结构的并集减去交集。 |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | 将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.graphicsPath` 的并集减去交集。 |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | 将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.region` 的并集减去交集。 |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | 将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.RectangleF` 结构不相交的部分。 |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | 将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.Rectangle` 结构不相交的部分。 |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | 将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.graphicsPath` 不相交的部分。 |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | 将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.region` 不相交的部分。 |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | 将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.RectangleF` 结构中不与此 `com.aspose.imaging.region` 相交的部分。 |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | 将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.Rectangle` 结构中不与此 `com.aspose.imaging.region` 相交的部分。 |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | 将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.GraphicsPath` 中不与此 `com.aspose.imaging.region` 相交的部分。 |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | 将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.Region` 中不与此 `com.aspose.imaging.region` 相交的部分。 |
| [translate(float dx, float dy)](#translate-float-float-) | 按指定的量偏移此 `com.aspose.imaging.Region` 的坐标。 |
| [translate(int dx, int dy)](#translate-int-int-) | 按指定的量偏移此 `com.aspose.imaging.Region` 的坐标。 |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | 使用指定的 `com.aspose.imaging.matrix` 对此 `com.aspose.imaging.Region` 进行变换。 |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | 测试此 `com.aspose.imaging.Region` 在指定的绘图表面上是否具有空的内部。 |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | 测试此 `com.aspose.imaging.Region` 在指定的绘图表面上是否具有无限的内部。 |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | 测试指定的 `com.aspose.imaging.Region` 在指定的绘图表面上是否与此 `com.aspose.imaging.Region` 完全相同。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 测试指定的点是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | 测试指定的 `com.aspose.imaging.PointF` 结构是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的点是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的 `com.aspose.imaging.PointF` 结构是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | 测试指定的 `com.aspose.imaging.RectangleF` 结构的任何部分是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的 `com.aspose.imaging.RectangleF` 结构的任何部分是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.Graphics` 对象绘制时，测试指定的点是否包含在此 `com.aspose.imaging.Region` 对象中。 |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | 测试指定的 `com.aspose.imaging.Point` 结构是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | 测试在使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的 `com.aspose.imaging.Point` 结构是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | 测试指定的 `com.aspose.imaging.Rectangle` 结构的任何部分是否包含在此 `com.aspose.imaging.region` 中。 |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | 在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.Region` 中。 |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | 测试在使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的 `com.aspose.imaging.Rectangle` 结构的任何部分是否包含在此 `com.aspose.imaging.Region` 中。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### Region() {#Region--}
```
public Region()
```


初始化一个新的 Region。

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


从指定的 `T:Aspose.Imaging.RectangleF` 结构初始化一个新的 `T:Aspose.Imaging.Region`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `T:Aspose.Imaging.RectangleF` 结构，定义新 `T:Aspose.Imaging.Region` 的内部。 |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


从指定的 `T:Aspose.Imaging.Rectangle` 结构初始化一个新的 `T:Aspose.Imaging.Region`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `T:Aspose.Imaging.Rectangle` 结构，定义新 `T:Aspose.Imaging.Region` 的内部。 |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


使用指定的 `T:Aspose.Imaging.GraphicsPath` 初始化一个新的 `T:Aspose.Imaging.Region`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `T:Aspose.Imaging.GraphicsPath`，定义新的 `T:Aspose.Imaging.Region`。 |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


创建此 `com.aspose.imaging.region` 的精确深拷贝。

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


初始化此 `com.aspose.imaging.Region` 为无限内部。

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


初始化此 `com.aspose.imaging.Region` 为空内部。

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 用于与此 `com.aspose.imaging.region` 求交的 `com.aspose.imaging.RectangleF` 结构。 |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.Rectangle` 结构的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于与此 `com.aspose.imaging.region` 求交的 `com.aspose.imaging.Rectangle` 结构。 |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.graphicsPath` 的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 用于与此 `com.aspose.imaging.region` 求交的 `com.aspose.imaging.GraphicsPath`。 |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.region` 的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 用于与此 `com.aspose.imaging.region` 求交的 `com.aspose.imaging.Region`。 |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 用于与此 `com.aspose.imaging.region` 合并的 `com.aspose.imaging.RectangleF` 结构。 |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.Rectangle` 结构的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于与此 `com.aspose.imaging.region` 合并的 `com.aspose.imaging.Rectangle` 结构。 |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.graphicsPath` 的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 用于与此 `com.aspose.imaging.region` 合并的 `com.aspose.imaging.GraphicsPath`。 |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.region` 的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 用于与此 `com.aspose.imaging.region` 合并的 `com.aspose.imaging.Region`。 |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


将此 `com.aspose.imaging.Region` 更新为其自身与指定的 `com.aspose.imaging.RectangleF` 结构的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 用于与此 `com.aspose.imaging.region` 进行异或的 `com.aspose.imaging.RectangleF` 结构。 |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.Rectangle` 结构的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于与此 `com.aspose.imaging.region` 进行异或的 `com.aspose.imaging.Rectangle` 结构。 |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.graphicsPath` 的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 用于与此 `com.aspose.imaging.region` 进行异或的 `com.aspose.imaging.GraphicsPath`。 |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


将此 `com.aspose.imaging.Region` 更新为它自身与指定的 `com.aspose.imaging.region` 的并集减去交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 用于与此 `com.aspose.imaging.region` 进行异或的 `com.aspose.imaging.Region`。 |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.RectangleF` 结构不相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 用于从此 `com.aspose.imaging.region` 中排除的 `com.aspose.imaging.RectangleF` 结构。 |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.Rectangle` 结构不相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于从此 `com.aspose.imaging.region` 中排除的 `com.aspose.imaging.Rectangle` 结构。 |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.graphicsPath` 不相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 用于从此 `com.aspose.imaging.region` 中排除的 `com.aspose.imaging.GraphicsPath`。 |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


将此 `com.aspose.imaging.Region` 更新为仅包含其内部与指定的 `com.aspose.imaging.region` 不相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 用于从此 `com.aspose.imaging.region` 中排除的 `com.aspose.imaging.Region`。 |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.RectangleF` 结构中不与此 `com.aspose.imaging.region` 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 用于补充此 `com.aspose.imaging.region` 的 `com.aspose.imaging.RectangleF` 结构。 |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.Rectangle` 结构中不与此 `com.aspose.imaging.region` 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于补充此 `com.aspose.imaging.region` 的 `com.aspose.imaging.Rectangle` 结构。 |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.GraphicsPath` 中不与此 `com.aspose.imaging.region` 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 用于补充此 `com.aspose.imaging.region` 的 `com.aspose.imaging.GraphicsPath`。 |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


将此 `com.aspose.imaging.Region` 更新为包含指定的 `com.aspose.imaging.Region` 中不与此 `com.aspose.imaging.region` 相交的部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 用于补充此 `com.aspose.imaging.Region` 对象的 `com.aspose.imaging.Region` 对象。 |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


按指定的量偏移此 `com.aspose.imaging.Region` 的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | float | 此 `com.aspose.imaging.Region` 水平偏移的量。 |
| dy | float | 此 `com.aspose.imaging.Region` 垂直偏移的量。 |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


按指定的量偏移此 `com.aspose.imaging.Region` 的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | int | 此 `com.aspose.imaging.Region` 水平偏移的量。 |
| dy | int | 此 `com.aspose.imaging.Region` 垂直偏移的量。 |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


使用指定的 `com.aspose.imaging.matrix` 对此 `com.aspose.imaging.Region` 进行变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于转换此 `com.aspose.imaging.region` 的 `com.aspose.imaging.Matrix`。 |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


测试此 `com.aspose.imaging.Region` 在指定的绘图表面上是否具有空的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示绘图表面的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 如果在应用与 `g` 关联的变换时此 `com.aspose.imaging.Region` 的内部为空，则为 true；否则为 false。
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


测试此 `com.aspose.imaging.Region` 在指定的绘图表面上是否具有无限的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示绘图表面的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 如果在应用与 `g` 关联的变换时此 `com.aspose.imaging.Region` 的内部是无限的，则为 true；否则为 false。
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


测试指定的 `com.aspose.imaging.Region` 在指定的绘图表面上是否与此 `com.aspose.imaging.Region` 完全相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 要测试的 `com.aspose.imaging.Region`。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示绘图表面的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 如果在应用与 `g` 参数关联的变换时 region 的内部与此 region 的内部相同，则为 True；否则为 false。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


测试指定的点是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns:**
布尔值 - 当指定的点位于此 `com.aspose.imaging.Region` 内部时为 True；否则为 false。
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


测试指定的 `com.aspose.imaging.PointF` 结构是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要测试的 `com.aspose.imaging.PointF` 结构。 |

**Returns:**
布尔值 - 当 `point` 位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的点是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当指定的点位于此 `com.aspose.imaging.Region` 内部时为 True；否则为 false。
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的 `com.aspose.imaging.PointF` 结构是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要测试的 `com.aspose.imaging.PointF` 结构。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当 `point` 位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | float | 要测试的矩形的宽度。 |
| 高度 | float | 要测试的矩形的高度。 |

**Returns:**
布尔值 - 当指定矩形的任何部分位于此 `com.aspose.imaging.Region` 对象内部时为 true；否则为 false。
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


测试指定的 `com.aspose.imaging.RectangleF` 结构的任何部分是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要测试的 `com.aspose.imaging.RectangleF` 结构。 |

**Returns:**
布尔值 - 当 `rect` 的任何部分位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | float | 要测试的矩形的宽度。 |
| 高度 | float | 要测试的矩形的高度。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当指定矩形的任何部分位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定的 `com.aspose.imaging.RectangleF` 结构的任何部分是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要测试的 `com.aspose.imaging.RectangleF` 结构。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当 `rect` 位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


在使用指定的 `com.aspose.imaging.Graphics` 对象绘制时，测试指定的点是否包含在此 `com.aspose.imaging.Region` 对象中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔 - 当指定的点位于此 `com.aspose.imaging.Region` 中时为 true；否则为 false。
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


测试指定的 `com.aspose.imaging.Point` 结构是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要测试的 `com.aspose.imaging.Point` 结构。 |

**Returns:**
布尔值 - 当 `point` 位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


测试在使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的 `com.aspose.imaging.Point` 结构是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要测试的 `com.aspose.imaging.Point` 结构。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当 `point` 位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | int | 要测试的矩形的宽度。 |
| 高度 | int | 要测试的矩形的高度。 |

**Returns:**
布尔值 - 当指定矩形的任何部分位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


测试指定的 `com.aspose.imaging.Rectangle` 结构的任何部分是否包含在此 `com.aspose.imaging.region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 要测试的 `com.aspose.imaging.Rectangle` 结构。 |

**Returns:**
布尔 - 当 `rect` 的任何部分位于此 `com.aspose.imaging.Region` 内时，此方法返回 true；否则返回 false。
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


在使用指定的 `com.aspose.imaging.graphics` 绘制时，测试指定矩形的任何部分是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | int | 要测试的矩形的宽度。 |
| 高度 | int | 要测试的矩形的高度。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔值 - 当指定矩形的任何部分位于此 `com.aspose.imaging.Region` 内部时为 true；否则为 false。
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


测试在使用指定的 `com.aspose.imaging.graphics` 绘制时，指定的 `com.aspose.imaging.Rectangle` 结构的任何部分是否包含在此 `com.aspose.imaging.Region` 中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 要测试的 `com.aspose.imaging.Rectangle` 结构。 |
| g | [Graphics](../../com.aspose.imaging/graphics) | 一个表示图形上下文的 `com.aspose.imaging.Graphics`。 |

**Returns:**
布尔 - 当 `rect` 的任何部分位于此 `com.aspose.imaging.Region` 中时为 true；否则为 false。
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
