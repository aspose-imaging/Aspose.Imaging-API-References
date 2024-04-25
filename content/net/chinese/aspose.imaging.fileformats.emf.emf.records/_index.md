---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging for .NET API 参考
description: 命名空间包含类型 MS-EMF增强的元文件格式 2.3 EMF Records
type: docs
weight: 360
url: /zh/aspose.imaging.fileformats.emf.emf.records/
---
命名空间包含类型 [MS-EMF]：增强的元文件格式。 2.3 EMF Records

## 课程

| 班级 | 描述 |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | 此记录中止路径括号或丢弃闭合路径括号中的路径。 |
| [EmfAlphaBlend](./emfalphablend) | EMR_ALPHABLEND 记录根据指定的混合操作指定从源位图到 目标矩形的像素块传输，包括 alpha 透明度数据。 |
| [EmfAngleArc](./emfanglearc) | EMR_ANGLEARC 记录指定弧的线段。线段从 当前位置绘制到弧的起点。圆弧沿圆的周长绘制，具有 给定的半径和圆心。弧的长度由给定的起始角和扫描角定义 |
| [EmfArc](./emfarc) | EMR_ARC 记录指定椭圆弧。 |
| [EmfArcTo](./emfarcto) | EMR_ARCTO 记录指定椭圆弧。它将当前位置重置为弧的终点。 |
| [EmfBeginPath](./emfbeginpath) | 此记录在当前播放设备上下文中打开一个路径括号。 打开路径括号后，应用程序可以开始处理记录以定义 位于路径中的点。应用程序必须通过 处理 EMR_ENDPATH 关闭打开的路径括号记录。 当应用程序处理 EMR_BEGINPATH 记录时，所有以前的路径 必须从播放设备上下文中丢弃。 |
| [EmfBitBlt](./emfbitblt) | EMR_BITBLT 记录指定像素从源位图到目标 矩形的块传输，根据指定的光栅操作，可选地结合画笔图案。 |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | 位图记录类型执行位图图像的块传输。 |
| [EmfChord](./emfchord) | EMR_CHORD 记录指定了一个弦，它是一个由 椭圆和一条线段的交点界定的区域，称为割线。使用当前笔勾勒和弦，使用当前画笔填充 。 |
| [EmfClippingRecordType](./emfclippingrecordtype) | 剪辑记录类型指定和管理剪辑区域。 注意 EMR_SETMETARGN 记录没有指定参数。 |
| [EmfCloseFigure](./emfclosefigure) | 此记录关闭路径中打开的图形。 处理 EMR_CLOSEFIGURE 记录必须通过从当前位置到图形的第一个点绘制一条线 来关闭图形，然后它必须使用线连接样式连接 线。如果通过处理 EMR_LINETO 记录而不是EMR_CLOSEFIGURE 记录来闭合地物，则端盖 用于创建角而不是连接。EMR_LINETO 在section 2.3.5.13 中指定。 只有在存在在播放设备上下文中打开路径 括号。 路径中的图形是打开的，除非通过处理此记录明确关闭它。 |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | EMR_COLORCORRECTPALETTE 记录指定如何使用 WCS 1.0 值更正逻辑调色板 对象的条目。 |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | EMR_COLORMATCHTOTargetW 记录指定是否使用在名称由 Unicode 字符组成的文件中指定的 color 配置文件执行颜色匹配。 |
| [EmfComment](./emfcomment) | EMR_COMMENT 记录包含任意私有数据。 注意本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | EMR_COMMENT_BEGINGROUP 记录指定一组绘图记录的开始。 |
| [EmfCommentEmfPlus](./emfcommentemfplus) | EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF+ 记录。 注意 本节中未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEmfSpool](./emfcommentemfspool) | EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。 注意 本节中未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEndGroup](./emfcommentendgroup) | EMR_COMMENT_ENDGROUP 记录指定一组绘图记录的结尾。 |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | EMR_COMMENT_MULTIFORMATS 记录指定了多种图形格式的图像。 |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | EMR_COMMENT_PUBLIC 记录类型指定 EMF 处理的扩展。 |
| [EmfCommentRecordType](./emfcommentrecordtype) | 注释记录类型定义了用于指定任意私有数据的格式，将记录 嵌入其他元文件格式，以及添加新的或特殊用途的命令。 |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像。 |
| [EmfControlRecordType](./emfcontrolrecordtype) | 控制记录类型定义 EMF 元文件的开始和结束以及元文件的属性。 |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | EMR_CREATEBRUSHINDIRECT 记录定义了图形操作的逻辑画笔。 |
| [EmfCreateColorSpace](./emfcreatecolorspace) | EMR_CREATECOLORSPACE 记录从颜色配置文件创建一个逻辑颜色空间对象，其名称为 ，名称由 ASCII 字符组成。 |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | EMR_CREATECOLORSPACEW 记录从具有 由Unicode 字符组成的名称的颜色配置文件创建逻辑色彩空间对象。 |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | EMR_CREATEDIBPATTERNBRUSHPT 记录定义图形操作的图案画笔。 模式由 DIB 指定。 |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | EMR_CREATEMONOBRUSH 记录定义了用于图形操作的单色图案画笔。 图案由单色 DIB 指定。 |
| [EmfCreatePalette](./emfcreatepalette) | EMR_CREATEPALETTE 记录定义了图形操作的逻辑调色板。 |
| [EmfCreatePen](./emfcreatepen) | EMR_CREATEPEN 记录定义了一个用于图形操作的逻辑笔。 |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | EMR_DELETECOLORSPACE 记录删除一个逻辑色彩空间对象。 |
| [EmfDeleteObject](./emfdeleteobject) | EMR_DELETEOBJECT 记录删除一个图形对象，该对象由其在 EMF 对象表中的索引指定（第 3.1.1.1 节）。 |
| [EmfDrawEscape](./emfdrawescape) | EMR_DRAWESCAPE 记录将任意信息传递给打印机驱动程序。意图是 信息将导致绘制完成。 |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | 绘图记录类型执行图形绘制。 |
| [EmfEllipse](./emfellipse) | EMR_ELLIPSE 记录指定一个椭圆。椭圆的中心是指定的 边界矩形的中心。椭圆用当前画笔勾勒，用当前画笔填充。 |
| [EmfEndPath](./emfendpath) | 这条记录关闭一个路径括号，并选择括号定义的路径进入 播放设备上下文。 |
| [EmfEof](./emfeof) | EMR_EOF 记录指示元文件的结尾并指定调色板。 |
| [EmfEscapeRecordType](./emfescaperecordtype) | 转义记录类型执行打印机驱动程序功能。 |
| [EmfExcludeClipRect](./emfexcludecliprect) | EMR_EXCLUDECLIPRECT 记录指定了一个新的剪辑区域，该区域由现有的 剪辑区域减去指定的矩形组成。 注意 本节中未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | EMR_EXTCREATEFONTINDIRECTW 记录定义了图形操作的逻辑字体。 |
| [EmfExtCreatePen](./emfextcreatepen) | EMR_EXTCREATEPEN 记录定义图形操作的扩展逻辑笔。 An 可选 DIB 可以指定用作线型。 |
| [EmfExtEscape](./emfextescape) | EMR_EXTESCAPE 记录将任意信息传递给打印机驱动程序。意图是 信息不会导致绘制完成。 |
| [EmfExtFloodFill](./emfextfloodfill) | EMR_EXTFLOODFILL 记录用当前画笔填充显示表面的一个区域 |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | EMR_EXTSELECTCLIPRGN 记录使用指定的模式将指定区域与当前剪辑区域 组合在一起。 注意 本节中未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtTextOutA](./emfexttextouta) | EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制一个 ASCII 文本字符串。 |
| [EmfExtTextOutW](./emfexttextoutw) | EMR_EXTTEXTOUTW 记录使用当前字体和文本颜色绘制一个 ASCII 文本字符串。 |
| [EmfFillPath](./emffillpath) | EMR_FILLPATH 记录关闭当前路径中所有打开的图形，并使用当前画笔和多边形填充模式将路径内部填充 。 |
| [EmfFillRgn](./emffillrgn) | EMR_FILLRGN 记录使用指定画笔填充指定区域。 |
| [EmfFlatternPath](./emfflatternpath) | 该记录将所选路径中的任何曲线转换为播放设备 上下文；每条曲线必须变成一系列线。 |
| [EmfForceUfiMapping](./emfforceufimapping) | EMR_FORCEUFIMAPPING 记录强制字体映射器根据它们的 UniversalFontId 优先于它们的LogFont（第2.2.13 节）信息匹配字体。 |
| [EmfFrameRgn](./emfframergn) | EMR_FRAMERGN 记录使用指定的画笔在指定区域周围绘制边框。 |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | EMR_GLSBOUNDEDRECORD 记录指定了一个带有用于输出的边界矩形的 OpenGL 函数。 |
| [EmfGlsRecord](./emfglsrecord) | EMR_GLSRECORD 记录指定了一个 OpenGL 函数。 |
| [EmfGradientFill](./emfgradientfill) | EMR_GRADIENTFILL 记录指定用颜色渐变填充矩形或三角形。 |
| [EmfIntersectClipRect](./emfintersectcliprect) | EMR_INTERSECTCLIPRECT 记录从 当前剪辑区域和指定矩形的交点指定一个新的剪辑区域。 注意 本节中未描述的字段在第 2.3.2 节中指定。 |
| [EmfInvertRgn](./emfinvertrgn) | EMR_INVERTRGN 记录反转指定区域的颜色。 |
| [EmfLineTo](./emflineto) | EMR_LINETO 记录指定从当前位置到但不包括 指定点的线。它将当前位置重置到指定点。 |
| [EmfMaskBlt](./emfmaskblt) | EMR_MASKBLT 记录指定像素从源位图到目标 矩形的块传输，根据指定的前景和背景光栅操作，可选地结合画笔图案和应用颜色掩码 位图。 |
| [EmfMetafileHeader](./emfmetafileheader) | EMR_HEADER 记录类型定义 EMF metafiles 的起点，并指定在其上创建 metafile 中的图像的设备的属性。标头记录中的信息使得 EMF 元文件可以独立于任何特定的输出设备。 Size 字段的值可用于区分本节前面列出的不同 EMR_HEADER 记录类型。 有三种可能headers: base header，即EmfMetafileHeader记录。 这个header的固定大小部分为88字节，包含一个Header对象。 第一个扩展头，即EmfMetafileHeaderExtension1记录。 固定大小这个头的一部分是100字节，它包含一个Header object 和一个HeaderExtension1对象（第2.2.10节）。 第二个扩展头，也就是EmfMetafileHeaderExtension2记录。 这个头的固定大小部分是108字节，它包含一个 Header 对象、 一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。 |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | EmfMetafileHeaderExtension1 记录是在 EMF 元文件的第一个扩展中使用的标头记录。 在 EmfHeaderExtension1 字段之后，其余字段是可选的，可以以任何顺序出现。 |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | EmfMetafileHeaderExtension2 记录是在 EMF 元文件的第二个扩展中使用的标头记录。在 EmfHeaderExtension2 字段之后，其余字段是可选的， 可以以任何顺序出现。 |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | EMR_MODIFYWORLDTRANSFORM 记录在播放设备上下文中将当前世界空间修改为 page-space 变换。 |
| [EmfMoveToEx](./emfmovetoex) | EMR_MOVETOEX 记录以逻辑单位指定新当前位置的坐标。 |
| [EmfNamedEscape](./emfnamedescape) | MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。 |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | 对象创建记录类型创建图形对象。 |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | 对象操作记录类型管理和修改图形对象。 |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | EMR_OFFSETCLIPRGN 记录将播放设备上下文 中的当前剪辑区域移动指定的偏移量。 |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | OpenGL 记录类型指定 OpenGL 函数。 |
| [EmfPaintRgn](./emfpaintrgn) | EMR_PAINTRGN 记录使用当前选择到 播放设备上下文中的画笔绘制指定区域。 |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | 路径括号记录类型指定和操作路径括号中的路径。 注意：路径括号记录均未指定参数。 |
| [EmfPie](./emfpie) | EMR_PIE 记录指定了一个由椭圆和两个 径向线的交点界定的饼形楔形。饼图用当前画笔勾勒，用当前画笔填充。 |
| [EmfPixelFormat](./emfpixelformat) | EMR_PIXELFORMAT 记录指定用于图形操作的像素格式。 |
| [EmfPlgBlt](./emfplgblt) | EMR_PLGBLT 记录指定像素从源位图到目标 平行四边形的块传输，并应用颜色掩码位图。 |
| [EmfPolyBezier](./emfpolybezier) | EMR_POLYBEZIER 记录指定一条或多条贝塞尔曲线。 |
| [EmfPolyBezier16](./emfpolybezier16) | EMR_POLYBEZIER16 记录指定一条或多条贝塞尔曲线。曲线是使用 当前笔绘制的。 |
| [EmfPolyBezierTo](./emfpolybezierto) | EMR_POLYBEZIERTO 记录根据当前位置指定一条或多条贝塞尔曲线。 |
| [EmfPolyBezierTo16](./emfpolybezierto16) | EMR_POLYBEZIERTO16 记录根据当前位置指定一条或多条贝塞尔曲线。 |
| [EmfPolyDraw](./emfpolydraw) | EMR_POLYDRAW 记录指定了一组线段和贝塞尔曲线。 |
| [EmfPolyDraw16](./emfpolydraw16) | EMR_POLYDRAW16 记录指定了一组线段和贝塞尔曲线。 |
| [EmfPolygon](./emfpolygon) | EMR_POLYGON 记录指定了一个多边形，该多边形由两个或多个由 直线连接的顶点组成。 |
| [EmfPolygon16](./emfpolygon16) | EMR_POLYGON16 记录指定了一个多边形，该多边形由两个或多个由 直线连接的顶点组成。使用当前画笔勾勒出多边形轮廓，并使用当前画笔 和多边形填充模式进行填充。通过从最后一个顶点到第一个顶点绘制一条线来自动关闭多边形。 |
| [EmfPolyline](./emfpolyline) | EMR_POLYLINE 记录通过连接 指定数组中的点来指定一系列线段。 |
| [EmfPolyline16](./emfpolyline16) | EMR_POLYLINE16 记录通过连接 指定数组中的点来指定一系列线段。 |
| [EmfPolylineTo](./emfpolylineto) | EMR_POLYLINETO 记录根据当前位置指定一条或多条直线。 |
| [EmfPolylineTo16](./emfpolylineto16) | EMR_POLYLINETO16 记录根据当前位置指定一条或多条直线。 使用 当前笔从当前位置到 aPoints 字段指定的第一个点绘制一条线。对于每条附加线，从前一条 线的终点到 aPoints 指定的下一个点进行绘制。 |
| [EmfPolyPolygon](./emfpolypolygon) | EMR_POLYPOLYGON 记录指定了一系列闭合多边形。 |
| [EmfPolyPolygon16](./emfpolypolygon16) | EMR_POLYPOLYGON16 记录指定了一系列闭合多边形。使用当前画笔对每个多边形进行 轮廓，并使用当前画笔和多边形填充模式进行填充。此记录绘制的多边形 可以重叠。 |
| [EmfPolyPolyline](./emfpolypolyline) | EMR_POLYPOLYLINE 记录指定了多个系列的连接线段。 |
| [EmfPolyPolyline16](./emfpolypolyline16) | EMR_POLYPOLYLINE16 记录指定了多个系列的连接线段。 |
| [EmfPolyTextOutA](./emfpolytextouta) | EMR_POLYTEXTOUTA 记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。 |
| [EmfPolyTextOutW](./emfpolytextoutw) | EMR_POLYTEXTOUTW 记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。 |
| [EmfRealizePalette](./emfrealizepalette) | 此记录将调色板条目从 current LogPalette 对象（第 2.2.17 节）映射到 system_palette。 此 EMF 记录未指定参数。 |
| [EmfRecord](./emfrecord) | EMF 记录的基类 所有 EMF 记录的长度必须是 4 字节的倍数。这在前面 EMF 记录类型的 通用结构中进行了描述，方法是在这些结构的末尾适当地包括 AlignmentPadding fields 。 AlignmentPadding fields 的内容必须始终被忽略。为简洁起见，这些字段并未显示在每个单独的 EMF 记录定义中。 |
| [EmfRectangle](./emfrectangle) | EMR_RECTANGLE 记录绘制一个矩形。矩形使用当前 pen 勾勒出轮廓，并使用当前画笔填充。 |
| [EmfResizePalette](./emfresizepalette) | EMR_RESIZEPALETTE 记录增加或减少现有 LogPalette 对象的大小（第 2.2.17 节）。 |
| [EmfRestoreDc](./emfrestoredc) | EMR_RESTOREDC 记录将播放设备上下文恢复到指定状态。 The 播放设备上下文是通过从由 之前的 EMR_SAVEDC 记录（第 2.3.11 节）创建的堆栈中弹出状态信息来恢复的。 |
| [EmfRop4](./emfrop4) | 四元光栅操作，它为 位图的前景色和背景色指定三元光栅运算。这些值定义了 源矩形的颜色数据如何与目标矩形的颜色数据结合。 |
| [EmfRoundRect](./emfroundrect) | EMR_ROUNDRECT 记录指定了一个圆角矩形。矩形使用当前笔勾勒出 轮廓并使用当前画笔填充。 |
| [EmfSaveDc](./emfsavedc) | 将播放设备上下文的当前状态保存在由前面的 EMR_SAVEDC 记录（如果有）保存的状态堆栈上。状态由图形属性 和对象组成，包括当前选择的位图、 画笔、调色板、字体、笔和区域。 An EMR_RESTOREDC 记录用于恢复状态。 此 EMF 记录未指定参数。 |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | EMR_SCALEVIEWPORTEXTEX 记录通过使用由指定的被乘数和除数形成的 比率重新指定设备上下文的视口。 |
| [EmfScaleWindowExtex](./emfscalewindowextex) | EMR_SCALEWINDOWEXTEX 记录通过 使用由指定的被乘数和除数形成的比率重新指定播放设备上下文的窗口。 |
| [EmfSelectClipPath](./emfselectclippath) | EMR_SELECTCLIPPATH 记录将当前路径指定为播放的剪辑区域 设备上下文，使用指定的模式将新区域与任何现有剪辑区域结合起来。 |
| [EmfSelectObject](./emfselectobject) | EMR_SELECTOBJECT 记录将图形对象添加到当前图元文件播放设备 上下文。该对象由其在 EMF 对象表中的索引（第 3.1.1.1 节）或由 StockObject 枚举（第 2.1.31 节）中的 its 值指定。 |
| [EmfSelectPalette](./emfselectpalette) | EMR_SELECTPALETTE 记录指定播放设备上下文的逻辑调色板。 |
| [EmfSetArcDirection](./emfsetarcdirection) | EMR_SETARCDIRECTION 记录指定用于圆弧和矩形输出的绘制方向。 |
| [EmfSetBkColor](./emfsetbkcolor) | EMR_SETBKCOLOR 记录指定背景颜色。 |
| [EmfSetBkMode](./emfsetbkmode) | EMR_SETBKMODE 记录指定播放设备上下文的背景混合模式。 背景混合模式用于文本、阴影画笔和非实线的笔样式。 |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | EMR_SETBRUSHORGEX 记录指定了当前画笔的原点。 |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | EMR_SETCOLORADJUSTMENT 记录在播放 设备上下文中指定颜色调整属性。 |
| [EmfSetColorSpace](./emfsetcolorspace) | EMR_SETCOLORSPACE 记录定义图形操作的当前逻辑色彩空间对象。 |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | EMR_SETDIBITSTODEVICE 记录指定像素从 的指定扫描线到目标矩形的块传输。 |
| [EmfSetIcmMode](./emfseticmmode) | EMR_SETICMMODE 记录指定图形操作的图像色彩管理 (ICM) 模式。 |
| [EmfSetIcmProfileA](./emfseticmprofilea) | EMR_SETICMPROFILEA 记录指定文件中的颜色配置文件，其名称由 ASCII 字符组成，用于图形输出。 |
| [EmfSetIcmProfileW](./emfseticmprofilew) | EMR_SETICMPROFILEW 记录指定文件中的颜色配置文件，其名称由 Unicode 字符组成，用于图形输出。 |
| [EmfSetLayout](./emfsetlayout) | EMR_SETLAYOUT 记录指定绘制文本和图形的顺序。 |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | EMR_SETLINKEDUFIS 记录将链接字体的 UniversalFontIds（第 2.2.27 节）设置为 在字符查找期间使用。 |
| [EmfSetMapMode](./emfsetmapmode) | EMR_SETMAPMODE 记录指定播放设备上下文的映射模式。 映射模式指定了用于将页面空间单元 转换为设备空间单元的度量单位，同时也指定了设备的x轴和y轴的方向。 |
| [EmfSetMapperFlags](./emfsetmapperflags) | EMR_SETMAPPERFLAGS 记录指定将逻辑字体匹配到 物理字体的过程的参数，该过程由字体映射器执行。 |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter 设置当前元区域与当前剪辑区域 以形成播放设备上下文的新元区域。 The 当前剪辑区域应该重置为空。 此 EMF 记录未指定参数。 |
| [EmfSetMiterLimit](./emfsetmiterlimit) | EMR_SETMITERLIMIT 记录指定回放设备上下文的斜接连接长度限制。 |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | EMR_SETPALETTEENTRIES 记录为现有 LogPalette（第 2.2.17 节）对象定义了一系列条目中的 RGB 颜色值。 |
| [EmfSetPixelV](./emfsetpixelv) | EMR_SETPIXELV 记录定义了指定逻辑坐标处像素的颜色。 |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | EMR_SETPOLYFILLMODE 记录定义多边形填充模式。 |
| [EmfSetRop2](./emfsetrop2) | EMR_SETROP2 记录定义了二进制光栅操作模式。 |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | EMR_SETSTRETCHBLTMODE 记录指定位图拉伸模式。 |
| [EmfSetTextAlign](./emfsettextalign) | EMR_SETTEXTALIGN 记录指定文本对齐方式。 |
| [EmfSetTextColor](./emfsettextcolor) | EMR_SETTEXTCOLOR 记录定义当前文本颜色。 |
| [EmfSetTextJustification](./emfsettextjustification) | EMR_SETTEXTJUSTIFICATION 记录指定要添加到 break 字符以进行文本对齐的额外空间量。 |
| [EmfSetViewportExtEx](./emfsetviewportextex) | EMR_SETVIEWPORTEXTEX 记录定义视口范围。 |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | EMR_SETVIEWPORTORGEX 记录定义视口原点。 |
| [EmfSetWindowExtEx](./emfsetwindowextex) | EMR_SETWINDOWEXTEX 记录定义了窗口范围。 |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | EMR_SETWINDOWORGEX 记录定义了窗口原点。 |
| [EmfSetWorldTransform](./emfsetworldtransform) | EMR_SETWORLDTRANSFORM 记录指定播放设备上下文中当前世界空间到页面空间变换的变换。 |
| [EmfSmallTextOut](./emfsmalltextout) | EMR_SMALLTEXTOUT 记录输出一个字符串。 |
| [EmfStateRecordType](./emfstaterecordtype) | 状态记录类型指定和管理定义播放设备上下文状态的图形属性。 |
| [EmfStretchBlt](./emfstretchblt) | EMR_STRETCHBLT 记录指定像素从源位图到 目标矩形的块传输，根据指定的 raster 操作，可选地结合画笔图案，拉伸或压缩输出以适应目标的尺寸，如有必要. |
| [EmfStretchDiBits](./emfstretchdibits) | EMR_STRETCHDIBITS 记录指定像素从源位图到 目标矩形的块传输，可选地结合画笔图案，根据指定的光栅 操作，拉伸或压缩输出以适应目标的尺寸，如果必要的。 |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | EMR_STROKEANDFILLPATH 记录关闭路径中任何打开的图形，使用当前画笔描边 路径的轮廓，并使用当前画笔填充其内部。 |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH 类 |
| [EmfTransformRecordType](./emftransformrecordtype) | 转换记录类型指定和修改世界空间到页面空间的转换。 |
| [EmfTransparentBlt](./emftransparentblt) | EMR_TRANSPARENTBLT 记录指定像素从源位图到 目标矩形的块传输，将指定的颜色视为透明，拉伸或压缩输出 以适应目标的尺寸，如有必要 |
| [EmfVertexData](./emfvertexdata) | 指定矩形或三角形顶点的对象以及 对应于它们的颜色。 |
| [EmfWidenPath](./emfwidenpath) | 此记录将当前路径重新定义为如果 path 是使用当前选择到播放设备上下文中的笔绘制的区域。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
