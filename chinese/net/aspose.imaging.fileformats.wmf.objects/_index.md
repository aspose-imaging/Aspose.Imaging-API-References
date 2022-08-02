---
title: Aspose.Imaging.FileFormats.Wmf.Objects
second_title: Aspose.Imaging for .NET API 参考
description: 的namespace包含类型 MS-WMFWindows Metafile Format 2.2 WMF Objects
type: docs
weight: 710
url: /zh/net/aspose.imaging.fileformats.wmf.objects/
---
的`namespace`包含类型 [MS-WMF]：Windows Metafile Format 2.2 WMF Objects

## 课程

| 班级 | 描述 |
| --- | --- |
| [WmfAnimatePalette](./wmfanimatepalette) | META_ANIMATEPALETTE 记录重新定义逻辑调色板 中的条目，该逻辑调色板 在回放设备上下文中使用指定的 调色板对象（第 2.2.1.3 节）定义。 |
| [WmfArc](./wmfarc) | META_ARC 记录绘制椭圆弧。 |
| [WmfBitBlt](./wmfbitblt) | META_BITBLT 记录根据光栅操作指定像素块 的传输。传输的目的地是播放设备上下文中的 当前输出区域。 |
| [WmfBitmap16](./wmfbitmap16) | Bitmap16 对象指定有关位图的尺寸和颜色 格式的信息。 |
| [WmfBitmapBaseHeader](./wmfbitmapbaseheader) | 基本位图头类。 |
| [WmfBitmapCoreHeader](./wmfbitmapcoreheader) | BitmapCoreHeader 对象包含有关与设备无关的位图 (DIB) 的尺寸 和颜色格式的信息。 |
| [WmfBitmapInfoHeader](./wmfbitmapinfoheader) | BitmapInfoHeader 对象包含有关与设备无关的尺寸和颜色格式的信息 位图 (DIB)。 |
| [WmfChord](./wmfchord) | META_CHORD 记录绘制和弦，该弦由以椭圆与线段的交点为界的 region 定义。 chord 使用笔勾勒出轮廓，并使用在播放设备上下文中定义的画笔进行填充。 |
| [WmfCieXyzTriple](./wmfciexyztriple) | CIEXYZTriple 对象定义了有关 CIEXYZTriple 颜色 对象的信息。 |
| [WmfCreateBrushInDirect](./wmfcreatebrushindirect) | direct 中的创建画笔 |
| [WmfCreateFontInDirect](./wmfcreatefontindirect) | 创建字体 |
| [WmfCreatePalette](./wmfcreatepalette) | META_CREATEPALETTE 记录创建一个调色板对象（第 2.2.1.3 节）。 |
| [WmfCreatePatternBrush](./wmfcreatepatternbrush) | META_CREATEPATTERNBRUSH 记录使用位图指定的模式 创建画笔对象。 |
| [WmfCreatePenInDirect](./wmfcreatepenindirect) | direct 中的创建笔 |
| [WmfCreateRegion](./wmfcreateregion) | META_CREATEREGION 记录创建一个区域对象（第 2.2.1.5 节）。 |
| [WmfDeleteObject](./wmfdeleteobject) | 删除对象 |
| [WmfDeviceIndependentBitmap](./wmfdeviceindependentbitmap) | DeviceIndependentBitmap 对象定义了一个图像 in 与设备无关的位图 (DIB) 格式 |
| [WmfDibBitBlt](./wmfdibbitblt) | META_DIBBITBLT 记录指定根据光栅操作以 设备无关格式传输像素块。 |
| [WmfDibCreatePatternBrush](./wmfdibcreatepatternbrush) | META_DIBCREATEPATTERNBRUSH 记录创建一个画笔对象 (section 2.2.1.1)，其图案由 DeviceIndependentBitmap (DIB) 对象（第 2.2.2.9 节）指定。 |
| [WmfDibStrechBlt](./wmfdibstrechblt) | META_DIBSTRETCHBLT 记录指定根据光栅操作以设备无关格式传输 像素块， 可能扩展或收缩。 |
| [WmfEllipse](./wmfellipse) | META_ELLIPSE 记录绘制一个椭圆。椭圆的中心是 指定边界矩形的中心。椭圆用笔勾勒 ，用画笔填充；这些在 播放设备上下文中定义。 |
| [WmfEof](./wmfeof) | Eof 对象。 |
| [WmfEscape](./wmfescape) | wmf 转义对象。 |
| [WmfExcludeClipRect](./wmfexcludecliprect) | META_EXCLUDECLIPRECT 记录将playback 设备上下文中的剪辑区域设置为现有剪辑区域减去指定的 矩形。 |
| [WmfExtFloodFill](./wmfextfloodfill) | META_EXTFLOODFILL 记录用播放设备上下文中定义的 的画笔填充区域。 |
| [WmfExtTextOut](./wmfexttextout) | Wmf 文本输出 |
| [WmfFillRegion](./wmffillregion) | META_FILLREGION 记录使用指定的画笔填充区域。 |
| [WmfFloodFill](./wmffloodfill) | META_FLOODFILL 记录使用播放设备上下文中定义的 画笔填充输出表面的区域。 |
| [WmfFrameRegion](./wmfframeregion) | wmf 框架区域对象。 |
| [WmfGraphicObject](./wmfgraphicobject) | WMF 图形对象指定图形输出的参数。 |
| [WmfIntersectClipRect](./wmfintersectcliprect) | META_INTERSECTCLIPRECT 记录将 播放设备上下文中的剪辑区域设置为现有剪辑 区域和指定矩形的交集。 |
| [WmfInvertRegion](./wmfinvertregion) | META_INVERTREGION 记录绘制了一个颜色为 反转的区域。 |
| [WmfLineTo](./wmflineto) | META_LINETO 记录从播放设备上下文中定义的 绘制位置绘制一条线，直到但不包括 指定点。 |
| [WmfLogColorSpace](./wmflogcolorspace) | LogColorSpace 对象为 播放设备上下文指定逻辑色彩空间，它可以是 ASCII 字符中的颜色配置文件的名称。 |
| [WmfLogColorSpaceW](./wmflogcolorspacew) | LogColorSpaceW 对象指定一个逻辑色彩空间，可以 由名称由Unicode 16 位 个字符组成的颜色配置文件定义 |
| [WmfMoveTo](./wmfmoveto) | META_MOVETO 记录将播放设备 上下文中的输出位置设置为指定点。 |
| [WmfObject](./wmfobject) | 基础 wmf 对象。 |
| [WmfOffsetClipRgn](./wmfoffsetcliprgn) | META_OFFSETCLIPRGN 记录将playback 设备上下文中的剪辑区域移动指定的偏移量。 |
| [WmfOffsetViewPortOrg](./wmfoffsetviewportorg) | META_OFFSETVIEWPORTORG 记录将 播放设备上下文中的视口原点移动指定的水平和垂直偏移量。 |
| [WmfOffsetWindowOrg](./wmfoffsetwindoworg) | META_OFFSETWINDOWORG 记录将 播放设备上下文中的输出窗口原点移动指定的水平和垂直偏移量。 |
| [WmfPaintRegion](./wmfpaintregion) | META_PAINTREGION 记录使用播放设备上下文中定义的 画笔绘制指定区域。 |
| [WmfPatBlt](./wmfpatblt) | META_PATBLT 记录使用在播放设备上下文中定义的 画笔绘制指定的矩形。使用指定的 raster 操作将画笔颜色和 表面颜色组合在一起。 |
| [WmfPie](./wmfpie) | META_PIE 记录绘制了一个饼形楔形，其边界为一个椭圆和两条径向线的交点 。饼图使用笔勾勒出轮廓， 使用播放设备中定义的画笔填充 context. |
| [WmfPointObject](./wmfpointobject) | 点对象。 |
| [WmfPolygon](./wmfpolygon) | 多边形对象 |
| [WmfPolyLine](./wmfpolyline) | 折线对象。 |
| [WmfPolyPolygon](./wmfpolypolygon) | PolyPolygon 对象定义了一系列封闭的多边形。 |
| [WmfRealizePalette](./wmfrealizepalette) | META_REALIZEPALETTE 记录将播放设备上下文中定义的逻辑调色板 中的条目映射到系统调色板。 |
| [WmfRecord](./wmfrecord) | Wmf 记录 |
| [WmfRectangle](./wmfrectangle) | META_RECTANGLE 记录绘制一个矩形。矩形是使用笔勾勒出 并使用在 播放设备上下文中定义的画笔填充的。 |
| [WmfRegion](./wmfregion) | 区域对象定义了一个潜在的非直线形状，由 扫描线数组定义。 |
| [WmfResizePalette](./wmfresizepalette) | META_RESIZEPALETTE 记录重新定义了回放设备上下文中定义的逻辑调色板 的大小。 |
| [WmfRestoreDc](./wmfrestoredc) | 恢复 DC 对象 |
| [WmfRoundRect](./wmfroundrect) | 矩形对象。 |
| [WmfSaveDc](./wmfsavedc) | META_SAVEDC 记录保存播放设备上下文以供稍后 检索。 |
| [WmfScaleViewportExt](./wmfscaleviewportext) | META_SCALEVIEWPORTEXT 记录使用由指定的被乘数和除数形成的比率来缩放在回放设备 context 中定义的视口的水平和垂直 范围。 |
| [WmfScaleWindowExt](./wmfscalewindowext) | META_SCALEWINDOWEXT 记录使用由指定的被乘数和 除数形成的比率来缩放播放设备 上下文中定义的输出窗口的水平和垂直 范围。 |
| [WmfScanObject](./wmfscanobject) | 扫描对象指定扫描线的集合。 |
| [WmfSelectClipRegion](./wmfselectclipregion) | META_SELECTCLIPREGION 记录指定一个区域对象（第 2.2.1.5 节）作为当前剪辑区域。 |
| [WmfSelectObject](./wmfselectobject) | 选择对象。 |
| [WmfSelectPalette](./wmfselectpalette) | META_SELECTPALETTE 记录用 a 指定的调色板对象定义当前逻辑调色板。 |
| [WmfSetBkColor](./wmfsetbkcolor) | META_SETBKCOLOR 记录将回放 设备上下文中的背景颜色设置为指定颜色，或者设置为最接近的物理颜色 if 设备无法表示指定颜色。 |
| [WmfSetBkMode](./wmfsetbkmode) | 设置的bk模式。 |
| [WmfSetDibToDev](./wmfsetdibtodev) | META_SETDIBTODEV 记录使用与设备无关的颜色数据在播放 设备上下文中设置像素块。 颜色数据的来源是 DIB. |
| [WmfSetLayout](./wmfsetlayout) | META_SETLAYOUT 记录定义了playback 设备上下文中的布局方向。布局方向决定了 文本和图形的绘制方向 |
| [WmfSetMapMode](./wmfsetmapmode) | 设置的地图模式。 |
| [WmfSetMapperFlags](./wmfsetmapperflags) | META_SETMAPPERFLAGS 记录定义了 font 映射器在将逻辑字体映射到物理字体时使用的算法。 |
| [WmfSetPalentries](./wmfsetpalentries) | META_SETPALENTRIES 记录在播放设备 context 中定义的逻辑调色板中定义 条目范围内的RGB 颜色值。 |
| [WmfSetPixel](./wmfsetpixel) | META_SETPIXEL 记录将指定坐标处的像素设置为 指定颜色。 |
| [WmfSetPolyFillMode](./wmfsetpolyfillmode) | 设置的多边形填充模式。 |
| [WmfSetRelabs](./wmfsetrelabs) | META_SETRELABS 记录已保留且不受支持。 |
| [WmfSetRop2](./wmfsetrop2) | 设置的 rop2 |
| [WmfSetStretchbltMode](./wmfsetstretchbltmode) | META_SETSTRETCHBLTMODE 记录定义了 播放设备上下文中的位图拉伸模式。 |
| [WmfSetTextAlign](./wmfsettextalign) | 设置文本 align |
| [WmfSetTextCharExtra](./wmfsettextcharextra) | META_SETTEXTCHAREXTRA 记录定义播放设备上下文中 文本对齐的字符间距。间距加到 每个字符之间的空白处，包括 `break`字符，当一行对齐的文本 is output. |
| [WmfSetTextColor](./wmfsettextcolor) | 设置文本颜色。 |
| [WmfSetTextJustification](./wmfsettextjustification) | META_SETTEXTJUSTIFICATION 记录定义了要添加 的空间量`break`对齐文本字符串中的字符。 |
| [WmfSetViewportExt](./wmfsetviewportext) | META_SETVIEWPORTEXT 记录设置播放设备上下文中视口的水平和垂直范围 。 |
| [WmfSetViewportOrg](./wmfsetviewportorg) | META_SETVIEWPORTORG 记录定义了 播放设备上下文中的视口原点。 |
| [WmfSetWindowExt](./wmfsetwindowext) | 设置的窗口对象。 |
| [WmfSetWindowOrg](./wmfsetwindoworg) | 设置的窗口组织对象 |
| [WmfStretchBlt](./wmfstretchblt) | META_STRETCHBLT 记录指定像素块的传输 根据光栅操作，可能扩展或收缩。 |
| [WmfStretchDib](./wmfstretchdib) | wmf Stretch DIB objetc. |
| [WmfTextOut](./wmftextout) | META_EXTTEXTOUT 记录通过使用在播放设备上下文中定义的字体、背景 颜色和文本颜色输出文本。 可以选择为裁剪、不透明或两者提供尺寸。 |
| [WmfUntyped](./wmfuntyped) | wmf 无类型对象 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
