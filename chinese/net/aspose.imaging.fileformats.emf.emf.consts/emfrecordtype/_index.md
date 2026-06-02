---
title: "枚举 EmfRecordType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfRecordType enum. RecordType 枚举定义了唯一标识 EMF 记录的值。这些值在每个记录的 Type 字段中提供。"
type: docs
weight: 2910
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

该 RecordType 枚举定义了唯一标识 EMF 记录的取值。这些取值在每个记录的 Type 字段中提供。

```csharp
public enum EmfRecordType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EMR_HEADER | `1` | 此记录定义了元文件的开始并指定其特性；其内容，包括嵌入图像的尺寸；元文件中的记录数量；以及创建嵌入图像的设备分辨率。这些值使元文件能够独立于设备。 |
| EMR_POLYBEZIER | `2` | 此记录定义了一个或多个贝塞尔曲线。使用指定的端点和控制点定义三次贝塞尔曲线，并使用当前笔进行描边。 |
| EMR_POLYGON | `3` | 此记录定义了一个由两条或更多顶点通过直线连接而成的多边形。多边形使用当前笔进行轮廓描绘，使用当前画刷和多边形填充模式进行填充。多边形会自动通过从最后一个顶点绘制到第一个顶点的线段来闭合。 |
| EMR_POLYLINE | `4` | 此记录通过连接指定数组中的点来定义一系列线段。 |
| EMR_POLYBEZIERTO | `5` | 此记录基于当前位置信息定义一个或多个贝塞尔曲线。 |
| EMR_POLYLINETO | `6` | 此记录基于当前位置信息定义一个或多个直线。使用当前笔从当前位置绘制到 points 字段指定的第一个点。对于每条后续直线，绘制从前一条线的结束点到 points 指定的下一个点。 |
| EMR_POLYPOLYLINE | `7` | 此记录定义了多系列相连的线段。线段使用当前笔绘制。由线段形成的图形不进行填充。当前位置既不被使用也不被此记录更新。 |
| EMR_POLYPOLYGON | `8` | 此记录定义了一系列闭合多边形。每个多边形使用当前笔描边，使用当前画刷和多边形填充模式填充。此记录定义的多边形可以重叠。 |
| EMR_SETWINDOWEXTEX | `9` | 此记录定义窗口范围。 |
| EMR_SETWINDOWORGEX | `10` | 此记录定义窗口原点。 |
| EMR_SETVIEWPORTEXTEX | `11` | 此记录定义视口范围。 |
| EMR_SETVIEWPORTORGEX | `12` | 此记录定义视口原点。 |
| EMR_SETBRUSHORGEX | `13` | 此记录定义当前画刷的原点。 |
| EMR_EOF | `14` | 此记录指示元文件的结束。 |
| EMR_SETPIXELV | `15` | 此记录定义指定逻辑坐标处像素的颜色。 |
| EMR_SETMAPPERFLAGS | `16` | 此记录指定将逻辑字体匹配到物理字体的过程参数，该过程由字体映射器执行。 |
| EMR_SETMAPMODE | `17` | 此记录定义回放设备上下文的映射模式。映射模式定义用于将页面空间单位转换为设备空间单位的度量单位，并且还定义设备的 x 轴和 y 轴的方向。 |
| EMR_SETBKMODE | `18` | 此记录定义回放设备上下文的背景混合模式。背景混合模式用于文本、带纹理的画刷以及非实线的笔样式。 |
| EMR_SETPOLYFILLMODE | `19` | 此记录定义多边形填充模式。 |
| EMR_SETROP2 | `20` | 此记录定义二进制光栅操作模式。 |
| EMR_SETSTRETCHBLTMODE | `21` | 此记录定义位图拉伸模式。 |
| EMR_SETTEXTALIGN | `22` | 此记录定义文本对齐方式。 |
| EMR_SETCOLORADJUSTMENT | `23` | 此记录使用指定的数值定义回放设备上下文的颜色调整值。 |
| EMR_SETTEXTCOLOR | `24` | 此记录定义当前文本颜色。 |
| EMR_SETBKCOLOR | `25` | 此记录定义背景颜色。 |
| EMR_OFFSETCLIPRGN | `26` | 此记录通过指定的偏移量重新定义回放设备上下文的裁剪区域。 |
| EMR_MOVETOEX | `27` | 此记录以逻辑单位定义新当前位置的坐标。 |
| EMR_SETMETARGN | `28` | 此记录将回放设备上下文的当前裁剪区域与当前元区域相交，并将组合后的区域保存为新的元区域。裁剪区域被重置为 null 区域。 |
| EMR_EXCLUDECLIPRECT | `29` | 此记录定义了一个新的裁剪区域，该区域由现有裁剪区域减去指定的矩形组成。 |
| EMR_INTERSECTCLIPRECT | `30` | 此记录从当前裁剪区域与指定矩形的交集定义了一个新的裁剪区域。 |
| EMR_SCALEVIEWPORTEXTEX | `31` | 此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的视口。 |
| EMR_SCALEWINDOWEXTEX | `32` | 此记录使用指定乘数和除数形成的比例重新定义回放设备上下文的窗口。 |
| EMR_SAVEDC | `33` | 此记录通过复制描述已选对象和图形模式的数据（包括位图、画刷、调色板、字体、画笔、区域、绘图模式和映射模式），将回放设备上下文的当前状态保存到已保存设备上下文的堆栈中。 |
| EMR_RESTOREDC | `34` | 此记录将回放设备上下文恢复到指定的已保存状态。回放设备上下文通过弹出先前 EMR_SAVEDC（第 2.3.11 节）记录创建的已保存设备上下文堆栈中的状态信息来恢复。 |
| EMR_SETWORLDTRANSFORM | `35` | 此记录为回放设备上下文定义了世界空间与页面空间之间的二维线性变换（更多信息，请参见 [MSDN-WRLDPGSPC]）。此变换可用于缩放、旋转、剪切或平移图形输出。 |
| EMR_MODIFYWORLDTRANSFORM | `36` | 此记录使用指定模式重新定义回放设备上下文的世界变换。 |
| EMR_SELECTOBJECT | `37` | 此记录向回放设备上下文添加对象，并通过其在 EMF 对象表（第 3.1.1.1 节）中的索引进行标识。 |
| EMR_CREATEPEN | `38` | 此记录定义了具有指定样式、宽度和颜色的逻辑画笔。随后可以将该画笔选入回放设备上下文并用于绘制直线和曲线。 |
| EMR_CREATEBRUSHINDIRECT | `39` | 此记录定义了用于图形操作中填充图形的逻辑画刷。 |
| EMR_DELETEOBJECT | `40` | 此记录删除图形对象，清除其在 EMF 对象表中的索引。如果已删除的对象在回放设备上下文中被选中，则必须恢复该上下文属性的默认对象。 |
| EMR_ANGLEARC | `41` | 此记录定义了弧线的线段。该线段从当前点绘制到弧的起始位置。弧沿具有给定半径和中心的圆周绘制。弧的长度由给定的起始角度和扫掠角度决定。 |
| EMR_ELLIPSE | `42` | 此记录定义了一个椭圆。椭圆的中心是指定边界矩形的中心。椭圆使用当前画笔描边，并使用当前画刷填充。 |
| EMR_RECTANGLE | `43` | 此记录定义了一个矩形。矩形使用当前画笔描边，并使用当前画刷填充。 |
| EMR_ROUNDRECT | `44` | 此记录定义了一个带圆角的矩形。矩形使用当前画笔描边，并使用当前画刷填充。 |
| EMR_ARC | `45` | 此记录定义了椭圆弧。 |
| EMR_CHORD | `46` | 此记录定义了一条弦（由椭圆与线段的交集形成的区域，称为割线）。弦使用当前画笔描边，并使用当前画刷填充。 |
| EMR_PIE | `47` | 此记录定义了由椭圆与两条径线交叉形成的饼形楔块。饼形使用当前画笔描边，并使用当前画刷填充。 |
| EMR_SELECTPALETTE | `48` | 此记录向回放设备上下文添加一个 LogPalette（第 2.2.17 节）对象，并通过其在 EMF 对象表中的索引进行标识。 |
| EMR_CREATEPALETTE | `49` | 此记录定义了一个 LogPalette 对象。 |
| EMR_SETPALETTEENTRIES | `50` | 此记录在 LogPalette 对象的条目范围内定义了 RGB（红-绿-蓝）颜色值。 |
| EMR_RESIZEPALETTE | `51` | 此记录增大或减小逻辑调色板的大小。 |
| EMR_REALIZEPALETTE | `52` | 此记录将当前逻辑调色板的条目映射到系统调色板。 |
| EMR_EXTFLOODFILL | `53` | 此记录使用当前画笔填充显示表面的区域。 |
| EMR_LINETO | `54` | 此记录定义了一条从当前坐标到指定点（但不包括该点）的直线。它将当前坐标重置为指定点。 |
| EMR_ARCTO | `55` | 此记录定义了一个椭圆弧。它将当前坐标重置为该弧的终点。 |
| EMR_POLYDRAW | `56` | 此记录定义了一组线段和贝塞尔曲线。 |
| EMR_SETARCDIRECTION | `57` | 此记录定义了用于弧和矩形操作的绘图方向。 |
| EMR_SETMITERLIMIT | `58` | 此记录定义了回放设备上下文中斜接连接长度的限制。 |
| EMR_BEGINPATH | `59` | 此记录在回放设备上下文中打开路径括号。 |
| EMR_ENDPATH | `60` | 此记录关闭路径括号并将括号定义的路径选入回放设备上下文。 |
| EMR_CLOSEFIGURE | `61` | 此记录关闭路径中打开的图形。 |
| EMR_FILLPATH | `62` | 此记录关闭当前路径中所有打开的图形，并使用当前画笔和多边形填充模式填充路径内部。 |
| EMR_STROKEANDFILLPATH | `63` | 此记录关闭路径中所有打开的图形，使用当前画笔描绘路径轮廓，并使用当前画刷填充其内部。 |
| EMR_STROKEPATH | `64` | 此记录使用当前画笔呈现指定的路径。 |
| EMR_FLATTENPATH | `65` | 此记录将路径中选中的任何曲线转换到回放设备上下文中，将每条曲线转换为一系列直线。 |
| EMR_WIDENPATH | `66` | 此记录将当前路径重新定义为如果使用当前在回放设备上下文中选中的画笔描边该路径时将被绘制的区域。 |
| EMR_SELECTCLIPPATH | `67` | 此记录将当前路径定义为回放设备上下文的裁剪区域，并使用指定模式将新区域与任何现有裁剪区域合并。 |
| EMR_ABORTPATH | `68` | 此记录中止路径括号或从已关闭的路径括号中丢弃路径。 |
| EMR_COMMENT | `70` | 此记录指定任意私有数据。 |
| EMR_FILLRGN | `71` | 此记录使用指定的画刷填充指定的区域。 |
| EMR_FRAMERGN | `72` | 此记录使用指定的画刷在指定区域周围绘制边框。 |
| EMR_INVERTRGN | `73` | 此记录反转指定区域的颜色。 |
| EMR_PAINTRGN | `74` | 此记录使用当前在回放设备上下文中选中的画刷绘制指定的区域。 |
| EMR_EXTSELECTCLIPRGN | `75` | 此记录使用指定模式将指定区域与当前裁剪区域合并。 |
| EMR_BITBLT | `76` | 此记录指定将像素块从源位图传输到目标矩形，可选地结合画刷图案，依据指定的光栅操作。 |
| EMR_STRETCHBLT | `77` | 此记录指定将像素块从源位图传输到目标矩形，可选地结合画刷图案，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| EMR_MASKBLT | `78` | 此记录指定将像素块从源位图传输到目标矩形，可选地结合画刷图案并使用颜色掩码位图，依据指定的前景和背景光栅操作。 |
| EMR_PLGBLT | `79` | 此记录指定将像素块从源位图传输到目标平行四边形，并使用颜色掩码位图。 |
| EMR_SETDIBITSTODEVICE | `80` | 此记录指定将像素块从源位图的指定扫描线传输到目标矩形。 |
| EMR_STRETCHDIBITS | `81` | 此记录指定将像素块从源位图传输到目标矩形，可选地结合画刷图案，依据指定的光栅操作，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| EMR_EXTCREATEFONTINDIRECTW | `82` | 此记录定义了具有指定特性的逻辑字体。随后可以将该字体选择为回放设备上下文的当前字体。 |
| EMR_EXTTEXTOUTA | `83` | 此记录使用当前字体和文本颜色绘制 ASCII 文本字符串。注意 EMR_EXTTEXTOUTA 应该使用 EMR_EXTTEXTOUTW 记录进行仿真（第 2.3.5.8 节）。这需要将 EmrText 对象中的 ASCII 文本字符串转换为 Unicode UTF16-LE 编码。 |
| EMR_EXTTEXTOUTW | `84` | 此记录使用当前字体和文本颜色绘制 Unicode 文本字符串。 |
| EMR_POLYBEZIER16 | `85` | 此记录定义一个或多个贝塞尔曲线。曲线使用当前画笔绘制。 |
| EMR_POLYGON16 | `86` | 此记录定义了一个由两条或更多顶点通过直线连接而成的多边形。多边形使用当前笔进行轮廓描绘，使用当前画刷和多边形填充模式进行填充。多边形会自动通过从最后一个顶点绘制到第一个顶点的线段来闭合。 |
| EMR_POLYLINE16 | `87` | 此记录通过连接指定数组中的点来定义一系列线段。 |
| EMR_POLYBEZIERTO16 | `88` | 此记录基于当前位置定义一个或多个贝塞尔曲线。 |
| EMR_POLYLINETO16 | `89` | 此记录基于当前位置定义一个或多个直线。使用当前画笔从当前位置绘制到 Points 字段指定的第一个点。对于每条后续直线，绘制从前一条直线的结束点到 Points 指定的下一个点。 |
| EMR_POLYPOLYLINE16 | `90` | 此记录定义多个相连线段系列。 |
| EMR_POLYPOLYGON16 | `91` | 此记录定义一系列闭合多边形。每个多边形使用当前画笔描边，并使用当前画刷和多边形填充模式填充。此记录指定的多边形可以重叠。 |
| EMR_POLYDRAW16 | `92` | 此记录定义了一组线段和贝塞尔曲线。 |
| EMR_CREATEMONOBRUSH | `93` | 此记录定义具有指定位图模式的逻辑画刷。该位图可以是设备无关位图（DIB）段位图，也可以是设备相关位图。 |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | 此记录定义具有 DIB 指定模式的逻辑画刷。 |
| EMR_EXTCREATEPEN | `95` | 此记录定义具有指定样式、宽度和画刷属性的逻辑装饰性或几何画笔。 |
| EMR_POLYTEXTOUTA | `96` | 此记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。注意 EMR_POLYTEXTOUTA 应该使用一系列 EMR_EXTTEXTOUTW 记录（每个字符串一个）进行仿真。 |
| EMR_POLYTEXTOUTW | `97` | 此记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。注意 EMR_POLYTEXTOUTW 应该使用一系列 EMR_EXTTEXTOUTW 记录（每个字符串一个）进行仿真。 |
| EMR_SETICMMODE | `98` | 此记录指定图形操作的图像颜色管理 (ICM) 模式。 |
| EMR_CREATECOLORSPACE | `99` | 此记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑颜色空间对象。 |
| EMR_SETCOLORSPACE | `100` | 此记录为图形操作定义当前的逻辑颜色空间对象。 |
| EMR_DELETECOLORSPACE | `101` | 此记录删除逻辑颜色空间对象。注意 应使用 EMR_DELETEOBJECT 记录而不是 EMR_DELETECOLORSPACE 来删除逻辑颜色空间对象。 |
| EMR_GLSRECORD | `102` | 此记录指定一个 OpenGL 函数。 |
| EMR_GLSBOUNDEDRECORD | `103` | 此记录指定一个带有输出边界矩形的 OpenGL 函数。 |
| EMR_PIXELFORMAT | `104` | 此记录指定用于图形操作的像素格式。 |
| EMR_DRAWESCAPE | `105` | 此记录向驱动程序传递任意信息。其意图是这些信息将导致执行绘制。 |
| EMR_EXTESCAPE | `106` | 此记录向驱动程序传递任意信息。其意图是这些信息不会导致执行绘制。 |
| EMR_SMALLTEXTOUT | `108` | 此记录输出一个字符串。 |
| EMR_FORCEUFIMAPPING | `109` | 此记录强制字体映射器优先根据 UniversalFontId 而非 LogFont 信息匹配字体。 |
| EMR_NAMEDESCAPE | `110` | 此记录向给定的已命名驱动程序传递任意信息。 |
| EMR_COLORCORRECTPALETTE | `111` | 此记录指定如何使用 Windows Color System (WCS) 1.0 值校正逻辑调色板对象的条目 |
| EMR_SETICMPROFILEA | `112` | 此记录指定使用包含 ASCII 字符的文件名的颜色配置文件，用于图形输出。 |
| EMR_SETICMPROFILEW | `113` | 此记录指定使用包含 Unicode 字符的文件名的颜色配置文件，用于图形输出。 |
| EMR_ALPHABLEND | `114` | 此记录指定根据指定的混合操作，将像素从源位图块传输到目标矩形，包括 alpha 透明度数据。 |
| EMR_SETLAYOUT | `115` | 此记录指定文本和图形的绘制顺序。 |
| EMR_TRANSPARENTBLT | `116` | 此记录指定将像素从源位图块传输到目标矩形，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标尺寸。 |
| EMR_GRADIENTFILL | `118` | 此记录指定使用颜色渐变填充矩形或三角形。 |
| EMR_SETLINKEDUFIS | `119` | 此记录设置在字符查找期间使用的链接字体的 UniversalFontIds。 |
| EMR_SETTEXTJUSTIFICATION | `120` | 此记录指定为断字符添加的额外空间量，以用于对齐目的。 |
| EMR_COLORMATCHTOTARGETW | `121` | 此记录指定是否使用文件名包含 Unicode 字符的颜色配置文件进行颜色匹配。 |
| EMR_CREATECOLORSPACEW | `122` | 此记录从名称包含 Unicode 字符的颜色配置文件创建逻辑颜色空间对象。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


