---
title: "EmfRecordType 枚举"
type: docs
weight: 290
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

RecordType 枚举定义了唯一标识 EMF 记录的值。<br/>            这些值在每个记录的 Type 字段中提供。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| EMR_ABORTPATH | 此记录中止路径括号或丢弃闭合路径括号中的路径。 |
| EMR_ALPHABLEND | 此记录指定将像素从源位图块传输到目标矩形，<br/>            包括 alpha 透明度数据，依据指定的混合操作。 |
| EMR_ANGLEARC | 此记录定义弧的线段。线段从 <br/>            当前位置信息绘制到弧的起点。弧沿给定半径和中心的圆周绘制。弧的长度由 <br/>            给定的起始角度和扫掠角度决定。 |
| EMR_ARC | 此记录定义椭圆弧。 |
| EMR_ARCTO | 此记录定义椭圆弧。它将当前位置信息重置为弧的 <br/>            终点。 |
| EMR_BEGINPATH | 此记录在回放设备上下文中打开路径括号。 |
| EMR_BITBLT | 此记录指定将像素从源位图块传输到目标<br/>            矩形，可选地结合画笔图案，依据指定的光栅操作。 |
| EMR_CHORD | 此记录定义和弦（由椭圆 <br/>            与线段（称为割线）的交叉形成的区域）。和弦使用当前笔进行描边，使用当前画笔进行填充。 |
| EMR_CLOSEFIGURE | 此记录关闭路径中打开的图形。 |
| EMR_COLORCORRECTPALETTE | 此记录指定如何使用 Windows <br/>            颜色系统 (WCS) 1.0 值来校正逻辑调色板对象的条目。 |
| EMR_COLORMATCHTOTARGETW | 此记录指定是否使用文件名由 Unicode 字符组成的文件中指定的颜色配置文件进行颜色匹配。 |
| EMR_COMMENT | 此记录指定任意私有数据。 |
| EMR_CREATEBRUSHINDIRECT | 此记录定义用于图形操作中图形填充的逻辑画刷。 |
| EMR_CREATECOLORSPACE | 此记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑颜色空间对象。 |
| EMR_CREATECOLORSPACEW | 此记录从名称由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象。 |
| EMR_CREATEDIBPATTERNBRUSHPT | 此记录定义具有 DIB 指定图案的逻辑画刷。 |
| EMR_CREATEMONOBRUSH | 此记录定义具有指定位图图案的逻辑画刷。位图可以<br/>             是设备无关位图（DIB）段位图，也可以是设备相关位图。 |
| EMR_CREATEPALETTE | 此记录定义一个 LogPalette 对象。 |
| EMR_CREATEPEN | 此记录定义具有指定样式、宽度和颜色的逻辑钢笔。<br/>            该钢笔随后可以被选入回放设备上下文并用于绘制直线和曲线。 |
| EMR_DELETECOLORSPACE | 此记录删除逻辑颜色空间对象。注意，应该使用 EMR_DELETEOBJECT 记录<br/>            而不是 EMR_DELETECOLORSPACE 来删除逻辑颜色空间对象。 |
| EMR_DELETEOBJECT | 此记录删除图形对象，清除其在 EMF 对象表中的索引。<br/>            如果已删除的对象在回放设备上下文中被选中，则必须恢复该上下文属性的默认对象。 |
| EMR_DRAWESCAPE | 此记录向驱动程序传递任意信息。其意图是这些信息<br/>            将导致执行绘图。 |
| EMR_ELLIPSE | 此记录定义一个椭圆。椭圆的中心是 <br/>            指定的边界矩形的中心。椭圆使用当前的笔进行描边，<br/>            并使用当前的画刷进行填充。 |
| EMR_ENDPATH | 此记录关闭路径括号并将括号定义的路径 <br/>            选入播放设备上下文。 |
| EMR_EOF | 此记录指示元文件的结束。 |
| EMR_EXCLUDECLIPRECT | 此记录定义一个新的剪裁区域，该区域由现有剪裁区域 <br/>            减去指定的矩形组成。 |
| EMR_EXTCREATEFONTINDIRECTW | 此记录定义具有指定特性的逻辑字体。该字体 <br/>            随后可以被选为播放设备上下文的当前字体。 |
| EMR_EXTCREATEPEN | 此记录定义具有指定样式、<br/>            宽度和画刷属性的逻辑装饰笔或几何笔。 |
| EMR_EXTESCAPE | 此记录向驱动程序传递任意信息。其意图是这些信息 <br/>            不会导致绘图操作。 |
| EMR_EXTFLOODFILL | 此记录使用当前画刷填充显示表面的一块区域。 |
| EMR_EXTSELECTCLIPRGN | 此记录使用 <br/>            指定的模式将指定区域与当前剪裁区域合并。 |
| EMR_EXTTEXTOUTA | 此记录使用当前字体和文字颜色绘制 ASCII 文本字符串。注意 <br/>            EMR_EXTTEXTOUTA 应该使用 EMR_EXTTEXTOUTW 记录（第 2.3.5.8 节）进行仿真。  <br/>            这需要将 EmrText 对象中的 ASCII 文本字符串转换为 Unicode UTF16-LE 编码。 |
| EMR_EXTTEXTOUTW | 此记录使用当前字体和文字颜色绘制 Unicode 文本字符串。 |
| EMR_FILLPATH | 此记录关闭当前路径中所有打开的图形，并使用当前画刷和多边形填充模式 <br/>            填充路径的内部。 |
| EMR_FILLRGN | 此记录使用指定的画刷填充指定的区域。 |
| EMR_FLATTENPATH | 此记录将所选路径中的任何曲线转换为播放设备<br/>            上下文，将每条曲线转换为一系列直线。 |
| EMR_FORCEUFIMAPPING | 此记录强制字体映射器基于其 UniversalFontId 在<br/>            优先于 LogFont 信息的情况下匹配字体。 |
| EMR_FRAMERGN | 此记录使用指定的画刷在指定区域周围绘制边框。 |
| EMR_GLSBOUNDEDRECORD | 此记录指定一个带有输出边界矩形的 OpenGL 函数。 |
| EMR_GLSRECORD | 此记录指定一个 OpenGL 函数。 |
| EMR_GRADIENTFILL | 此记录指定使用颜色渐变填充矩形或三角形。 |
| EMR_HEADER | 此记录定义了元文件的起始并指定其特性；其内容，<br/>            包括嵌入图像的尺寸；元文件中的记录数；以及创建嵌入图像的设备分辨率。这些值使元文件能够实现设备无关性。 |
| EMR_INTERSECTCLIPRECT | 此记录通过当前裁剪区域与指定矩形的交集定义一个新的裁剪区域。 |
| EMR_INVERTRGN | 此记录反转指定区域的颜色。 |
| EMR_LINETO | 此记录定义从当前坐标到指定点（但不包括该点）的直线。它将当前坐标重置为指定点。 |
| EMR_MASKBLT | 此记录指定将像素从源位图块传输到目标<br/>             矩形，可选地结合画刷图案并应用<br/>            颜色掩码位图，依据指定的前景和背景光栅操作。 |
| EMR_MODIFYWORLDTRANSFORM | 此记录使用指定模式重新定义播放设备上下文的世界变换。 |
| EMR_MOVETOEX | 此记录定义新当前位置信息的坐标，使用逻辑单位。 |
| EMR_NAMEDESCAPE | 此记录将任意信息传递给指定的命名驱动程序。 |
| EMR_OFFSETCLIPRGN | 此记录通过指定的偏移量重新定义回放设备上下文的裁剪区域。 |
| EMR_PAINTRGN | 此记录使用当前在 <br/>            回放设备上下文中选中的画笔来绘制指定的区域。 |
| EMR_PIE | 此记录定义由椭圆 <br/>            与两条径线的交叉所限定的扇形楔形。该扇形使用当前画笔描边，并使用 <br/>            当前画刷填充。 |
| EMR_PIXELFORMAT | 此记录指定用于图形操作的像素格式 |
| EMR_PLGBLT | 此记录指定将像素块从源位图传输到目标 <br/>            平行四边形，并应用颜色掩码位图。 |
| EMR_POLYBEZIER | 此记录定义一个或多个贝塞尔曲线。使用<br/>            指定的端点和控制点来定义三次贝塞尔曲线，并使用当前画笔描边。 |
| EMR_POLYBEZIER16 | 此记录定义一个或多个贝塞尔曲线。曲线使用当前画笔绘制。 |
| EMR_POLYBEZIERTO | 此记录基于当前位置信息定义一个或多个贝塞尔曲线。 |
| EMR_POLYBEZIERTO16 | 此记录基于当前位置信息定义一个或多个贝塞尔曲线。 |
| EMR_POLYDRAW | 此记录定义一组线段和贝塞尔曲线。 |
| EMR_POLYDRAW16 | 此记录定义一组线段和贝塞尔曲线。 |
| EMR_POLYGON | 此记录定义了一个由两个或多个顶点通过直线 <br/>            连接而成的多边形。多边形使用当前画笔描边，并使用当前画刷和多边形填充模式进行填充。多边形会自动闭合，通过从最后一个顶点绘制一条线到第一个顶点。 |
| EMR_POLYGON16 | 此记录定义了一个由两个或多个顶点通过直线连接而成的多边形。<br/>            多边形使用当前画笔描边，并使用当前画刷和多边形<br/>             填充模式进行填充。多边形会自动闭合，通过从最后一个顶点绘制一条线到第一个顶点。 |
| EMR_POLYLINE | 此记录通过连接指定 <br/>            数组中的点来定义一系列线段。 |
| EMR_POLYLINE16 | 此记录通过连接指定数组中的点来定义一系列线段。 |
| EMR_POLYLINETO | 此记录基于当前坐标定义一条或多条直线。<br/>            使用当前画笔，从当前坐标绘制一条线到 points 字段指定的第一个点。对于每条后续直线，绘制从前一条线的结束点到 points 指定的下一个点。 |
| EMR_POLYLINETO16 | 此记录基于当前坐标定义一条或多条直线。<br/>             使用当前画笔，从当前坐标绘制一条线到 Points 字段指定的第一个点。对于每条后续直线，绘制从前一条线的结束点到 Points 指定的下一个点。 |
| EMR_POLYPOLYGON | 此记录定义了一系列闭合多边形。每个多边形使用 <br/>            当前画笔描边，并使用当前画刷和多边形填充模式进行填充。此记录定义的多边形可能会重叠。 |
| EMR_POLYPOLYGON16 | 此记录定义了一系列闭合多边形。每个多边形使用 <br/>            当前画笔描边，并使用当前画刷和多边形填充模式进行填充。此记录指定的多边形<br/>             可能会重叠。 |
| EMR_POLYPOLYLINE | 此记录定义了多组相连的线段。线段使用当前画笔 <br/>            绘制。由线段形成的图形不进行填充。T<br/>            he 当前坐标既不被使用也不被此记录更新。 |
| EMR_POLYPOLYLINE16 | 此记录定义了多组相连的线段。 |
| EMR_POLYTEXTOUTA | 此记录使用当前字体和文字颜色绘制一个或多个 ASCII 文本字符串。<br/>             注意 EMR_POLYTEXTOUTA 应该通过一系列 EMR_EXTTEXTOUTW 记录来模拟，每个字符串对应一条记录 |
| EMR_POLYTEXTOUTW | 此记录使用当前字体和文字颜色绘制一个或多个 Unicode 文本字符串。<br/>            注意 EMR_POLYTEXTOUTW 应该通过一系列 EMR_EXTTEXTOUTW 记录来模拟，每个字符串对应一条记录 |
| EMR_REALIZEPALETTE | 此记录将当前逻辑调色板中的条目映射到系统调色板。 |
| EMR_RECTANGLE | 此记录定义一个矩形。矩形使用当前的 <br/>            笔进行描边，并使用当前的画刷进行填充。 |
| EMR_RESIZEPALETTE | 此记录增加或减少逻辑调色板的大小。 |
| EMR_RESTOREDC | 此记录将回放设备上下文恢复到指定的保存状态。 <br/>            回放设备上下文通过从先前的 EMR_SAVEDC（第 2.3.11 节）记录创建的已保存设备上下文堆栈中弹出状态信息来恢复。 |
| EMR_ROUNDRECT | 此记录定义一个带圆角的矩形。矩形使用当前的笔进行描边 <br/>            并使用当前的画刷进行填充。 |
| EMR_SAVEDC | 此记录通过复制描述所选对象和图形模式的数据显示（包括位图、画刷、调色板、<br/>            字体、笔、区域、绘图模式和映射模式），将回放设备上下文的当前状态保存到已保存设备上下文的堆栈中。 |
| EMR_SCALEVIEWPORTEXTEX | 此记录使用指定的乘数和除数形成的比例 <br/>            重新定义回放设备上下文的视口。 |
| EMR_SCALEWINDOWEXTEX | 此记录使用指定的乘数和除数形成的比例 <br/>            重新定义回放设备上下文的窗口。 |
| EMR_SELECTCLIPPATH | 此记录将当前路径定义为回放设备 <br/>            上下文的裁剪区域，并使用指定的模式将新区域与任何现有的裁剪区域合并。 |
| EMR_SELECTOBJECT | 此记录向回放设备上下文添加一个对象，通过其在 EMF 对象表（第 3.1.1.1 节）中的 <br/>            索引进行标识。 |
| EMR_SELECTPALETTE | 此记录向回放设备 <br/>            上下文添加一个 LogPalette（第 2.2.17 节）对象，通过其在 EMF 对象表中的索引进行标识。 |
| EMR_SETARCDIRECTION | 此记录定义用于弧和矩形<br/>             操作的绘图方向。 |
| EMR_SETBKCOLOR | 此记录定义背景颜色。 |
| EMR_SETBKMODE | 此记录定义了回放设备上下文的背景混合模式。背景混合<br/>             模式用于文本、交叉填充刷和非实线的笔样式。 |
| EMR_SETBRUSHORGEX | 此记录定义了当前画刷的原点。 |
| EMR_SETCOLORADJUSTMENT | 此记录使用指定的值定义了回放设备上下文的颜色调整值。 |
| EMR_SETCOLORSPACE | 此记录定义了用于图形操作的当前逻辑颜色空间对象。 |
| EMR_SETDIBITSTODEVICE | 此记录指定了从源<br/>             位图的指定扫描线向目标矩形的像素块传输。 |
| EMR_SETICMMODE | 此记录指定了图形操作的图像颜色管理 (ICM) 模式。 |
| EMR_SETICMPROFILEA | 此记录指定了一个颜色配置文件，该文件的名称由 ASCII 字符组成，<br/>             用于图形输出。 |
| EMR_SETICMPROFILEW | 此记录指定了一个颜色配置文件，该文件的名称由 Unicode 字符组成，<br/>             用于图形输出。 |
| EMR_SETLAYOUT | 此记录指定了文本和图形的绘制顺序 |
| EMR_SETLINKEDUFIS | 此记录设置已链接字体的 UniversalFontIds，以在字符查找期间使用。 |
| EMR_SETMAPMODE | 此记录定义了回放设备上下文的映射模式。映射模式<br/>             定义了用于将页面空间单位转换为设备空间单位的度量单位，<br/>             还定义了设备的 x 轴和 y 轴的方向。 |
| EMR_SETMAPPERFLAGS | 此记录指定了将逻辑字体匹配到物理<br/>            字体的过程参数，该过程由字体映射器执行。 |
| EMR_SETMETARGN | 此记录将回放设备上下文的当前裁剪区域与<br/>            当前元区域相交，并将组合后的区域保存为新的元区域。裁剪区域被重置为 null 区域。 |
| EMR_SETMITERLIMIT | 此记录定义了播放 <br/>            设备上下文的斜接接合长度限制。 |
| EMR_SETPALETTEENTRIES | 此记录在 LogPalette 对象中 <br/>            定义了一系列条目的 RGB（红-绿-蓝）颜色值。 |
| EMR_SETPIXELV | 此记录定义了指定逻辑坐标处像素的颜色。 |
| EMR_SETPOLYFILLMODE | 此记录定义了多边形填充模式。 |
| EMR_SETROP2 | 此记录定义了二进制光栅操作模式。 |
| EMR_SETSTRETCHBLTMODE | 此记录定义了位图拉伸模式。 |
| EMR_SETTEXTALIGN | 此记录定义了文本对齐方式。 |
| EMR_SETTEXTCOLOR | 此记录定义了当前文本颜色。 |
| EMR_SETTEXTJUSTIFICATION | 此记录指定在两端对齐时为断字符添加的额外空白量<br/>             用于排版。 |
| EMR_SETVIEWPORTEXTEX | 此记录定义了视口范围。 |
| EMR_SETVIEWPORTORGEX | 此记录定义了视口原点。 |
| EMR_SETWINDOWEXTEX | 此记录定义了窗口范围。 |
| EMR_SETWINDOWORGEX | 此记录定义窗口原点。 |
| EMR_SETWORLDTRANSFORM | 此记录定义了世界空间与 <br/>            页面空间之间的二维线性变换（有关更多信息，请参阅 [MSDN-WRLDPGSPC]）用于回放设备上下文。 <br/>            此变换可用于缩放、旋转、剪切或平移图形输出。 |
| EMR_SMALLTEXTOUT | 此记录输出一个字符串。 |
| EMR_STRETCHBLT | 此记录指定将像素从源位图块传输到目标<br/>             矩形，可选地结合画笔图案，依据指定的光栅<br/>             操作，必要时拉伸或压缩输出以适应目标的尺寸。 |
| EMR_STRETCHDIBITS | 此记录指定将像素从源位图块传输到目标 <br/>            矩形，可选地结合画笔图案，依据指定的光栅操作，<br/>            必要时拉伸或压缩输出以适应目标的尺寸。 |
| EMR_STROKEANDFILLPATH | 此记录关闭路径中所有打开的图形，使用当前笔 <br/>            对路径轮廓进行描边，并使用当前画刷填充其内部。 |
| EMR_STROKEPATH | 此记录使用当前笔渲染指定的路径。 |
| EMR_TRANSPARENTBLT | 此记录指定将像素从源位图块传输到目标矩形，<br/>             将指定颜色视为透明，必要时拉伸或压缩输出以适应目标的尺寸。 |
| EMR_WIDENPATH | 此记录将当前路径重新定义为如果路径 <br/>            使用当前在回放设备上下文中选定的笔进行描边，则会被绘制的区域。 |
