---
title: "Aspose.Imaging.FileFormats.Emf.Emf.Records"
second_title: "Aspose.Imaging for .NET API 参考"
description: "该命名空间包含类型 MSEMF Enhanced Metafile Format。2.3 EMF 记录"
type: docs
weight: 400
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/
---
该命名空间包含类型 [MS-EMF]：增强型图元文件格式。2.3 EMF 记录

## 类

| 类 | 描述 |
| --- | --- |
| [EmfAbortPath](./emfabortpath/) | 此记录中止路径括号或从已关闭的路径括号中丢弃路径。 |
| [EmfAlphaBlend](./emfalphablend/) | EMR_ALPHABLEND 记录指定将像素块从源位图传输到目标矩形，包括 alpha 透明度数据，依据指定的混合操作。 |
| [EmfAngleArc](./emfanglearc/) | EMR_ANGLEARC 记录指定弧的线段。该线段从当前位置信息绘制到弧的起点。弧沿具有给定半径和中心的圆周绘制。弧的长度由给定的起始角度和扫掠角度决定。 |
| [EmfArc](./emfarc/) | EMR_ARC 记录指定椭圆弧。 |
| [EmfArcTo](./emfarcto/) | EMR_ARCTO 记录指定椭圆弧。它将当前位置信息重置为弧的终点。 |
| [EmfBeginPath](./emfbeginpath/) | 此记录在当前回放设备上下文中打开路径括号。路径括号打开后，应用程序可以开始处理记录以定义路径中的点。应用程序必须通过处理 EMR_ENDPATH 记录来关闭打开的路径括号。当应用程序处理 EMR_BEGINPATH 记录时，所有先前的路径必须从回放设备上下文中丢弃。 |
| [EmfBitBlt](./emfbitblt/) | EMR_BITBLT 记录指定将像素块从源位图传输到目标矩形，可选地结合画笔图案，依据指定的光栅操作。 |
| [EmfBitmapRecordType](./emfbitmaprecordtype/) | 位图记录类型执行位图图像的块传输。 |
| [EmfBoundedRecord](./emfboundedrecord/) | EMF 多边形基类。 |
| [EmfChord](./emfchord/) | EMR_CHORD 记录指定弦线，即由椭圆与一条线段（称为割线）相交形成的区域。弦线使用当前笔进行描边，并使用当前画刷进行填充。 |
| [EmfClippingRecordType](./emfclippingrecordtype/) | 剪裁记录类型指定并管理剪裁区域。注意 EMR_SETMETARGN 记录不指定参数。 |
| [EmfCloseFigure](./emfclosefigure/) | 此记录关闭路径中的打开图形。处理 EMR_CLOSEFIGURE 记录时必须通过从当前位置信息绘制到图形的第一个点来关闭图形，然后必须使用线段连接样式连接这些线段。如果图形是通过处理 EMR_LINETO 记录而不是 EMR_CLOSEFIGURE 记录来关闭的，则使用端帽来创建拐角而不是连接。EMR_LINETO 在第 2.3.5.13 节中指定。只有在回放设备上下文中存在打开的路径括号时才应使用 EMR_CLOSEFIGURE 记录。路径中的图形默认是打开的，除非通过处理此记录显式关闭。 |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette/) | EMR_COLORCORRECTPALETTE 记录指定如何使用 WCS 1.0 值校正逻辑调色板对象的条目。 |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw/) | EMR_COLORMATCHTOTargetW 记录指定是否使用文件名为 Unicode 字符的颜色配置文件进行颜色匹配。 |
| [EmfComment](./emfcomment/) | EMR_COMMENT 记录包含任意私有数据。注意，本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentBeginGroup](./emfcommentbegingroup/) | EMR_COMMENT_BEGINGROUP 记录指定一组绘图记录的开始。 |
| [EmfCommentEmfPlus](./emfcommentemfplus/) | EMR_COMMENT_EMFPLUS 记录包含嵌入的 EMF+ 记录。注意，本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEmfSpool](./emfcommentemfspool/) | EMR_COMMENT_EMFSPOOL 记录包含嵌入的 EMFSPOOL 记录。注意，本节未描述的字段在第 2.3.3 节中指定。 |
| [EmfCommentEndGroup](./emfcommentendgroup/) | EMR_COMMENT_ENDGROUP 记录指定一组绘图记录的结束。 |
| [EmfCommentMultiFormats](./emfcommentmultiformats/) | EMR_COMMENT_MULTIFORMATS 记录指定多种图形格式的图像。 |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype/) | EMR_COMMENT_PUBLIC 记录类型指定对 EMF 处理的扩展。 |
| [EmfCommentRecordType](./emfcommentrecordtype/) | 注释记录类型定义了用于指定任意私有数据、在其他元文件格式中嵌入记录以及添加新或特殊用途命令的格式。 |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile/) | EMR_COMMENT_WINDOWS_METAFILE 记录指定嵌入 WMF 元文件中的图像。 |
| [EmfControlRecordType](./emfcontrolrecordtype/) | 控制记录类型定义 EMF 元文件的开始和结束以及元文件的属性。 |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect/) | EMR_CREATEBRUSHINDIRECT 记录定义用于图形操作的逻辑画刷。 |
| [EmfCreateColorSpace](./emfcreatecolorspace/) | EMR_CREATECOLORSPACE 记录从名称由 ASCII 字符组成的颜色配置文件创建逻辑颜色空间对象。 |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew/) | EMR_CREATECOLORSPACEW 记录从名称由 Unicode 字符组成的颜色配置文件创建逻辑颜色空间对象。 |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt/) | EMR_CREATEDIBPATTERNBRUSHPT 记录定义用于图形操作的图案画刷。该图案由 DIB 指定。 |
| [EmfCreateMonoBrush](./emfcreatemonobrush/) | EMR_CREATEMONOBRUSH 记录定义用于图形操作的单色图案画刷。该图案由单色 DIB 指定。 |
| [EmfCreatePalette](./emfcreatepalette/) | EMR_CREATEPALETTE 记录定义用于图形操作的逻辑调色板。 |
| [EmfCreatePen](./emfcreatepen/) | EMR_CREATEPEN 记录定义用于图形操作的逻辑钢笔。 |
| [EmfDeleteColorSpace](./emfdeletecolorspace/) | EMR_DELETECOLORSPACE 记录删除逻辑颜色空间对象。 |
| [EmfDeleteObject](./emfdeleteobject/) | EMR_DELETEOBJECT 记录删除图形对象，该对象通过其在 EMF 对象表（第 3.1.1.1 节）中的索引指定。 |
| [EmfDrawEscape](./emfdrawescape/) | EMR_DRAWESCAPE 记录向打印机驱动程序传递任意信息。其目的是使这些信息导致绘图操作。 |
| [EmfDrawingRecordType](./emfdrawingrecordtype/) | 绘图记录类型执行图形绘制。 |
| [EmfEllipse](./emfellipse/) | EMR_ELLIPSE 记录指定一个椭圆。椭圆的中心是指定的边界矩形的中心。椭圆使用当前钢笔描边，使用当前画刷填充。 |
| [EmfEndPath](./emfendpath/) | 此记录关闭路径括号并将括号定义的路径选入回放设备上下文。 |
| [EmfEof](./emfeof/) | EMR_EOF 记录指示元文件的结束并指定调色板。 |
| [EmfEscapeRecordType](./emfescaperecordtype/) | 转义记录类型执行打印机驱动程序函数。 |
| [EmfExcludeClipRect](./emfexcludecliprect/) | EMR_EXCLUDECLIPRECT 记录指定一个新的裁剪区域，该区域由现有裁剪区域减去指定的矩形组成。注意，本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw/) | EMR_EXTCREATEFONTINDIRECTW 记录定义用于图形操作的逻辑字体。 |
| [EmfExtCreatePen](./emfextcreatepen/) | EMR_EXTCREATEPEN 记录定义用于图形操作的扩展逻辑笔。可以指定可选的 DIB 作为线型。 |
| [EmfExtEscape](./emfextescape/) | EMR_EXTESCAPE 记录向打印机驱动程序传递任意信息。其意图是这些信息不会导致绘图操作。 |
| [EmfExtFloodFill](./emfextfloodfill/) | EMR_EXTFLOODFILL 记录使用当前画刷填充显示表面的区域。 |
| [EmfExtSelectClipRgn](./emfextselectcliprgn/) | EMR_EXTSELECTCLIPRGN 记录使用指定模式将指定区域与当前裁剪区域合并。注意，本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfExtTextOutA](./emfexttextouta/) | EMR_EXTTEXTOUTA 记录使用当前字体和文字颜色绘制 ASCII 文本字符串。 |
| [EmfExtTextOutW](./emfexttextoutw/) | EMR_EXTTEXTOUTW 记录使用当前字体和文字颜色绘制 ASCII 文本字符串。 |
| [EmfFillPath](./emffillpath/) | EMR_FILLPATH 记录关闭当前路径中的所有未闭合图形，并使用当前画刷和多边形填充模式填充路径内部。 |
| [EmfFillRgn](./emffillrgn/) | EMR_FILLRGN 记录使用指定的画刷填充指定的区域。 |
| [EmfFlatternPath](./emfflatternpath/) | 此记录将选定路径中的所有曲线转换为回放设备上下文；每条曲线必须转换为一系列直线。 |
| [EmfForceUfiMapping](./emfforceufimapping/) | EMR_FORCEUFIMAPPING 记录强制字体映射器优先根据其 UniversalFontId 而非 LogFont（第 2.2.13 节）信息匹配字体。 |
| [EmfFrameRgn](./emfframergn/) | EMR_FRAMERGN 记录使用指定的画刷在指定区域周围绘制边框。 |
| [EmfGlsBoundedRecord](./emfglsboundedrecord/) | EMR_GLSBOUNDEDRECORD 记录指定一个带有输出边界矩形的 OpenGL 函数。 |
| [EmfGlsRecord](./emfglsrecord/) | EMR_GLSRECORD 记录指定一个 OpenGL 函数。 |
| [EmfGradientFill](./emfgradientfill/) | EMR_GRADIENTFILL 记录指定使用颜色渐变填充矩形或三角形。 |
| [EmfIntersectClipRect](./emfintersectcliprect/) | EMR_INTERSECTCLIPRECT 记录指定一个新的裁剪区域，该区域为当前裁剪区域与指定矩形的交集。注意，本节未描述的字段在第 2.3.2 节中指定。 |
| [EmfInvertRgn](./emfinvertrgn/) | EMR_INVERTRGN 记录反转指定区域的颜色。 |
| [EmfLineTo](./emflineto/) | EMR_LINETO 记录指定一条从当前点到指定点（但不包括该点）的直线。它将当前点重置为指定点。 |
| [EmfMaskBlt](./emfmaskblt/) | EMR_MASKBLT 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案并应用颜色掩码位图，依据指定的前景和背景光栅操作。 |
| [EmfMetafileHeader](./emfmetafileheader/) | EMR_HEADER 记录类型定义了 EMF 元文件的起始点，并指定创建该元文件图像的设备属性。头部记录中的信息使 EMF 元文件能够独立于任何特定输出设备。Size 字段的值可用于区分本节前面列出的不同 EMR_HEADER 记录类型。共有三种可能的头部：基础头部，即 EmfMetafileHeader 记录。该头部的固定大小部分为 88 字节，包含一个 Header 对象。第一扩展头部，即 EmfMetafileHeaderExtension1 记录。该头部的固定大小部分为 100 字节，包含一个 Header 对象和一个 HeaderExtension1 对象（第 2.2.10 节）。第二扩展头部，即 EmfMetafileHeaderExtension2 记录。该头部的固定大小部分为 108 字节，包含一个 Header 对象、一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。 |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1/) | EmfMetafileHeaderExtension1 记录是 EMF 元文件第一扩展中使用的头部记录。在 EmfHeaderExtension1 字段之后，其余字段为可选，可按任意顺序出现。 |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2/) | EmfMetafileHeaderExtension2 记录是 EMF 元文件第二扩展中使用的头部记录。在 EmfHeaderExtension2 字段之后，其余字段为可选，可按任意顺序出现。 |
| [EmfModifyWorldTransform](./emfmodifyworldtransform/) | EMR_MODIFYWORLDTRANSFORM 记录修改回放设备上下文中当前的世界空间到页面空间的变换。 |
| [EmfMoveToEx](./emfmovetoex/) | EMR_MOVETOEX 记录以逻辑单位指定新当前位置的坐标。 |
| [EmfNamedEscape](./emfnamedescape/) | MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。 |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype/) | 对象创建记录类型创建图形对象。 |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype/) | 对象操作记录类型管理并修改图形对象。 |
| [EmfOffsetClipRgn](./emfoffsetcliprgn/) | EMR_OFFSETCLIPRGN 记录通过指定的偏移量移动回放设备上下文中的当前裁剪区域。 |
| [EmfOpenGlRecordType](./emfopenglrecordtype/) | OpenGL 记录类型指定 OpenGL 函数。 |
| [EmfPaintRgn](./emfpaintrgn/) | EMR_PAINTRGN 记录使用当前在回放设备上下文中选中的画刷绘制指定区域。 |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype/) | 路径括号记录类型指定并操作路径括号中的路径。注意：路径括号记录不指定参数。 |
| [EmfPie](./emfpie/) | EMR_PIE 记录指定由椭圆与两条径线交叉形成的扇形楔。该扇形使用当前画笔描边，并使用当前画刷填充。 |
| [EmfPixelFormat](./emfpixelformat/) | EMR_PIXELFORMAT 记录指定用于图形操作的像素格式。 |
| [EmfPlgBlt](./emfplgblt/) | EMR_PLGBLT 记录指定将像素从源位图块传输到目标平行四边形，并应用颜色掩码位图。 |
| [EmfPolyBezier](./emfpolybezier/) | EMR_POLYBEZIER 记录指定一个或多个贝塞尔曲线。 |
| [EmfPolyBezier16](./emfpolybezier16/) | EMR_POLYBEZIER16 记录指定一个或多个贝塞尔曲线。曲线使用当前画笔绘制。 |
| [EmfPolyBezierTo](./emfpolybezierto/) | EMR_POLYBEZIERTO 记录指定基于当前位置信息的一个或多个贝塞尔曲线。 |
| [EmfPolyBezierTo16](./emfpolybezierto16/) | EMR_POLYBEZIERTO16 记录指定基于当前位置信息的一个或多个贝塞尔曲线。 |
| [EmfPolyDraw](./emfpolydraw/) | EMR_POLYDRAW 记录指定一组线段和贝塞尔曲线。 |
| [EmfPolyDraw16](./emfpolydraw16/) | EMR_POLYDRAW16 记录指定一组线段和贝塞尔曲线。 |
| [EmfPolygon](./emfpolygon/) | EMR_POLYGON 记录指定由两个或更多顶点通过直线连接组成的多边形。 |
| [EmfPolygon16](./emfpolygon16/) | EMR_POLYGON16 记录指定由两个或更多顶点通过直线连接组成的多边形。该多边形使用当前画笔描边，使用当前画刷和多边形填充模式填充。通过从最后一个顶点绘制到第一个顶点的线条，自动闭合多边形。 |
| [EmfPolyline](./emfpolyline/) | EMR_POLYLINE 记录通过连接指定数组中的点来指定一系列线段。 |
| [EmfPolyline16](./emfpolyline16/) | EMR_POLYLINE16 记录通过连接指定数组中的点来指定一系列线段。 |
| [EmfPolylineTo](./emfpolylineto/) | EMR_POLYLINETO 记录指定基于当前位置信息的一个或多个直线。 |
| [EmfPolylineTo16](./emfpolylineto16/) | EMR_POLYLINETO16 记录指定基于当前位置信息的一个或多个直线。使用当前画笔从当前位置信息绘制到 aPoints 字段指定的第一个点。对于每条后续直线，从前一条线的结束点绘制到 aPoints 指定的下一个点。 |
| [EmfPolyPolygon](./emfpolypolygon/) | EMR_POLYPOLYGON 记录指定一系列闭合多边形。 |
| [EmfPolyPolygon16](./emfpolypolygon16/) | EMR_POLYPOLYGON16 记录指定一系列闭合多边形。每个多边形使用当前画笔描边，使用当前画刷和多边形填充模式填充。此记录绘制的多边形可以重叠。 |
| [EmfPolyPolyline](./emfpolypolyline/) | EMR_POLYPOLYLINE 记录指定多个相连线段的系列。 |
| [EmfPolyPolyline16](./emfpolypolyline16/) | EMR_POLYPOLYLINE16 记录指定多个相连线段的系列。 |
| [EmfPolyPolyShape](./emfpolypolyshape/) | 基础 EMF 多边形多形状类。 |
| [EmfPolyShape](./emfpolyshape/) | EMF 多边形基类。 |
| [EmfPolyTextOutA](./emfpolytextouta/) | 该 EMR_POLYTEXTOUTA 记录使用当前字体和文本颜色绘制一个或多个 ASCII 文本字符串。 |
| [EmfPolyTextOutW](./emfpolytextoutw/) | 该 EMR_POLYTEXTOUTW 记录使用当前字体和文本颜色绘制一个或多个 Unicode 文本字符串。 |
| [EmfRealizePalette](./emfrealizepalette/) | 此记录将当前 LogPalette 对象（第 2.2.17 节）中的调色板条目映射到 system_palette。此 EMF 记录不指定任何参数。 |
| [EmfRecord](./emfrecord/) | EMF 记录的基类。所有 EMF 记录的长度必须是 4 字节的倍数。这在前述 EMF 记录类型的通用结构中通过在这些结构的末尾适当加入 AlignmentPadding 字段来体现。AlignmentPadding 字段的内容必须始终被忽略。为简洁起见，这些字段未在每个单独的 EMF 记录定义中显示。 |
| [EmfRectangle](./emfrectangle/) | 该 EMR_RECTANGLE 记录绘制一个矩形。矩形使用当前笔进行描边，使用当前刷子进行填充。 |
| [EmfResizePalette](./emfresizepalette/) | 该 EMR_RESIZEPALETTE 记录增大或减小现有 LogPalette 对象（第 2.2.17 节）的大小。 |
| [EmfRestoreDc](./emfrestoredc/) | 该 EMR_RESTOREDC 记录将回放设备上下文恢复到指定状态。回放设备上下文通过弹出先前 EMR_SAVEDC 记录（第 2.3.11 节）创建的堆栈中的状态信息来恢复。 |
| [EmfRop4](./emfrop4/) | 四元光栅操作，指定位图前景色和背景色的三元光栅操作。这些值定义了如何将源矩形的颜色数据与目标矩形的颜色数据组合。 |
| [EmfRoundRect](./emfroundrect/) | 该 EMR_ROUNDRECT 记录指定一个带圆角的矩形。矩形使用当前笔进行描边，使用当前刷子进行填充。 |
| [EmfSaveDc](./emfsavedc/) | 将回放设备上下文的当前状态保存到由先前 EMR_SAVEDC 记录（如果有）保存的状态堆栈中。该状态包括图形属性和对象，包括当前选中的位图、刷子、调色板、字体、笔和区域。使用 EMR_RESTOREDC 记录来恢复该状态。此 EMF 记录不指定任何参数。 |
| [EmfScaleViewportExtex](./emfscaleviewportextex/) | 该 EMR_SCALEVIEWPORTEXTEX 记录通过使用指定的乘数和除数形成的比例重新指定设备上下文的视口。 |
| [EmfScaleWindowExtex](./emfscalewindowextex/) | 该 EMR_SCALEWINDOWEXTEX 记录通过使用指定的乘数和除数形成的比例重新指定回放设备上下文的窗口。 |
| [EmfSelectClipPath](./emfselectclippath/) | 该 EMR_SELECTCLIPPATH 记录将当前路径指定为回放设备上下文的剪裁区域，并使用指定的模式将新区域与任何现有剪裁区域合并。 |
| [EmfSelectObject](./emfselectobject/) | 该 EMR_SELECTOBJECT 记录向当前元文件回放设备上下文添加一个图形对象。该对象可以通过其在 EMF 对象表（第 3.1.1.1 节）中的索引或通过其在 StockObject 枚举（第 2.1.31 节）中的值来指定。 |
| [EmfSelectPalette](./emfselectpalette/) | 该 EMR_SELECTPALETTE 记录为回放设备上下文指定逻辑调色板。 |
| [EmfSetArcDirection](./emfsetarcdirection/) | 该 EMR_SETARCDIRECTION 记录指定用于弧线和矩形输出的绘制方向。 |
| [EmfSetBkColor](./emfsetbkcolor/) | 该 EMR_SETBKCOLOR 记录指定背景颜色。 |
| [EmfSetBkMode](./emfsetbkmode/) | 该 EMR_SETBKMODE 记录指定回放设备上下文的背景混合模式。背景混合模式用于文本、带纹理的刷子以及非实线的笔样式。 |
| [EmfSetBrushOrgEx](./emfsetbrushorgex/) | 该 EMR_SETBRUSHORGEX 记录指定当前刷子的原点。 |
| [EmfSetColorAdjustment](./emfsetcoloradjustment/) | 该 EMR_SETCOLORADJUSTMENT 记录在回放设备上下文中指定颜色调整属性。 |
| [EmfSetColorSpace](./emfsetcolorspace/) | 该 EMR_SETCOLORSPACE 记录定义用于图形操作的当前逻辑颜色空间对象。 |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice/) | 该 EMR_SETDIBITSTODEVICE 记录指定将像素从源位图的指定扫描线块传输到目标矩形。 |
| [EmfSetIcmMode](./emfseticmmode/) | 该 EMR_SETICMMODE 记录指定图形操作的图像颜色管理 (ICM) 模式。 |
| [EmfSetIcmProfileA](./emfseticmprofilea/) | EMR_SETICMPROFILEA 记录指定在文件中使用由 ASCII 字符组成的名称的颜色配置文件，用于图形输出。 |
| [EmfSetIcmProfileW](./emfseticmprofilew/) | EMR_SETICMPROFILEW 记录指定在文件中使用由 Unicode 字符组成的名称的颜色配置文件，用于图形输出。 |
| [EmfSetLayout](./emfsetlayout/) | EMR_SETLAYOUT 记录指定文本和图形的绘制顺序。 |
| [EmfSetLinkedUfis](./emfsetlinkedufis/) | EMR_SETLINKEDUFIS 记录设置在字符查找期间使用的链接字体的 UniversalFontIds（第 2.2.27 节）。 |
| [EmfSetMapMode](./emfsetmapmode/) | EMR_SETMAPMODE 记录指定回放设备上下文的映射模式。映射模式指定用于将页面空间单位转换为设备空间单位的度量单位，并且还指定设备的 x 轴和 y 轴的方向。 |
| [EmfSetMapperFlags](./emfsetmapperflags/) | EMR_SETMAPPERFLAGS 记录指定字体映射器执行的将逻辑字体匹配到物理字体的过程参数。 |
| [EmfSetMetaRgn](./emfsetmetargn/) | Inter 将当前元区域与当前裁剪区域合并，以形成回放设备上下文的新元区域。当前裁剪区域应重置为 null。此 EMF 记录不指定任何参数。 |
| [EmfSetMiterLimit](./emfsetmiterlimit/) | EMR_SETMITERLIMIT 记录指定回放设备上下文的斜接连接长度限制。 |
| [EmfSetPaletteEntries](./emfsetpaletteentries/) | EMR_SETPALETTEENTRIES 记录为现有的 LogPalette（第 2.2.17 节）对象的若干条目定义 RGB 颜色值。 |
| [EmfSetPixelV](./emfsetpixelv/) | EMR_SETPIXELV 记录定义指定逻辑坐标处像素的颜色。 |
| [EmfSetPolyFillMode](./emfsetpolyfillmode/) | EMR_SETPOLYFILLMODE 记录定义多边形填充模式。 |
| [EmfSetRop2](./emfsetrop2/) | EMR_SETROP2 记录定义二进制光栅操作模式。 |
| [EmfSetStrechBltMode](./emfsetstrechbltmode/) | EMR_SETSTRETCHBLTMODE 记录指定位图拉伸模式。 |
| [EmfSetTextAlign](./emfsettextalign/) | EMR_SETTEXTALIGN 记录指定文本对齐方式。 |
| [EmfSetTextColor](./emfsettextcolor/) | EMR_SETTEXTCOLOR 记录定义当前文本颜色。 |
| [EmfSetTextJustification](./emfsettextjustification/) | EMR_SETTEXTJUSTIFICATION 记录指定为文本两端对齐在换行字符处添加的额外空间量。 |
| [EmfSetViewportExtEx](./emfsetviewportextex/) | EMR_SETVIEWPORTEXTEX 记录定义视口范围。 |
| [EmfSetViewportOrgEx](./emfsetviewportorgex/) | EMR_SETVIEWPORTORGEX 记录定义视口原点。 |
| [EmfSetWindowExtEx](./emfsetwindowextex/) | EMR_SETWINDOWEXTEX 记录定义窗口范围。 |
| [EmfSetWindowOrgEx](./emfsetwindoworgex/) | EMR_SETWINDOWORGEX 记录定义窗口原点。 |
| [EmfSetWorldTransform](./emfsetworldtransform/) | EMR_SETWORLDTRANSFORM 记录指定回放设备上下文中当前世界空间到页面空间的变换。 |
| [EmfSmallTextOut](./emfsmalltextout/) | EMR_SMALLTEXTOUT 记录输出字符串。 |
| [EmfStateRecordType](./emfstaterecordtype/) | 状态记录类型指定并管理定义回放设备上下文状态的图形属性。 |
| [EmfStretchBlt](./emfstretchblt/) | EMR_STRETCHBLT 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案，依据指定的光栅操作，根据需要拉伸或压缩输出以适应目标的尺寸。 |
| [EmfStretchDiBits](./emfstretchdibits/) | EMR_STRETCHDIBITS 记录指定将像素从源位图块传输到目标矩形的操作，可选地结合画刷图案，依据指定的光栅操作，根据需要拉伸或压缩输出以适应目标的尺寸。 |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath/) | 该 EMR_STROKEANDFILLPATH 记录会关闭路径中任何打开的图形，使用当前笔描绘路径的轮廓，并使用当前画刷填充其内部。 |
| [EmfStrokePath](./emfstrokepath/) | EMR_STROKEPATH 类 |
| [EmfTransformRecordType](./emftransformrecordtype/) | 该变换记录类型指定并修改世界空间到页面空间的变换。 |
| [EmfTransparentBlt](./emftransparentblt/) | 该 EMR_TRANSPARENTBLT 记录指定将像素块从源位图传输到目标矩形，将指定颜色视为透明，并在必要时拉伸或压缩输出以适应目标的尺寸。 |
| [EmfVertexData](./emfvertexdata/) | 指定矩形或三角形顶点及其对应颜色的对象。 |
| [EmfWidenPath](./emfwidenpath/) | 该记录将当前路径重新定义为如果使用当前在回放设备上下文中选中的笔绘制路径时将被绘制的区域。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [EmfBlendFunction](./emfblendfunction/) | 指定源位图和目标位图混合操作的结构体。 |


