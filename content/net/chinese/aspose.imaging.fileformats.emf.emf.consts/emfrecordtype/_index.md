---
title: EmfRecordType
second_title: Aspose.Imaging for .NET API 参考
description: RecordType 枚举定义了唯一标识 EMF 记录的值 这些值在每条记录的类型字段中提供
type: docs
weight: 2820
url: /zh/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

RecordType 枚举定义了唯一标识 EMF 记录的值。 这些值在每条记录的类型字段中提供。

```csharp
public enum EmfRecordType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| EMR_HEADER | `1` | 这条记录定义了元文件的开始并指定了它的特征；它的内容， ，包括嵌入图像的尺寸；元文件中的记录数；以及创建嵌入图像的设备的 分辨率。这些值使图元文件可以独立于设备。 |
| EMR_POLYBEZIER | `2` | 该记录定义了一条或多条贝塞尔曲线。三次贝塞尔曲线使用 指定的端点和控制点定义，并使用当前笔进行描边。 |
| EMR_POLYGON | `3` | 该记录定义了一个多边形，该多边形由两个或多个由 直线连接的顶点组成。使用当前画笔勾勒出多边形轮廓，并使用当前画笔 和多边形填充模式进行填充。通过从最后一个顶点到第一个顶点绘制一条线来自动关闭多边形。 |
| EMR_POLYLINE | `4` | 这条记录通过连接指定的 数组中的点来定义一系列线段。 |
| EMR_POLYBEZIERTO | `5` | 该记录根据当前位置定义了一条或多条贝塞尔曲线。 |
| EMR_POLYLINETO | `6` | 此记录根据当前位置定义一条或多条直线。 使用当前笔从当前位置到点字段 指定的第一个点绘制一条线。对于每条附加线，从前一条线的结束 点到点指定的下一个点执行绘制。 |
| EMR_POLYPOLYLINE | `7` | 该记录定义了多个系列的连接线段。线段是 使用当前笔绘制的。由这些段组成的图形未填充。 T 他当前的位置既没有被这个记录使用也没有更新。 |
| EMR_POLYPOLYGON | `8` | 这个记录定义了一系列封闭的多边形。使用 当前笔勾勒出每个多边形的轮廓，并使用当前画笔和多边形填充模式进行填充。此记录定义的多边形可以重叠。 |
| EMR_SETWINDOWEXTEX | `9` | 这条记录定义了窗口范围。 |
| EMR_SETWINDOWORGEX | `10` | 这条记录定义了窗口原点。 |
| EMR_SETVIEWPORTEXTEX | `11` | 此记录定义视口范围。 |
| EMR_SETVIEWPORTORGEX | `12` | 此记录定义视口原点。 |
| EMR_SETBRUSHORGEX | `13` | 这条记录定义了当前画笔的原点。 |
| EMR_EOF | `14` | 这条记录表示元文件的结束。 |
| EMR_SETPIXELV | `15` | 这条记录定义了指定逻辑坐标处像素的颜色。 |
| EMR_SETMAPPERFLAGS | `16` | 该记录指定了将逻辑字体匹配到物理 字体的过程的参数，该过程由字体映射器执行。 |
| EMR_SETMAPMODE | `17` | 该记录定义了播放设备上下文的映射模式。映射模式 定义了用于将页面空间单元转换为设备空间单元的度量单位 ，还定义了设备x轴和y轴的方向。 |
| EMR_SETBKMODE | `18` | 该记录定义了播放设备上下文的背景混合模式。背景 mix 模式与非实线的文本、阴影画笔和笔样式一起使用。 |
| EMR_SETPOLYFILLMODE | `19` | 此记录定义多边形填充模式。 |
| EMR_SETROP2 | `20` | 这条记录定义了二进制光栅操作模式。 |
| EMR_SETSTRETCHBLTMODE | `21` | 此记录定义位图拉伸模式。 |
| EMR_SETTEXTALIGN | `22` | 此记录定义文本对齐方式。 |
| EMR_SETCOLORADJUSTMENT | `23` | 此记录使用指定值定义播放设备上下文的颜色调整值。 |
| EMR_SETTEXTCOLOR | `24` | 这条记录定义了当前的文本颜色。 |
| EMR_SETBKCOLOR | `25` | 这条记录定义了背景颜色。 |
| EMR_OFFSETCLIPRGN | `26` | 此记录通过指定的偏移量重新定义播放设备上下文的剪辑区域。 |
| EMR_MOVETOEX | `27` | 此记录定义新当前位置的坐标，以逻辑单位表示。 |
| EMR_SETMETARGN | `28` | 该记录将播放设备上下文的当前剪辑区域与 当前元区域相交，并将组合区域保存为新元区域。剪辑区域被重置为空区域。 |
| EMR_EXCLUDECLIPRECT | `29` | 此记录定义了一个新的剪辑区域，该区域由现有的剪辑区域 减去指定的矩形组成。 |
| EMR_INTERSECTCLIPRECT | `30` | 这条记录定义了一个新的剪辑区域，从当前剪辑 区域和指定矩形的交点开始。 |
| EMR_SCALEVIEWPORTEXTEX | `31` | 此记录使用由指定的被乘数和除数形成的比率 重新定义播放设备上下文的视口。 |
| EMR_SCALEWINDOWEXTEX | `32` | 此记录使用指定的被乘数和除数形成的比率 重新定义播放设备上下文的窗口。 |
| EMR_SAVEDC | `33` | 此记录通过将描述选定对象和图形模式（包括位图、画笔、调色板、 字体、笔、区域、绘图模式和映射模式）的数据 复制到已保存的堆栈中来保存播放设备上下文的当前状态设备上下文. |
| EMR_RESTOREDC | `34` | 此记录将播放设备上下文恢复到指定的保存状态。 播放设备上下文通过从早期 EMR_SAVEDC（第 2.3.11 节）记录创建的 已保存设备上下文堆栈中弹出状态信息来恢复。 |
| EMR_SETWORLDTRANSFORM | `35` | 此记录定义了世界空间和 页面空间之间的二维线性变换（更多信息，请参阅 [MSDN-WRLDPGSPC]），用于播放设备上下文。 此转换可用于缩放、旋转、剪切或平移图形输出。 |
| EMR_MODIFYWORLDTRANSFORM | `36` | 此记录使用指定模式重新定义播放设备上下文的世界变换。 |
| EMR_SELECTOBJECT | `37` | 此记录将一个对象添加到播放设备上下文，通过其在 EMF 对象表（第 3.1.1.1 节）中的 索引来标识它。 |
| EMR_CREATEPEN | `38` | 该记录定义了具有指定样式、宽度和颜色的逻辑笔。 随后可以将笔选择到播放设备上下文中并用于绘制直线和曲线。 |
| EMR_CREATEBRUSHINDIRECT | `39` | 该记录定义了图形填充图形操作的逻辑画笔。 |
| EMR_DELETEOBJECT | `40` | 此记录删除一个图形对象，清除其在 EMF 对象表中的索引。 如果在播放设备上下文中选择了删除的对象，则必须恢复该上下文属性的默认对象 。 |
| EMR_ANGLEARC | `41` | 这条记录定义了一段弧线。线段从 当前位置绘制到弧的起点。圆弧沿具有给定半径和圆心的圆的周长 绘制。弧的长度由 给定的起始角和扫描角定义。 |
| EMR_ELLIPSE | `42` | 这个记录定义了一个椭圆。椭圆的中心是 指定的边界矩形的中心。椭圆使用当前笔勾勒出轮廓， 使用当前画笔填充。 |
| EMR_RECTANGLE | `43` | 这个记录定义了一个矩形。矩形使用当前的 笔勾勒出轮廓，并使用当前的画笔进行填充。 |
| EMR_ROUNDRECT | `44` | 该记录定义了一个圆角矩形。矩形使用当前笔勾勒出 轮廓并使用当前画笔填充。 |
| EMR_ARC | `45` | 这条记录定义了一个椭圆弧。 |
| EMR_CHORD | `46` | 该记录定义了一个弦（由椭圆 和一条线段的交点界定的区域，称为割线）。使用当前的 笔勾勒和弦，使用当前的画笔填充。 |
| EMR_PIE | `47` | 此记录定义了一个饼形楔形，其边界为椭圆 和两条径向线的交点。饼图用当前笔勾勒出轮廓，用 当前画笔填充。 |
| EMR_SELECTPALETTE | `48` | 此记录将 LogPalette（第 2.2.17 节）对象添加到播放设备 上下文，通过其在 EMF 对象表中的索引来标识它。 |
| EMR_CREATEPALETTE | `49` | 这条记录定义了一个 LogPalette 对象。 |
| EMR_SETPALETTEENTRIES | `50` | 此记录定义了 LogPalette 对象中一系列条目 中的 RGB（红-绿-蓝）颜色值。 |
| EMR_RESIZEPALETTE | `51` | 此记录增加或减少逻辑调色板的大小。 |
| EMR_REALIZEPALETTE | `52` | 此记录将条目从当前逻辑调色板映射到系统调色板。 |
| EMR_EXTFLOODFILL | `53` | 这条记录用当前画笔填充显示表面的一个区域。 |
| EMR_LINETO | `54` | 此记录定义了从当前位置到但不包括 指定点的线。它将当前位置重置为指定点。 |
| EMR_ARCTO | `55` | 这个记录定义了一个椭圆弧。它将当前位置重置为弧的 端点。 |
| EMR_POLYDRAW | `56` | 这条记录定义了一组线段和贝塞尔曲线。 |
| EMR_SETARCDIRECTION | `57` | 该记录定义了用于圆弧和矩形操作的绘制方向 操作。 |
| EMR_SETMITERLIMIT | `58` | 此记录定义回放的斜接连接长度限制 设备上下文。 |
| EMR_BEGINPATH | `59` | 此记录在播放设备上下文中打开一个路径括号。 |
| EMR_ENDPATH | `60` | 这条记录关闭一个路径括号并选择括号 定义的路径进入播放设备上下文。 |
| EMR_CLOSEFIGURE | `61` | 此记录关闭路径中打开的图形。 |
| EMR_FILLPATH | `62` | 此记录关闭当前路径中所有打开的图形，并使用当前画笔和多边形填充模式填充路径的内部 。 |
| EMR_STROKEANDFILLPATH | `63` | 此记录关闭路径中所有打开的图形，使用当前笔在路径轮廓上描边 ，并使用当前画笔填充路径内部。 |
| EMR_STROKEPATH | `64` | 这条记录使用当前画笔渲染指定路径 |
| EMR_FLATTENPATH | `65` | 此记录将路径中选择的任何曲线转换为播放设备 上下文，将每条曲线转换为线序列。 |
| EMR_WIDENPATH | `66` | 此记录将当前路径重新定义为如果路径 是使用当前在播放设备上下文中选择的笔描边时将被绘制的区域。 |
| EMR_SELECTCLIPPATH | `67` | 此记录将当前路径定义为播放设备 上下文的剪辑区域，使用指定的模式将新区域与任何现有剪辑区域相结合。 |
| EMR_ABORTPATH | `68` | 此记录中止路径括号或丢弃闭合路径括号中的路径。 |
| EMR_COMMENT | `70` | 这条记录指定了任意私人数据。 |
| EMR_FILLRGN | `71` | 这条记录使用指定的画笔填充指定区域。 |
| EMR_FRAMERGN | `72` | 这条记录使用指定的画笔在指定区域周围绘制边框。 |
| EMR_INVERTRGN | `73` | 这条记录反转指定区域的颜色。 |
| EMR_PAINTRGN | `74` | 该记录使用当前选择的画笔将指定区域绘制到 播放设备上下文中。 |
| EMR_EXTSELECTCLIPRGN | `75` | 此记录使用 指定模式将指定区域与当前剪辑区域组合在一起。 |
| EMR_BITBLT | `76` | 此记录指定像素从源位图到目标的块传输 矩形，可选地结合画笔图案，根据指定的光栅操作。 |
| EMR_STRETCHBLT | `77` | 此记录指定像素从源位图到目标的块传输 矩形，可选地结合画笔图案，根据指定的 raster 操作，拉伸或压缩输出以适应目标的尺寸，如果需要的话。 |
| EMR_MASKBLT | `78` | 此记录指定像素从源位图到目标 矩形的块传输，根据指定的前景和背景光栅操作，可选地结合画笔图案和应用 颜色掩码位图。 |
| EMR_PLGBLT | `79` | 此记录指定像素从源位图到目标 平行四边形的块传输，并应用颜色掩码位图。 |
| EMR_SETDIBITSTODEVICE | `80` | 此记录指定从源 位图的指定扫描线到目标矩形的像素块传输。 |
| EMR_STRETCHDIBITS | `81` | 此记录指定像素从源位图到目标的块传输. |
| EMR_EXTCREATEFONTINDIRECTW | `82` | 该记录定义了具有指定特征的逻辑字体。随后可以选择字体 作为播放设备上下文的当前字体。 |
| EMR_EXTTEXTOUTA | `83` | 此记录使用当前字体和文本颜色绘制一个 ASCII 文本字符串。注意 EMR_EXTTEXTOUTA 应该使用 EMR_EXTTEXTOUTW 记录来模拟（第 2.3.5.8 节）。 这需要将 EmrText 对象中的 ASCII 文本字符串转换为 Unicode UTF16-LE 编码。 |
| EMR_EXTTEXTOUTW | `84` | 此记录使用当前字体和文本颜色绘制一个 Unicode 文本字符串。 |
| EMR_POLYBEZIER16 | `85` | 该记录定义了一条或多条贝塞尔曲线。曲线是使用当前笔绘制的。 |
| EMR_POLYGON16 | `86` | 这个记录定义了一个由两个或多个由直线连接的顶点组成的多边形。 使用当前画笔勾勒多边形轮廓，并使用当前画笔和多边形 填充模式进行填充。通过从最后一个顶点到第一个顶点绘制一条线来自动关闭多边形。 |
| EMR_POLYLINE16 | `87` | 这条记录通过连接指定数组中的点来定义一系列线段。 |
| EMR_POLYBEZIERTO16 | `88` | 这条记录根据当前位置定义了一条或多条贝塞尔曲线。 |
| EMR_POLYLINETO16 | `89` | 此记录根据当前位置定义一条或多条直线。 使用当前笔从当前位置到点 字段指定的第一个点绘制一条线。对于每条附加线，从上一条线的 结束点到Points. 指定的下一个点执行绘制 |
| EMR_POLYPOLYLINE16 | `90` | 这条记录定义了多串相连的线段。 |
| EMR_POLYPOLYGON16 | `91` | 这个记录定义了一系列封闭的多边形。每个多边形都使用当前画笔 勾勒出轮廓，并使用当前画笔和多边形填充模式进行填充。此记录指定的多边形 可以重叠。 |
| EMR_POLYDRAW16 | `92` | 这条记录定义了一组线段和贝塞尔曲线。 |
| EMR_CREATEMONOBRUSH | `93` | 此记录定义了具有指定位图模式的逻辑画笔。位图可以 是与设备无关的位图 (DIB) 部分位图，也可以是与设备相关的位图。 |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | 此记录定义了一个逻辑画笔，其具有 DIB 指定的模式。 |
| EMR_EXTCREATEPEN | `95` | 此记录定义具有指定样式、 宽度和画笔属性的逻辑修饰或几何笔。 |
| EMR_POLYTEXTOUTA | `96` | 此记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。 注意 EMR_POLYTEXTOUTA 应该使用一系列 EMR_EXTTEXTOUTW 记录来模拟，每个字符串一个 |
| EMR_POLYTEXTOUTW | `97` | 此记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。 注意 EMR_POLYTEXTOUTW 应该使用一系列 EMR_EXTTEXTOUTW 记录来模拟，每个字符串一个 |
| EMR_SETICMMODE | `98` | 此记录指定图形操作的图像色彩管理 (ICM) 模式。 |
| EMR_CREATECOLORSPACE | `99` | 此记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑颜色空间对象 |
| EMR_SETCOLORSPACE | `100` | 该记录定义了图形操作的当前逻辑色彩空间对象。 |
| EMR_DELETECOLORSPACE | `101` | 此记录删除一个逻辑色彩空间对象。注意 EMR_DELETEOBJECT 记录应该 用来代替 EMR_DELETECOLORSPACE 来删除逻辑色彩空间 object |
| EMR_GLSRECORD | `102` | 这条记录指定了一个OpenGL函数。 |
| EMR_GLSBOUNDEDRECORD | `103` | 这条记录指定了一个OpenGL函数，带有一个用于输出的边界矩形。 |
| EMR_PIXELFORMAT | `104` | 此记录指定用于图形操作的像素格式 |
| EMR_DRAWESCAPE | `105` | 此记录将任意信息传递给驱动程序。目的是信息 将导致绘制完成。 |
| EMR_EXTESCAPE | `106` | 此记录将任意信息传递给驱动程序。目的是信息 不会导致绘制完成。 |
| EMR_SMALLTEXTOUT | `108` | 这条记录输出一个字符串。 |
| EMR_FORCEUFIMAPPING | `109` | 此记录强制字体映射器根据其在 首选项中的 UniversalFontId 将字体与其 LogFont 信息相匹配。 |
| EMR_NAMEDESCAPE | `110` | 此记录将任意信息传递给给定的命名驱动程序。 |
| EMR_COLORCORRECTPALETTE | `111` | 此记录指定如何使用 Windows 更正逻辑调色板对象的条目 颜色系统 (WCS) 1.0 值 |
| EMR_SETICMPROFILEA | `112` | 此记录指定文件中的颜色配置文件，其名称由 ASCII 字符组成， 用于图形输出。 |
| EMR_SETICMPROFILEW | `113` | 此记录指定文件中的颜色配置文件，其名称由 Unicode 字符组成， 用于图形输出 |
| EMR_ALPHABLEND | `114` | 此记录指定像素从源位图到目标矩形的块传输， 包括 alpha 透明度数据，根据指定的混合操作。 |
| EMR_SETLAYOUT | `115` | 这条记录指定了文字和图形的绘制顺序 |
| EMR_TRANSPARENTBLT | `116` | 此记录指定像素从源位图到目标矩形的块传输， 将指定的颜色视为透明，必要时拉伸或压缩输出以适合目标的尺寸 |
| EMR_GRADIENTFILL | `118` | 这条记录指定用color 的渐变填充矩形或三角形 |
| EMR_SETLINKEDUFIS | `119` | 此记录设置链接字体的 UniversalFontIds 以在字符查找期间使用。 |
| EMR_SETTEXTJUSTIFICATION | `120` | 这条记录指定了额外的空间量，以添加用于分隔字符的对齐 目的。 |
| EMR_COLORMATCHTOTARGETW | `121` | 此记录指定是否使用在名称由 Unicode 字符组成的文件中指定的颜色配置文件执行颜色匹配。 |
| EMR_CREATECOLORSPACEW | `122` | 此记录从名称由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
