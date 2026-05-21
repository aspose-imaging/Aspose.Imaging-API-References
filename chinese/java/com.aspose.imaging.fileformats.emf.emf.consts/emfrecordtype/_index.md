---
title: "EmfRecordType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "RecordType 枚举定义了唯一标识 EMF 记录的取值。"
type: docs
weight: 38
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

RecordType 枚举定义了唯一标识 EMF 记录的值。这些值在每个记录的 Type 字段中提供。
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | 此记录定义了元文件的开始并指定其特性；其内容，包括嵌入图像的尺寸；元文件中的记录数；以及创建嵌入图像的设备分辨率。 |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | 此记录定义一个或多个贝塞尔曲线。 |
| [EMR_POLYGON](#EMR-POLYGON) | 此记录定义一个由两个或多个顶点通过直线连接组成的多边形。 |
| [EMR_POLYLINE](#EMR-POLYLINE) | 此记录通过连接指定数组中的点来定义一系列线段。 |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | 此记录基于当前位置信息定义一个或多个贝塞尔曲线。 |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | 此记录基于当前位置信息定义一个或多个直线。 |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | 此记录定义多个相连线段的系列。 |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | 此记录定义一系列闭合多边形。 |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | 此记录定义窗口范围。 |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | 此记录定义窗口原点。 |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | 此记录定义视口范围。 |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | 此记录定义视口原点。 |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | 此记录定义当前画刷的原点。 |
| [EMR_EOF](#EMR-EOF) | 此记录指示元文件的结束。 |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | 此记录定义指定逻辑坐标处像素的颜色。 |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | 此记录指定将逻辑字体匹配到物理字体的过程参数，该过程由字体映射器执行。 |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | 此记录定义回放设备上下文的映射模式。 |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | 此记录定义回放设备上下文的背景混合模式。 |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | 此记录定义多边形填充模式。 |
| [EMR_SETROP2](#EMR-SETROP2) | 此记录定义二进制光栅操作模式。 |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | 此记录定义位图拉伸模式。 |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | 此记录定义文本对齐方式。 |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | 此记录使用指定的值定义回放设备上下文的颜色调整值。 |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | 此记录定义当前文本颜色。 |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | 此记录定义背景颜色。 |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | 此记录通过指定的偏移量重新定义回放设备上下文的裁剪区域。 |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | 此记录以逻辑单位定义新当前位置的坐标。 |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | 此记录将回放设备上下文的当前裁剪区域与当前元区域相交，并将组合后的区域保存为新的元区域。 |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | 此记录定义一个新裁剪区域，该区域由现有裁剪区域减去指定的矩形组成。 |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | 此记录通过当前裁剪区域与指定矩形的交集定义一个新裁剪区域。 |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | 此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的视口。 |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | 此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的窗口。 |
| [EMR_SAVEDC](#EMR-SAVEDC) | 此记录通过复制描述所选对象和图形模式的数据显示\u2014包括位图、画刷、调色板、字体、画笔、区域、绘图模式和映射模式\u2014到已保存设备上下文的堆栈中，以保存回放设备上下文的当前状态。 |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | 此记录将回放设备上下文恢复到指定的已保存状态。 |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | 此记录为回放设备上下文定义世界空间与页面空间之间的二维线性变换（有关更多信息，请参阅[MSDN-WRLDPGSPC]）。 |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | 此记录使用指定模式重新定义回放设备上下文的世界变换。 |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | 此记录向回放设备上下文添加对象，并通过其在 EMF 对象表（第 3.1.1.1 节）中的索引进行标识。 |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | 此记录定义具有指定样式、宽度和颜色的逻辑笔。 |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | 此记录定义用于图形操作中填充图形的逻辑画刷。 |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | 此记录删除图形对象，并清除其在 EMF 对象表中的索引。 |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | 此记录定义弧线的线段。 |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | 此记录定义椭圆。 |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | 此记录定义矩形。 |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | 此记录定义带圆角的矩形。 |
| [EMR_ARC](#EMR-ARC) | 此记录定义椭圆弧。 |
| [EMR_CHORD](#EMR-CHORD) | 此记录定义了一个弦（由椭圆与线段的交点界定的区域，称为割线）。 |
| [EMR_PIE](#EMR-PIE) | 此记录定义了一个饼形楔形，由椭圆与两条径向线的交点界定。 |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | 此记录向回放设备上下文添加一个 LogPalette（第 2.2.17 节）对象，并通过其在 EMF 对象表中的索引进行标识。 |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | 此记录定义了一个 LogPalette 对象。 |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | 此记录在 LogPalette 对象的若干条目范围内定义 RGB（红绿蓝）颜色值。 |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | 此记录增大或减小逻辑调色板的大小。 |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | 此记录将当前逻辑调色板的条目映射到系统调色板。 |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | 此记录使用当前画笔填充显示表面的一个区域。 |
| [EMR_LINETO](#EMR-LINETO) | 此记录定义了一条从当前坐标到指定点（不包括该点）的直线。 |
| [EMR_ARCTO](#EMR-ARCTO) | 此记录定义椭圆弧。 |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | 此记录定义了一组线段和贝塞尔曲线。 |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | 此记录定义用于弧和矩形操作的绘图方向。 |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | 此记录定义了回放设备上下文中斜接连接长度的限制。 |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | 此记录在回放设备上下文中打开路径括号。 |
| [EMR_ENDPATH](#EMR-ENDPATH) | 此记录关闭路径括号并将括号定义的路径选入回放设备上下文。 |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | 此记录关闭路径中打开的图形。 |
| [EMR_FILLPATH](#EMR-FILLPATH) | 此记录关闭当前路径中所有未闭合的图形，并使用当前画笔和多边形填充模式填充路径内部。 |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | 此记录关闭路径中所有未闭合的图形，使用当前笔描绘路径轮廓，并使用当前画笔填充其内部。 |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | 此记录使用当前笔渲染指定的路径。 |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | 此记录将路径中选中的任何曲线转换到回放设备上下文，将每条曲线转换为一系列直线。 |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | 此记录将当前路径重新定义为如果使用当前在回放设备上下文中选中的笔描边该路径时将被绘制的区域。 |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | 此记录将当前路径定义为回放设备上下文的裁剪区域，并使用指定模式将新区域与任何现有裁剪区域合并。 |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | 此记录中止路径括号或从已关闭的路径括号中丢弃路径。 |
| [EMR_COMMENT](#EMR-COMMENT) | 此记录指定任意私有数据。 |
| [EMR_FILLRGN](#EMR-FILLRGN) | 此记录使用指定的画笔填充指定的区域。 |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | 此记录使用指定的画笔在指定区域周围绘制边框。 |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | 此记录反转指定区域中的颜色。 |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | 此记录使用当前在回放设备上下文中选中的画笔绘制指定的区域。 |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | 此记录使用指定模式将指定区域与当前裁剪区域合并。 |
| [EMR_BITBLT](#EMR-BITBLT) | 此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作。 |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | 此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| [EMR_MASKBLT](#EMR-MASKBLT) | 此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案以及颜色遮罩位图一起使用，依据指定的前景和背景光栅操作。 |
| [EMR_PLGBLT](#EMR-PLGBLT) | 此记录指定将像素块从源位图传输到目标平行四边形，并使用颜色遮罩位图。 |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | 此记录指定将像素块从源位图的指定扫描线传输到目标矩形。 |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | 此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | 此记录定义具有指定特性的逻辑字体。 |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | 此记录使用当前字体和文本颜色绘制 ASCII 文本字符串。注意 EMR\\_EXTTEXTOUTA 应使用 EMR\\_EXTTEXTOUTW 记录进行仿真（第 2.3.5.8 节）。 |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | 此记录使用当前字体和文本颜色绘制 Unicode 文本字符串。 |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | 此记录定义一个或多个贝塞尔曲线。 |
| [EMR_POLYGON16](#EMR-POLYGON16) | 此记录定义一个由两个或多个顶点通过直线连接组成的多边形。 |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | 此记录通过连接指定数组中的点来定义一系列线段。 |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | 此记录基于当前坐标定义一个或多个贝塞尔曲线。 |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | 此记录基于当前位置信息定义一个或多个直线。 |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | 此记录定义多个相连线段的系列。 |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | 此记录定义一系列闭合多边形。 |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | 此记录定义了一组线段和贝塞尔曲线。 |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | 此记录定义具有指定位图图案的逻辑画笔。 |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | 此记录定义其图案由 DIB 指定的逻辑画笔。 |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | 此记录定义具有指定样式、宽度和画笔属性的逻辑装饰性或几何笔。 |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | 此记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。 |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | 此记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。 |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | 此记录指定图形操作的图像颜色管理 (ICM) 模式。 |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | 此记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑色彩空间对象。 |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | 此记录为图形操作定义当前的逻辑色彩空间对象。 |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | 此记录删除逻辑色彩空间对象。 |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | 此记录指定一个 OpenGL 函数。 |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | 此记录指定一个带有输出边界矩形的 OpenGL 函数。 |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | 此记录指定用于图形操作的像素格式 |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | 此记录向驱动程序传递任意信息。 |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | 此记录向驱动程序传递任意信息。 |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | 此记录输出字符串。 |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | 此记录强制字体映射器优先根据其 UniversalFontId 匹配字体，而不是其 LogFont 信息。 |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | 此记录向给定的已命名驱动程序传递任意信息。 |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | 此记录指定如何使用 Windows Color System (WCS) 1.0 值来校正逻辑调色板对象的条目 |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | 此记录指定用于图形输出的、文件名由 ASCII 字符组成的颜色配置文件。 |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | 此记录指定用于图形输出的、文件名由 Unicode 字符组成的颜色配置文件 |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | 此记录指定根据指定的混合操作，将像素块从源位图传输到目标矩形，包括 alpha 透明度数据。 |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | 此记录指定文本和图形的绘制顺序 |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | 此记录指定将像素块从源位图传输到目标矩形，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | 此记录指定使用颜色渐变填充矩形或三角形 |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | 此记录设置在字符查找期间使用的链接字体的 UniversalFontIds。 |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | 此记录指定为两端对齐目的在断字符后添加的额外空间量。 |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | 此记录指定是否使用文件名由 Unicode 字符组成的颜色配置文件进行颜色匹配。 |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | 此记录从文件名由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象 |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


此记录定义元文件的开始并指定其特性；其内容，包括嵌入图像的尺寸；元文件中的记录数；以及创建嵌入图像的设备分辨率。这些值使元文件能够独立于设备。

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


此记录定义一个或多个贝塞尔曲线。使用指定的端点和控制点定义三次贝塞尔曲线，并使用当前笔进行描边。

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


此记录定义由两条或更多直线连接的顶点组成的多边形。多边形使用当前笔描边，并使用当前画刷和多边形填充模式填充。通过从最后一个顶点绘制到第一个顶点的线条自动闭合多边形。

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


此记录通过连接指定数组中的点来定义一系列线段。

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


此记录基于当前位置信息定义一个或多个贝塞尔曲线。

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


此记录基于当前坐标定义一个或多个直线。使用当前笔从当前坐标绘制到 points 字段指定的第一个点。对于每条后续直线，绘制从前一条线的终点到 points 指定的下一个点。

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


此记录定义多段相连的线段系列。线段使用当前笔绘制。由线段形成的图形不进行填充。此记录既不使用也不更新当前坐标。

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


此记录定义一系列闭合多边形。每个多边形使用当前笔描边，并使用当前画刷和多边形填充模式填充。此记录定义的多边形可以重叠。

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


此记录定义窗口范围。

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


此记录定义窗口原点。

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


此记录定义视口范围。

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


此记录定义视口原点。

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


此记录定义当前画刷的原点。

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


此记录指示元文件的结束。

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


此记录定义指定逻辑坐标处像素的颜色。

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


此记录指定将逻辑字体匹配到物理字体的过程参数，该过程由字体映射器执行。

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


此记录定义回放设备上下文的映射模式。映射模式定义用于将页面空间单位转换为设备空间单位的度量单位，并且定义设备的 X 轴和 Y 轴的方向。

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


此记录定义回放设备上下文的背景混合模式。背景混合模式用于文本、交叉线画刷以及非实线的笔样式。

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


此记录定义多边形填充模式。

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


此记录定义二进制光栅操作模式。

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


此记录定义位图拉伸模式。

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


此记录定义文本对齐方式。

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


此记录使用指定的值定义回放设备上下文的颜色调整值。

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


此记录定义当前文本颜色。

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


此记录定义背景颜色。

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


此记录通过指定的偏移量重新定义回放设备上下文的裁剪区域。

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


此记录以逻辑单位定义新当前位置的坐标。

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


此记录将回放设备上下文的当前裁剪区域与当前元区域相交，并将组合后的区域保存为新的元区域。裁剪区域被重置为 null 区域。

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


此记录定义一个新裁剪区域，该区域由现有裁剪区域减去指定的矩形组成。

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


此记录通过当前裁剪区域与指定矩形的交集定义一个新裁剪区域。

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的视口。

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的窗口。

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


此记录通过复制描述所选对象和图形模式的数据显示\u2014包括位图、画刷、调色板、字体、画笔、区域、绘图模式和映射模式\u2014到已保存设备上下文的堆栈中，以保存回放设备上下文的当前状态。

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


此记录将回放设备上下文恢复到指定的已保存状态。回放设备上下文通过弹出先前 EMR\_SAVEDC（第 2.3.11 节）记录创建的已保存设备上下文堆栈中的状态信息来恢复。

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


此记录为回放设备上下文定义世界空间与页面空间之间的二维线性变换（有关更多信息，请参阅 [MSDN-WRLDPGSPC]）。此变换可用于缩放、旋转、剪切或平移图形输出。

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


此记录使用指定模式重新定义回放设备上下文的世界变换。

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


此记录向回放设备上下文添加对象，并通过其在 EMF 对象表（第 3.1.1.1 节）中的索引进行标识。

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


此记录定义具有指定样式、宽度和颜色的逻辑笔。该笔随后可以被选入回放设备上下文并用于绘制直线和曲线。

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


此记录定义用于图形操作中填充图形的逻辑画刷。

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


此记录删除图形对象，清除其在 EMF 对象表中的索引。如果已删除的对象在回放设备上下文中被选中，则必须恢复该上下文属性的默认对象。

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


此记录定义弧线的线段。该线段从当前坐标绘制到弧线的起点。弧线沿具有给定半径和中心的圆周绘制。弧线的长度由给定的起始角度和扫掠角度决定。

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


此记录定义一个椭圆。椭圆的中心是指定边界矩形的中心。椭圆使用当前笔进行描边，并使用当前画刷进行填充。

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


此记录定义一个矩形。矩形使用当前笔进行描边，并使用当前画刷进行填充。

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


此记录定义一个带圆角的矩形。矩形使用当前笔进行描边，并使用当前画刷进行填充。

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


此记录定义椭圆弧。

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


此记录定义一条弦（由椭圆与一条线段（称为割线）的交集所围成的区域）。弦使用当前笔进行描边，并使用当前画刷进行填充。

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


此记录定义一个由椭圆与两条径线的交集所限定的扇形楔块。扇形使用当前笔进行描边，并使用当前画刷进行填充。

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


此记录向回放设备上下文添加一个 LogPalette（第 2.2.17 节）对象，并通过其在 EMF 对象表中的索引进行标识。

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


此记录定义了一个 LogPalette 对象。

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


此记录在 LogPalette 对象的若干条目范围内定义 RGB（红绿蓝）颜色值。

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


此记录增大或减小逻辑调色板的大小。

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


此记录将当前逻辑调色板的条目映射到系统调色板。

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


此记录使用当前画笔填充显示表面的一个区域。

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


此记录定义一条从当前点到指定点（但不包括该点）的直线。它会将当前点重置为指定点。

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


此记录定义一个椭圆弧。它会将当前点重置为该弧的终点。

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


此记录定义了一组线段和贝塞尔曲线。

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


此记录定义用于弧和矩形操作的绘图方向。

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


此记录定义了回放设备上下文中斜接连接长度的限制。

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


此记录在回放设备上下文中打开路径括号。

--------------------

在路径括号打开后，应用程序可以开始处理记录以定义路径中的点。应用程序必须通过处理 EMR\_ENDPATH 记录来关闭打开的路径括号。当应用程序处理 EMR\_BEGINPATH 记录时，所有先前的路径必须从回放设备上下文中丢弃。

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


此记录关闭路径括号并将括号定义的路径选入回放设备上下文。

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


此记录关闭路径中打开的图形。

--------------------

处理 EMR\_CLOSEFIGURE 记录时，必须通过从当前点绘制一条线到图形的第一个点来关闭图形，然后必须使用线段连接样式来连接这些线段。如果图形是通过处理 EMR\_LINETO 记录而不是 EMR\_CLOSEFIGURE 记录来关闭的，则使用端帽来创建拐角而不是连接。EMR\_LINETO 在第 2.3.5.13 节中有说明。只有在回放设备上下文中存在打开的路径括号时，才应使用 EMR\_CLOSEFIGURE 记录。路径中的图形默认是打开的，除非通过处理此记录显式关闭。注意：即使当前点与图形的起始点相同，图形仍可能是打开的。处理 EMR\_CLOSEFIGURE 记录后，向路径添加线条或曲线必须启动一个新图形。

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


此记录关闭当前路径中所有未闭合的图形，并使用当前画笔和多边形填充模式填充路径内部。

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


此记录关闭路径中所有未闭合的图形，使用当前笔描绘路径轮廓，并使用当前画笔填充其内部。

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


此记录使用当前笔渲染指定的路径。

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


此记录将路径中选中的任何曲线转换到回放设备上下文，将每条曲线转换为一系列直线。

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


此记录将当前路径重新定义为如果使用当前在回放设备上下文中选中的笔描边该路径时将被绘制的区域。

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


此记录将当前路径定义为回放设备上下文的裁剪区域，并使用指定模式将新区域与任何现有裁剪区域合并。

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


此记录中止路径括号或从已关闭的路径括号中丢弃路径。

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


此记录指定任意私有数据。

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


此记录使用指定的画笔填充指定的区域。

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


此记录使用指定的画笔在指定区域周围绘制边框。

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


此记录反转指定区域中的颜色。

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


此记录使用当前在回放设备上下文中选中的画笔绘制指定的区域。

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


此记录使用指定模式将指定区域与当前裁剪区域合并。

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作。

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案以及颜色遮罩位图一起使用，依据指定的前景和背景光栅操作。

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


此记录指定将像素块从源位图传输到目标平行四边形，并使用颜色遮罩位图。

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


此记录指定将像素块从源位图的指定扫描线传输到目标矩形。

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


此记录指定将像素块从源位图传输到目标矩形，可选地与画笔图案结合，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


此记录定义一个具有指定特性的逻辑字体。该字体随后可以被选为回放设备上下文的当前字体。

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


此记录使用当前字体和文字颜色绘制 ASCII 文本字符串。注意 EMR\_EXTTEXTOUTA 应该通过 EMR\_EXTTEXTOUTW 记录（第 2.3.5.8 节）进行仿真。这需要将 EmrText 对象中的 ASCII 文本字符串转换为 Unicode UTF16-LE 编码。

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


此记录使用当前字体和文本颜色绘制 Unicode 文本字符串。

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


此记录定义一个或多个贝塞尔曲线。曲线使用当前笔进行绘制。

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


此记录定义由两条或更多直线连接的顶点组成的多边形。多边形使用当前笔描边，并使用当前画刷和多边形填充模式填充。通过从最后一个顶点绘制到第一个顶点的线条自动闭合多边形。

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


此记录通过连接指定数组中的点来定义一系列线段。

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


此记录基于当前坐标定义一个或多个贝塞尔曲线。

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


此记录基于当前点定义一个或多个直线。使用当前笔从当前点绘制到 Points 字段指定的第一个点。对于每条后续直线，绘制从前一条线的结束点到 Points 指定的下一个点。

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


此记录定义多个相连线段的系列。

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


此记录定义一系列闭合多边形。每个多边形使用当前笔进行描边，并使用当前画刷和多边形填充模式进行填充。此记录指定的多边形可以重叠。

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


此记录定义了一组线段和贝塞尔曲线。

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


此记录定义一个具有指定位图图案的逻辑画刷。该位图可以是设备无关位图（DIB）段位图，也可以是设备相关位图。

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


此记录定义其图案由 DIB 指定的逻辑画笔。

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


此记录定义具有指定样式、宽度和画笔属性的逻辑装饰性或几何笔。

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


此记录使用当前字体和文字颜色绘制一个或多个 ASCII 文本字符串。注意 EMR\_POLYTEXTOUTA 应该通过一系列 EMR\_EXTTEXTOUTW 记录（每个字符串对应一条）进行仿真。

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


此记录使用当前字体和文字颜色绘制一个或多个 Unicode 文本字符串。注意 EMR\_POLYTEXTOUTW 应该通过一系列 EMR\_EXTTEXTOUTW 记录（每个字符串对应一条）进行仿真。

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


此记录指定图形操作的图像颜色管理 (ICM) 模式。

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


此记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑色彩空间对象。

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


此记录为图形操作定义当前的逻辑色彩空间对象。

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


此记录删除一个逻辑颜色空间对象。注意 应使用 EMR\_DELETEOBJECT 记录而不是 EMR\_DELETECOLORSPACE 来删除逻辑颜色空间对象。

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


此记录指定一个 OpenGL 函数。

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


此记录指定一个带有输出边界矩形的 OpenGL 函数。

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


此记录指定用于图形操作的像素格式

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


此记录向驱动程序传递任意信息。其意图是这些信息将导致绘图操作的执行。

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


此记录向驱动程序传递任意信息。其意图是这些信息不会导致绘图操作的执行。

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


此记录输出字符串。

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


此记录强制字体映射器优先根据其 UniversalFontId 匹配字体，而不是其 LogFont 信息。

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


此记录向给定的已命名驱动程序传递任意信息。

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


此记录指定如何使用 Windows Color System (WCS) 1.0 值来校正逻辑调色板对象的条目

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


此记录指定用于图形输出的、文件名由 ASCII 字符组成的颜色配置文件。

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


此记录指定用于图形输出的、文件名由 Unicode 字符组成的颜色配置文件

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


此记录指定根据指定的混合操作，将像素块从源位图传输到目标矩形，包括 alpha 透明度数据。

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


此记录指定文本和图形的绘制顺序

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


此记录指定将像素块从源位图传输到目标矩形，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


此记录指定使用颜色渐变填充矩形或三角形

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


此记录设置在字符查找期间使用的链接字体的 UniversalFontIds。

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


此记录指定为两端对齐目的在断字符后添加的额外空间量。

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


此记录指定是否使用文件名由 Unicode 字符组成的颜色配置文件进行颜色匹配。

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


此记录从文件名由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象

