---
title: "aspose.imaging.fileformats.emf.emf.records"
type: docs
weight: 400
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/
---


该模块包含类型 [MS-EMF]：增强型图元文件格式。2.3 EMF 记录

## **Classes**
| **Class** | **描述** |
| :- | :- |
| [EmfAbortPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfabortpath/) | 此记录中止路径括号或丢弃闭合路径括号中的路径。 |
| [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) | EMR_ALPHABLEND 记录指定将像素从源位图块传输到 <br/>            目标矩形的操作，包括 alpha 透明度数据，依据指定的混合操作。 |
| [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) | EMR_ANGLEARC 记录指定弧线的线段。该线段从 <br/>            当前位点绘制到弧线的起点。弧线沿着给定半径和中心的圆周绘制。弧线的长度由给定的起始角度和扫掠角度定义。 |
| [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) | EMR_ARC 记录指定椭圆弧。 |
| [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) | EMR_ARCTO 记录指定椭圆弧。它将当前位点重置为弧线的终点。 |
| [EmfBeginPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/) | 此记录在当前回放设备上下文中打开路径括号。<br/>            当路径括号打开后，应用程序可以开始处理记录以定义<br/>            位于路径中的点。应用程序必须通过处理 EMR_ENDPATH 记录来关闭打开的路径括号。<br/>            当应用程序处理 EMR_BEGINPATH 记录时，所有先前的路径<br/>            必须从回放设备上下文中丢弃。 |
| [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/) | 该 EMR_BITBLT 记录指定将像素块从源位图传输到目标<br/>            矩形，可选地结合画笔图案，依据指定的光栅操作。 |
| [EmfBitmapRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype/) | 该 位图 记录类型执行位图图像的块传输。 |
| [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | 一个结构指定源位图和目标位图的混合操作。 |
| [EmfBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/) | 基础 EMF polyshape 类。 |
| [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) | 该 EMR_CHORD 记录指定弦，弦是由椭圆与一条线段（称为割线）的交叉所界定的区域。<br/>            弦使用当前笔进行描边，并使用当前画刷进行填充。 |
| [EmfClippingRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype/) | 该 剪裁 记录类型指定并管理剪裁区域。<br/>            注：EMR_SETMETARGN 记录未指定参数。 |
| [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/) | 此记录关闭路径中的打开图形。<br/>            处理 EMR_CLOSEFIGURE 记录必须通过绘制一条线将当前位置信息连接到图形的第一个点来关闭图形，然后必须使用线段连接样式来连接这些线段。如果图形是通过处理 EMR_LINETO 记录而不是 EMR_CLOSEFIGURE 记录来关闭的，则使用端帽来创建拐角而不是连接。EMR_LINETO 在第 2.3.5.13 节中指定。<br/>            仅当回放设备上下文中存在打开的路径括号时，才应使用 EMR_CLOSEFIGURE 记录。<br/>            路径中的图形默认是打开的，除非通过处理此记录显式关闭。 |
| [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/) | 该 EMR_COLORCORRECTPALETTE 记录指定如何使用 WCS 1.0 值校正逻辑调色板<br/>            对象的条目。 |
| [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/) | 该 EMR_COLORMATCHTOTargetW 记录指定是否使用名称由 Unicode 字符组成的文件中指定的颜色<br/>            配置文件执行颜色匹配。 |
| [EmfComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcomment/) | 该 EMR_COMMENT 记录包含任意私有数据。<br/>            注：本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentBeginGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/) | 该 EMR_COMMENT_BEGINGROUP 记录指定一组绘图记录的开始。 |
| [EmfCommentEmfPlus](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/) | 该 EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF+ 记录。<br/>            注：本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) | 该 EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。<br/>            注：本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEndGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/) | 该 EMR_COMMENT_ENDGROUP 记录指定一组绘图记录的结束。 |
| [EmfCommentMultiFormats](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/) | 该 EMR_COMMENT_MULTIFORMATS 记录指定以多种图形格式呈现的图像。 |
| [EmfCommentPublicRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/) | 该 EMR_COMMENT_PUBLIC 记录类型指定对 EMF 处理的扩展。 |
| [EmfCommentRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/) | 该 注释 记录类型定义用于指定任意私有数据、在其他元文件格式中嵌入记录<br/>            以及添加新或特殊用途命令的格式。 |
| [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) | 该 EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像。 |
| [EmfControlRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype/) | 该 控制 记录类型定义 EMF 元文件的开始和结束以及元文件的属性。 |
| [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) | 该 EMR_CREATEBRUSHINDIRECT 记录定义用于图形操作的逻辑画刷。 |
| [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/) | 该 EMR_CREATECOLORSPACE 记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑色彩空间对象。<br/>             |
| [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) | 该 EMR_CREATECOLORSPACEW 记录从名称由 Unicode 字符组成的颜色配置文件创建逻辑色彩空间对象。<br/>             |
| [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/) | 该 EMR_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案画刷。<br/>            图案由 DIB 指定。 |
| [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/) | 该 EMR_CREATEMONOBRUSH 记录定义用于图形操作的单色图案画刷。<br/>            图案由单色 DIB 指定。 |
| [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) | 该 EMR_CREATEPALETTE 记录定义用于图形操作的逻辑调色板。 |
| [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/) | 该 EMR_CREATEPEN 记录定义用于图形操作的逻辑笔。 |
| [EmfDeleteColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/) | 该 EMR_DELETECOLORSPACE 记录删除逻辑颜色空间对象。 |
| [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) | 该 EMR_DELETEOBJECT 记录删除图形对象，该对象通过其在 EMF 对象表（第 3.1.1.1 节）中的索引指定。 |
| [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) | 该 EMR_DRAWESCAPE 记录将任意信息传递给打印机驱动程序。其意图是该<br/>            信息将导致执行绘图。 |
| [EmfDrawingRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype/) | 绘图记录类型执行图形绘制。 |
| [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) | 该 EMR_ELLIPSE 记录指定一个椭圆。椭圆的中心是指定的<br/>            边界矩形的中心。椭圆使用当前笔进行描边，并使用当前画刷进行填充。 |
| [EmfEndPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfendpath/) | 该记录关闭路径括号并将括号定义的路径选入<br/>            回放设备上下文。 |
| [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) | 该 EMR_EOF 记录指示元文件的结束并指定调色板。 |
| [EmfEscapeRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/) | 转义记录类型执行打印机驱动函数。 |
| [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) | 该 EMR_EXCLUDECLIPRECT 记录指定一个新的剪裁区域，该区域由现有的<br/>            剪裁区域减去指定的矩形组成。<br/>            注意：本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) | 该 EMR_EXTCREATEFONTINDIRECTW 记录定义用于图形操作的逻辑字体。 |
| [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) | 该 EMR_EXTCREATEPEN 记录定义用于图形操作的扩展逻辑笔。可以指定一个<br/>            可选的 DIB 作为线型。 |
| [EmfExtEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/) | 该 EMR_EXTESCAPE 记录将任意信息传递给打印机驱动程序。其意图是该<br/>            信息不会导致执行绘图。 |
| [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) | 该 EMR_EXTFLOODFILL 记录使用当前画刷填充显示表面的区域。 |
| [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) | 该 EMR_EXTSELECTCLIPRGN 记录使用指定模式将指定区域与当前剪裁区域<br/>            合并。<br/>            注意：本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/) | 该 EMR_EXTTEXTOUTA 记录使用当前字体和文本颜色绘制 ASCII 文本字符串。 |
| [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/) | 该 EMR_EXTTEXTOUTW 记录使用当前字体和文本颜色绘制 ASCII 文本字符串。 |
| [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/) | 该 EMR_FILLPATH 记录关闭当前路径中的所有打开图形，并通过<br/>            使用当前画刷和多边形填充模式来填充路径内部。 |
| [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) | 该 EMR_FILLRGN 记录使用指定的画刷填充指定的区域。 |
| [EmfFlatternPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfflatternpath/) | 该记录将选定路径中的所有曲线转换为回放设备<br/>            上下文；每条曲线必须转换为一系列直线。 |
| [EmfForceUfiMapping](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/) | 该 EMR_FORCEUFIMAPPING 记录强制字体映射器基于其<br/>            UniversalFontId 而非其 LogFont（第 2.2.13 节）信息来匹配字体。 |
| [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) | 该 EMR_FRAMERGN 记录使用指定的画刷在指定区域周围绘制边框。 |
| [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/) | 该 EMR_GLSBOUNDEDRECORD 记录指定一个带有输出边界矩形的 OpenGL 函数。 |
| [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/) | 该 EMR_GLSRECORD 记录指定一个 OpenGL 函数。 |
| [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/) | 该 EMR_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。 |
| [EmfIntersectClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/) | 该 EMR_INTERSECTCLIPRECT 记录指定从以下交集创建新的裁剪区域：<br/>            当前裁剪区域和指定的矩形。<br/>            注意：本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfInvertRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/) | 该 EMR_INVERTRGN 记录反转指定区域中的颜色。 |
| [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) | 该 EMR_LINETO 记录指定从当前点到（但不包括）<br/>            指定点的直线。它会将当前点重置为指定点。 |
| [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/) | 该 EMR_MASKBLT 记录指定将像素块从源位图传输到目标<br/>            矩形，可选地结合画笔图案并使用颜色掩码<br/>            位图，依据指定的前景和背景光栅操作。 |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | 该 EMR_HEADER 记录类型定义 EMF 元文件的起始点<br/>            并指定创建该元文件图像的设备属性。头记录中的信息使得<br/>            EMF 元文件能够独立于任何特定输出设备。<br/>            Size 字段的值可用于区分本节前面列出的不同<br/>            EMR_HEADER 记录类型。<br/>            有三种可能的头部：<br/>            基础头部，即 EmfMetafileHeader 记录。<br/>            此头部的固定大小部分为 88 字节，包含一个 Header 对象。<br/>            第一个扩展头部，即 EmfMetafileHeaderExtension1 记录。<br/>            此头部的固定大小部分为 100 字节，包含一个 Header 对象<br/>            和一个 HeaderExtension1 对象（第 2.2.10 节）。<br/>            第二个扩展头部，即 EmfMetafileHeaderExtension2 记录。<br/>            此头部的固定大小部分为 108 字节，包含一个 Header 对象、<br/>            一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。 |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | 该 EmfMetafileHeaderExtension1 记录是用于 EMF 元文件第一扩展的头记录。<br/>            在 EmfHeaderExtension1 字段之后，其余字段为可选，且可以以任意顺序出现。 |
| [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) | 该 EmfMetafileHeaderExtension2 记录是用于 EMF 元文件第二扩展的头记录。<br/>            在 EmfHeaderExtension2 字段之后，其余字段为可选，且可以以任意顺序出现。 |
| [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) | 该 EMR_MODIFYWORLDTRANSFORM 记录修改回放设备上下文中当前的世界空间到页面空间<br/>            的变换。 |
| [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/) | 该 EMR_MOVETOEX 记录指定新当前位置的坐标，使用逻辑单位。 |
| [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/) | 该 MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。 |
| [EmfObjectCreationRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype/) | 该对象创建记录类型创建图形对象。 |
| [EmfObjectManipulationRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype/) | 该对象操作记录类型管理并修改图形对象。 |
| [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) | 该 EMR_OFFSETCLIPRGN 记录移动回放设备上下文中的当前裁剪区域 <br/>            通过指定的偏移量。 |
| [EmfOpenGlRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype/) | 该 OpenGL 记录类型指定 OpenGL 函数。 |
| [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/) | 该 EMR_PAINTRGN 记录通过使用当前选入 <br/>            回放设备上下文的画刷来绘制指定区域。 |
| [EmfPathBracketRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype/) | 该路径括号记录类型指定并操作路径括号中的路径。<br/>            注意：路径括号记录不指定任何参数。 |
| [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) | 该 EMR_PIE 记录指定由椭圆与两条<br/>            径向线的交叉形成的扇形楔块。该扇形使用当前笔描边，并使用当前画刷填充。 |
| [EmfPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpixelformat/) | 该 EMR_PIXELFORMAT 记录指定用于图形操作的像素格式。 |
| [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) | 该 EMR_PLGBLT 记录指定将像素块从源位图传输到目标<br/>            平行四边形，并使用颜色掩码位图。 |
| [EmfPolyBezier](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier/) | 该 EMR_POLYBEZIER 记录指定一个或多个贝塞尔曲线。 |
| [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) | 该 EMR_POLYBEZIER16 记录指定一个或多个贝塞尔曲线。这些曲线使用<br/>            当前笔绘制。 |
| [EmfPolyBezierTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/) | 该 EMR_POLYBEZIERTO 记录指定基于当前点的一个或多个贝塞尔曲线。 |
| [EmfPolyBezierTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/) | 该 EMR_POLYBEZIERTO16 记录指定基于当前点的一个或多个贝塞尔曲线。 |
| [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/) | 该 EMR_POLYDRAW 记录指定一组线段和贝塞尔曲线。 |
| [EmfPolyDraw16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/) | EMR_POLYDRAW16 记录指定一组线段和贝塞尔曲线。 |
| [EmfPolyPolyShape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape/) | 基础 EMF 多边形 polyshape 类。 |
| [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) | EMR_POLYPOLYGON 记录指定一系列闭合多边形。 |
| [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) | EMR_POLYPOLYGON16 记录指定一系列闭合多边形。每个多边形使用当前笔进行描边，<br/>            并使用当前画刷和多边形填充模式进行填充。此记录绘制的多边形<br/>            可以重叠。 |
| [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/) | EMR_POLYPOLYLINE 记录指定多个相连线段的系列。 |
| [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) | EMR_POLYPOLYLINE16 记录指定多个相连线段的系列。 |
| [EmfPolyShape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyshape/) | 基础 EMF polyshape 类。 |
| [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/) | EMR_POLYTEXTOUTA 记录使用当前字体和文字颜色绘制一个或多个 ASCII 文本字符串。 |
| [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/) | EMR_POLYTEXTOUTW 记录使用当前字体和文字颜色绘制一个或多个 Unicode 文本字符串。 |
| [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) | EMR_POLYGON 记录指定一个由两个或多个顶点通过<br/>            直线相连组成的多边形。 |
| [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) | EMR_POLYGON16 记录指定一个由两个或多个顶点通过<br/>            直线相连组成的多边形。该多边形使用当前笔进行描边，并使用当前画刷<br/>            和多边形填充模式进行填充。多边形会自动闭合，通过从最后一个顶点绘制一条线到第一个顶点实现。 |
| [EmfPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline/) | EMR_POLYLINE 记录通过连接指定数组中的点来指定一系列线段。<br/>             |
| [EmfPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolyline16/) | EMR_POLYLINE16 记录通过连接指定数组中的点来指定一系列线段。<br/>             |
| [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) | EMR_POLYLINETO 记录基于当前位置信息指定一个或多个直线。 |
| [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) | EMR_POLYLINETO16 记录基于当前位置信息指定一个或多个直线。<br/>            使用当前笔，从当前位置信息绘制一条线到 aPoints 字段指定的第一个点。对于每条后续直线，绘制过程从前一条线的结束点开始，连接到 aPoints 指定的下一个点。 |
| [EmfRealizePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrealizepalette/) | 此记录将当前<br/>            LogPalette 对象（第 2.2.17 节）的调色板条目映射到 system_palette。<br/>            此 EMF 记录不包含任何参数。 |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | EMF 记录的基类<br/>            所有 EMF 记录的长度必须是 4 字节的整数倍。这在前述 EMF 记录类型的通用结构中通过在这些结构的末尾适当加入 AlignmentPadding 字段来体现。AlignmentPadding 字段的内容必须始终被忽略。为简洁起见，这些字段未在每个单独的 EMF 记录定义中显示。 |
| [EmfRectangle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/) | EMR_RECTANGLE 记录绘制一个矩形。该矩形使用当前笔进行描边<br/>            并使用当前画刷进行填充。 |
| [EmfResizePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/) | EMR_RESIZEPALETTE 记录增大或缩小现有 LogPalette 对象（第 2.2.17 节）的大小。 |
| [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) | EMR_RESTOREDC 记录将回放设备上下文恢复到指定状态。<br/>            回放设备上下文通过弹出先前 EMR_SAVEDC 记录（第 2.3.11 节）创建的状态栈来实现恢复。 |
| [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | 四元光栅操作，指定位图前景色和背景色的三元光栅操作。<br/>            这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据进行组合。 |
| [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) | EMR_ROUNDRECT 记录指定一个带圆角的矩形。该矩形使用当前笔进行描边<br/>            并使用当前画刷进行填充。 |
| [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) | 将回放设备上下文的当前状态保存到由之前的 EMR_SAVEDC<br/>            记录（如果有）保存的状态栈上。该状态包括图形属性<br/>            和对象，包括当前选中的位图、<br/>            画刷、调色板、字体、笔和区域。使用<br/>            EMR_RESTOREDC 记录来恢复该状态。<br/>            此 EMF 记录不包含任何参数。 |
| [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) | EMR_SCALEVIEWPORTEXTEX 记录通过使用<br/>            指定的乘数和除数形成的比率，重新指定设备上下文的视口。 |
| [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) | EMR_SCALEWINDOWEXTEX 记录通过<br/>            使用指定的乘数和除数形成的比率，重新指定回放设备上下文的窗口。 |
| [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) | EMR_SELECTCLIPPATH 记录将当前路径指定为回放<br/>            设备上下文的裁剪区域，并使用指定的模式将新区域与任何现有裁剪区域合并。 |
| [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) | The EMR_SELECTOBJECT 记录将图形对象添加到当前元文件回放设备<br/>            上下文。该对象可以通过其在 EMF 对象表（第 3.1.1.1 节）中的索引或通过其<br/>            来自 StockObject 枚举（第 2.1.31 节）的值来指定。 |
| [EmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/) | EMR_SELECTPALETTE 记录指定回放设备上下文的逻辑调色板。 |
| [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/) | EMR_SETARCDIRECTION 记录指定用于弧和矩形输出的绘制方向。 |
| [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/) | EMR_SETBKCOLOR 记录指定背景颜色。 |
| [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) | EMR_SETBKMODE 记录指定回放设备上下文的背景混合模式。<br/>            背景混合模式用于文本、带状刷和非实线的笔样式。 |
| [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) | EMR_SETBRUSHORGEX 记录指定当前画刷的原点。 |
| [EmfSetColorAdjustment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/) | EMR_SETCOLORADJUSTMENT 记录指定回放<br/>            设备上下文中的颜色调整属性。 |
| [EmfSetColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/) | EMR_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象。 |
| [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) | EMR_SETDIBITSTODEVICE 记录指定从源位图的指定扫描线<br/>            到目标矩形的像素块传输。 |
| [EmfSetIcmMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/) | EMR_SETICMMODE 记录指定图形操作的图像颜色管理 (ICM) 模式。 |
| [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/) | EMR_SETICMPROFILEA 记录指定用于图形输出的、文件名由 ASCII<br/>            字符组成的颜色配置文件。 |
| [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) | EMR_SETICMPROFILEW 记录指定用于图形输出的、文件名由<br/>            Unicode 字符组成的颜色配置文件。 |
| [EmfSetLayout](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlayout/) | EMR_SETLAYOUT 记录指定文本和图形的绘制顺序。 |
| [EmfSetLinkedUfis](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetlinkedufis/) | EMR_SETLINKEDUFIS 记录设置在字符查找期间使用的链接字体的 UniversalFontIds（第 2.2.27 节）<br/>            。 |
| [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) | EMR_SETMAPMODE 记录指定回放设备上下文的映射模式。<br/>            映射模式指定用于将页面空间单位转换为设备空间单位的度量单位，<br/>            并且还指定设备的 x 轴和 y 轴的方向。 |
| [EmfSetMapperFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/) | EMR_SETMAPPERFLAGS 记录指定将逻辑字体匹配到<br/>            物理字体的过程参数，该过程由字体映射器执行。 |
| [EmfSetMetaRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmetargn/) | Inter 将当前元区域与当前裁剪区域<br/>            合并，以形成回放设备上下文的新元区域。当前裁剪区域应被重置为 null。<br/>            此 EMF 记录不指定任何参数。 |
| [EmfSetMiterLimit](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/) | EMR_SETMITERLIMIT 记录指定回放设备上下文中斜接连接长度的限制。 |
| [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) | EMR_SETPALETTEENTRIES 记录为现有的<br/>            LogPalette（第 2.2.17 节）对象的条目范围定义 RGB 颜色值。 |
| [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) | EMR_SETPIXELV 记录定义指定逻辑坐标处像素的颜色。 |
| [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) | EMR_SETPOLYFILLMODE 记录定义多边形填充模式。 |
| [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) | EMR_SETROP2 记录定义二进制光栅操作模式。 |
| [EmfSetStrechBltMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/) | EMR_SETSTRETCHBLTMODE 记录指定位图拉伸模式。 |
| [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) | EMR_SETTEXTALIGN 记录指定文本对齐方式。 |
| [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) | EMR_SETTEXTCOLOR 记录定义当前文本颜色。 |
| [EmfSetTextJustification](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/) | EMR_SETTEXTJUSTIFICATION 记录指定要在换行<br/>字符之间添加的额外空间量，以实现文本对齐。 |
| [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) | EMR_SETVIEWPORTEXTEX 记录定义视口范围。 |
| [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) | EMR_SETVIEWPORTORGEX 记录定义视口原点。 |
| [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/) | EMR_SETWINDOWEXTEX 记录定义窗口范围。 |
| [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) | EMR_SETWINDOWORGEX 记录定义窗口原点。 |
| [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) | EMR_SETWORLDTRANSFORM 记录指定在回放设备上下文中，将当前世界空间转换为页面空间的变换。 |
| [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) | EMR_SMALLTEXTOUT 记录输出字符串。 |
| [EmfStateRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype/) | 状态记录类型指定并管理定义回放设备上下文状态的图形属性。 |
| [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) | EMR_STRETCHBLT 记录指定将像素块从源位图传输到一个<br/>目标矩形， 可选地结合画刷图案， 根据指定的光栅<br/>操作， 如有必要， 拉伸或压缩输出以适应目标的尺寸。 |
| [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/) | EMR_STRETCHDIBITS 记录指定将像素块从源位图传输到一个<br/>目标矩形， 可选地结合画刷图案， 根据指定的光栅<br/>操作， 如有必要， 拉伸或压缩输出以适应目标的尺寸。 |
| [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) | EMR_STROKEANDFILLPATH 记录关闭路径中所有未闭合的图形， 使用当前画笔描绘路径的轮廓<br/>并使用当前画刷填充其内部。 |
| [EmfStrokePath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokepath/) | EMR_STROKEPATH 类 |
| [EmfTransformRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype/) | 变换记录类型指定并修改世界空间到页面空间的变换。 |
| [EmfTransparentBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/) | EMR_TRANSPARENTBLT 记录指定将像素块从源位图传输到一个<br/>目标矩形，将指定颜色视为透明， 如有必要， 拉伸或压缩输出以适应目标的尺寸。 |
| [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | 对象指定矩形或三角形的顶点以及<br/>对应的颜色。 |
| [EmfWidenPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfwidenpath/) | 此记录将当前路径重新定义为如果使用当前在回放设备上下文中选定的画笔绘制路径时将被填充的区域<br/>。 |
## **Enumerations**
| **Enumeration** | **描述** |
| :- | :- |
