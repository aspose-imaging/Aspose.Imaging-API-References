---
title: "Aspose.Imaging.FileFormats.Wmf.Objects"
second_title: "Aspose.Imaging for .NET API 参考"
description: "该命名空间包含类型 MSWMF Windows Metafile Format 2.2 WMF 对象"
type: docs
weight: 770
url: /zh/net/aspose.imaging.fileformats.wmf.objects/
---
该 `namespace` 包含类型 [MS-WMF]：Windows Metafile Format 2.2 WMF 对象

## 类

| 类 | 描述 |
| --- | --- |
| [WmfAnimatePalette](./wmfanimatepalette/) | META_ANIMATEPALETTE 记录重新定义在播放设备上下文中使用指定的 Palette 对象定义的逻辑调色板条目（第 2.2.1.3 节）。 |
| [WmfArc](./wmfarc/) | META_ARC 记录绘制椭圆弧。 |
| [WmfBitBlt](./wmfbitblt/) | META_BITBLT 记录指定根据光栅操作传输像素块。传输的目标是播放设备上下文中的当前输出区域。 |
| [WmfBitmap16](./wmfbitmap16/) | Bitmap16 对象指定位图的尺寸和颜色格式信息。 |
| [WmfBitmapBaseHeader](./wmfbitmapbaseheader/) | 基础位图头类。 |
| [WmfBitmapCoreHeader](./wmfbitmapcoreheader/) | BitmapCoreHeader 对象包含关于设备无关位图（DIB）尺寸和颜色格式的信息。 |
| [WmfBitmapInfoHeader](./wmfbitmapinfoheader/) | BitmapInfoHeader 对象包含关于设备无关位图（DIB）尺寸和颜色格式的信息。 |
| [WmfChord](./wmfchord/) | META_CHORD 记录绘制和弦，其由椭圆与线段相交形成的区域界定。和弦使用在播放设备上下文中定义的笔进行描边，并使用刷子进行填充。 |
| [WmfCieXyzTriple](./wmfciexyztriple/) | CIEXYZTriple 对象定义关于 CIEXYZTriple 颜色对象的信息。 |
| [WmfCreateBrushInDirect](./wmfcreatebrushindirect/) | 直接创建画笔 |
| [WmfCreateFontInDirect](./wmfcreatefontindirect/) | 创建字体 |
| [WmfCreatePalette](./wmfcreatepalette/) | 该 META_CREATEPALETTE 记录创建一个调色板对象（第 2.2.1.3 节）。 |
| [WmfCreatePatternBrush](./wmfcreatepatternbrush/) | 该 META_CREATEPATTERNBRUSH 记录创建一个画刷对象，其图案由位图指定。 |
| [WmfCreatePenInDirect](./wmfcreatepenindirect/) | 在直接模式下创建笔。 |
| [WmfCreateRegion](./wmfcreateregion/) | 该 META_CREATEREGION 记录创建一个区域对象（第 2.2.1.5 节）。 |
| [WmfDeleteObject](./wmfdeleteobject/) | 该 Delete 对象。 |
| [WmfDeviceIndependentBitmap](./wmfdeviceindependentbitmap/) | 该 DeviceIndependentBitmap 对象定义了以设备无关位图（DIB）格式表示的图像。 |
| [WmfDibBitBlt](./wmfdibbitblt/) | 该 META_DIBBITBLT 记录指定根据光栅操作在设备无关格式下传输像素块。 |
| [WmfDibCreatePatternBrush](./wmfdibcreatepatternbrush/) | 该 META_DIBCREATEPATTERNBRUSH 记录创建一个画刷对象（第 2.2.1.1 节），其图案由 DeviceIndependentBitmap（DIB）对象（第 2.2.2.9 节）指定。 |
| [WmfDibStrechBlt](./wmfdibstrechblt/) | 该 META_DIBSTRETCHBLT 记录指定根据光栅操作在设备无关格式下传输像素块，可能会进行放大或收缩。 |
| [WmfEllipse](./wmfellipse/) | 该 META_ELLIPSE 记录绘制椭圆。椭圆的中心是指定的边界矩形的中心。椭圆使用笔描边，使用画刷填充；这些在回放设备上下文中定义。 |
| [WmfEof](./wmfeof/) | 该 Eof 对象。 |
| [WmfEscape](./wmfescape/) | 该 wmf escape 对象。 |
| [WmfExcludeClipRect](./wmfexcludecliprect/) | 该 META_EXCLUDECLIPRECT 记录将回放设备上下文中的裁剪区域设置为现有裁剪区域减去指定的矩形。 |
| [WmfExtFloodFill](./wmfextfloodfill/) | 该 META_EXTFLOODFILL 记录使用在回放设备上下文中定义的画刷填充区域。 |
| [WmfExtTextOut](./wmfexttextout/) | Wmf 扩展文本输出。 |
| [WmfFillRegion](./wmffillregion/) | 该 META_FILLREGION 记录使用指定的画刷填充区域。 |
| [WmfFloodFill](./wmffloodfill/) | 该 META_FLOODFILL 记录使用在回放设备上下文中定义的画刷填充输出表面的区域。 |
| [WmfFrameRegion](./wmfframeregion/) | 该 wmf frame region 对象。 |
| [WmfGraphicObject](./wmfgraphicobject/) | 该 WMF Graphics 对象指定图形输出的参数。 |
| [WmfIntersectClipRect](./wmfintersectcliprect/) | 该 META_INTERSECTCLIPRECT 记录将回放设备上下文中的裁剪区域设置为现有裁剪区域与指定矩形的交集。 |
| [WmfInvertRegion](./wmfinvertregion/) | 该 META_INVERTREGION 记录绘制颜色被反转的区域。 |
| [WmfLineTo](./wmflineto/) | 该 META_LINETO 记录从回放设备上下文中定义的绘图位置绘制一条线，直至（但不包括）指定的点。 |
| [WmfLogColorSpace](./wmflogcolorspace/) | 该 LogColorSpace 对象指定回放设备上下文的逻辑颜色空间，可以是 ASCII 字符表示的颜色配置文件名称。 |
| [WmfLogColorSpaceW](./wmflogcolorspacew/) | 该 LogColorSpaceW 对象指定逻辑颜色空间，可以通过名称由 Unicode 16 位字符组成的颜色配置文件来定义。 |
| [WmfMoveTo](./wmfmoveto/) | 该 META_MOVETO 记录将回放设备上下文中的输出位置设置为指定的点。 |
| [WmfObject](./wmfobject/) | 基础 wmf 对象。 |
| [WmfOffsetClipRgn](./wmfoffsetcliprgn/) | META_OFFSETCLIPRGN 记录通过指定的偏移量移动回放设备上下文中的剪裁区域。 |
| [WmfOffsetViewPortOrg](./wmfoffsetviewportorg/) | META_OFFSETVIEWPORTORG 记录通过指定的水平和垂直偏移量移动回放设备上下文中的视口原点。 |
| [WmfOffsetWindowOrg](./wmfoffsetwindoworg/) | META_OFFSETWINDOWORG 记录通过指定的水平和垂直偏移量移动回放设备上下文中的输出窗口原点。 |
| [WmfPaintRegion](./wmfpaintregion/) | META_PAINTREGION 记录使用在回放设备上下文中定义的画刷来绘制指定的区域。 |
| [WmfPatBlt](./wmfpatblt/) | META_PATBLT 记录使用在回放设备上下文中定义的画刷绘制指定的矩形。画刷颜色与表面颜色或颜色通过指定的光栅操作进行组合。 |
| [WmfPie](./wmfpie/) | META_PIE 记录绘制由椭圆与两条半径的交叉所限定的饼形楔形。该饼形使用在回放设备上下文中定义的笔进行描边，并使用画刷进行填充。 |
| [WmfPointObject](./wmfpointobject/) | Point 对象。 |
| [WmfPolygon](./wmfpolygon/) | 多边形对象 |
| [WmfPolyLine](./wmfpolyline/) | 折线对象。 |
| [WmfPolyPolygon](./wmfpolypolygon/) | PolyPolygon 对象定义了一系列封闭的多边形。 |
| [WmfRealizePalette](./wmfrealizepalette/) | META_REALIZEPALETTE 记录将回放设备上下文中定义的逻辑调色板条目映射到系统调色板。 |
| [WmfRecord](./wmfrecord/) | Wmf 记录 |
| [WmfRectangle](./wmfrectangle/) | META_RECTANGLE 记录绘制矩形。该矩形使用在回放设备上下文中定义的笔进行描边，并使用画刷进行填充。 |
| [WmfRegion](./wmfregion/) | Region 对象定义了一种可能非矩形的形状，该形状由扫描线数组定义。 |
| [WmfResizePalette](./wmfresizepalette/) | META_RESIZEPALETTE 记录重新定义了回放设备上下文中逻辑调色板的大小。 |
| [WmfRestoreDc](./wmfrestoredc/) | 恢复 DC 对象 |
| [WmfRoundRect](./wmfroundrect/) | 矩形对象。 |
| [WmfSaveDc](./wmfsavedc/) | META_SAVEDC 记录保存回放设备上下文以供以后检索。 |
| [WmfScaleViewportExt](./wmfscaleviewportext/) | META_SCALEVIEWPORTEXT 记录通过使用指定的乘数和除数形成的比例，缩放回放设备上下文中定义的视口的水平和垂直范围。 |
| [WmfScaleWindowExt](./wmfscalewindowext/) | META_SCALEWINDOWEXT 记录通过使用指定的乘数和除数形成的比例，缩放回放设备上下文中定义的输出窗口的水平和垂直范围。 |
| [WmfScanObject](./wmfscanobject/) | Scan 对象指定了一组扫描线。 |
| [WmfSelectClipRegion](./wmfselectclipregion/) | META_SELECTCLIPREGION 记录指定一个 Region 对象（第 2.2.1.5 节）作为当前的剪裁区域。 |
| [WmfSelectObject](./wmfselectobject/) | 选择对象。 |
| [WmfSelectPalette](./wmfselectpalette/) | META_SELECTPALETTE 记录使用指定的 Palette 对象定义当前的逻辑调色板。 |
| [WmfSetBkColor](./wmfsetbkcolor/) | META_SETBKCOLOR 记录将回放设备上下文中的背景颜色设置为指定颜色，如果设备无法表示指定颜色，则使用最接近的物理颜色。 |
| [WmfSetBkMode](./wmfsetbkmode/) | 设置 bk 模式。 |
| [WmfSetDibToDev](./wmfsetdibtodev/) | META_SETDIBTODEV 记录使用设备无关的颜色数据在回放设备上下文中设置一块像素。颜色数据的来源是 DIB。 |
| [WmfSetLayout](./wmfsetlayout/) | META_SETLAYOUT 记录定义回放设备上下文中的布局方向。布局方向决定文本和图形的绘制方向。 |
| [WmfSetMapMode](./wmfsetmapmode/) | 设置映射模式。 |
| [WmfSetMapperFlags](./wmfsetmapperflags/) | META_SETMAPPERFLAGS 记录定义字体映射器在将逻辑字体映射到物理字体时使用的算法。 |
| [WmfSetPalentries](./wmfsetpalentries/) | META_SETPALENTRIES 记录定义在回放设备上下文中定义的逻辑调色板的条目范围内的 RGB 颜色值。 |
| [WmfSetPixel](./wmfsetpixel/) | META_SETPIXEL 记录将指定坐标处的像素设置为指定颜色。 |
| [WmfSetPolyFillMode](./wmfsetpolyfillmode/) | 设置多边形填充模式。 |
| [WmfSetRelabs](./wmfsetrelabs/) | META_SETRELABS 记录已保留且不受支持。 |
| [WmfSetRop2](./wmfsetrop2/) | 设置 rop2 |
| [WmfSetStretchbltMode](./wmfsetstretchbltmode/) | META_SETSTRETCHBLTMODE 记录定义回放设备上下文中的位图拉伸模式。 |
| [WmfSetTextAlign](./wmfsettextalign/) | 设置文本对齐 |
| [WmfSetTextCharExtra](./wmfsettextcharextra/) | META_SETTEXTCHAREXTRA 记录定义回放设备上下文中用于文本对齐的字符间距。当输出对齐文本行时，间距会添加到每个字符之间的空白，包括 `break` 字符。 |
| [WmfSetTextColor](./wmfsettextcolor/) | 设置文本颜色。 |
| [WmfSetTextJustification](./wmfsettextjustification/) | META_SETTEXTJUSTIFICATION 记录定义在对齐文本字符串中向 `break` 字符添加的空间量。 |
| [WmfSetViewportExt](./wmfsetviewportext/) | META_SETVIEWPORTEXT 记录设置回放设备上下文中视口的水平和垂直范围。 |
| [WmfSetViewportOrg](./wmfsetviewportorg/) | META_SETVIEWPORTORG 记录定义回放设备上下文中视口的原点。 |
| [WmfSetWindowExt](./wmfsetwindowext/) | 设置窗口对象。 |
| [WmfSetWindowOrg](./wmfsetwindoworg/) | 设置窗口 org 对象。 |
| [WmfStretchBlt](./wmfstretchblt/) | META_STRETCHBLT 记录指定根据光栅操作传输一块像素，可进行扩展或收缩。 |
| [WmfStretchDib](./wmfstretchdib/) | wmf Stretch DIB 对象。 |
| [WmfTextOut](./wmftextout/) | META_EXTTEXTOUT 记录使用回放设备上下文中定义的字体、背景颜色和文本颜色输出文本。可选地，可以提供用于剪裁、遮蔽或两者的尺寸。 |
| [WmfUntyped](./wmfuntyped/) | wmf 未类型化对象。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [WmfCieXyz](./wmfciexyz/) | CIEXYZ 对象定义有关 CIEXYZ 色度对象的信息。 |
| [WmfPitchAndFamily](./wmfpitchandfamily/) | PitchAndFamily 对象指定 Font 对象的 pitch 和 family 属性（第 2.2.1.2 节）。Pitch 指字符的宽度，family 指字体的一般外观。 |


