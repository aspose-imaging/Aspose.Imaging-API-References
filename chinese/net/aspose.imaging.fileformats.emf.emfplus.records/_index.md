---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging for .NET API 参考
description: 命名空间包含类型 MS-EMFPLUS增强的图元文件格式加扩展名 2.3 EMF Records
type: docs
weight: 390
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/
---
命名空间包含类型 [MS-EMFPLUS]：增强的图元文件格式加扩展名 2.3 EMF+ Records

## 课程

| 班级 | 描述 |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定一个变换。 |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | EmfPlusBeginContainerNoParams 记录打开一个新的图形状态容器。 |
| [EmfPlusClear](./emfplusclear) | EmfPlusClear 记录清除输出坐标空间，并用背景色和透明度对其进行初始化 |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | 剪辑记录类型指定剪辑区域和操作。 |
| [EmfPlusComment](./emfpluscomment) | EmfPlusComment 记录指定任意私有数据。 |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | 控制记录类型指定 EMF+ 图元文件处理的全局参数。 |
| [EmfPlusDrawArc](./emfplusdrawarc) | EmfPlusDrawArc 记录指定绘制椭圆的弧线。 |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | EmfPlusDrawBeziers 记录指定绘制一系列连接的贝塞尔曲线。 Bezier 数据点的顺序是起点、控制点 1、 控制点 2 和终点。有关详细信息，请参阅 [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | EmfPlusDrawClosedCurve 记录指定绘制闭合基数样条 |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | EmfPlusDrawCurve 记录指定绘制基本样条曲线 注意：ObjectID（1 字节）：EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节） 的索引以绘制曲线。该值必须是 0 到 63，包括在内。 |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | EmfPlusDrawDriverString 记录指定带有字符位置的文本输出。 |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | EmfPlusDrawEllipse 记录指定绘制椭圆。 |
| [EmfPlusDrawImage](./emfplusdrawimage) | EmfPlusDrawImage 记录指定绘制缩放图像。 |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。 |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | 绘图记录类型指定图形输出。 |
| [EmfPlusDrawLines](./emfplusdrawlines) | EmfPlusDrawlLines 记录指定绘制一系列连接线 |
| [EmfPlusDrawPath](./emfplusdrawpath) | EmfPlusDrawPath 记录指定绘制图形路径。 |
| [EmfPlusDrawPie](./emfplusdrawpie) | EmfPlusDrawPie 记录指定绘制椭圆内部的一部分。 |
| [EmfPlusDrawRects](./emfplusdrawrects) | EmfPlusDrawRects 记录指定绘制一系列矩形 |
| [EmfPlusDrawString](./emfplusdrawstring) | EmfPlusDrawString 记录使用字符串格式指定文本输出 |
| [EmfPlusEndContainer](./emfplusendcontainer) | EmfPlusEndContainer 记录关闭先前由开始容器操作打开的图形状态容器。 |
| [EmfPlusEndOfFile](./emfplusendoffile) | EmfPlusEndOfFile 记录指定元文件中 EMF+ 数据的结尾。 |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | EmfPlusFillClosedCurve 记录指定填充闭合基数样条的内部 |
| [EmfPlusFillEllipse](./emfplusfillellipse) | EmfPlusFillEllipse 记录指定填充椭圆的内部 |
| [EmfPlusFillPath](./emfplusfillpath) | 填充路径记录 FLAGS: 16 位无符号整数，提供有关如何执行操作的信息， 以及有关记录结构的信息。 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S（1 位）：该位指示 BrushId 字段中的数据类型。 如果设置，BrushId 将颜色指定为 EmfPlusARGB 对象（第 2.2.2.1 节）。如果清除，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 X（1 位）：保留且必须被忽略。 ObjectId（1 字节）：EmfPlusPath 对象的索引（第 2.2.1.6 节）填写 EMF+ 对象表。该值必须是 0 到 63，包括在内。 |
| [EmfPlusFillPie](./emfplusfillpie) | EmfPlusFillPie 记录指定填充椭圆内部的一部分 |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | EmfPlusFillPolygon 记录指定填充多边形的内部。 |
| [EmfPlusFillRects](./emfplusfillrects) | EmfPlusFillRects 记录指定填充一系列矩形的内部 |
| [EmfPlusFillRegion](./emfplusfillregion) | EmfPlusFillRegion 记录指定填充图形区域的内部 |
| [EmfPlusGetDc](./emfplusgetdc) | EmfPlusGetDC 记录指定应处理在元文件中遇到的后续 EMF 记录。 |
| [EmfPlusHeader](./emfplusheader) | EmfPlusHeader 记录指定元文件中 EMF+ 数据的开始。 EmfPlusHeader 记录必须嵌入到 EMF EMR_COMMENT_EMFPLUS 记录中， 必须是紧跟在元文件中的 EMF 头之后的记录。 EMR_COMMENT_EMFPLUS 记录在 [MS-EMF] 部分 2.3.3.2. 中指定 |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | EmfPlusMultiplyWorldTransform 记录将当前世界空间变换乘以一个 指定的变换矩阵。 |
| [EmfPlusObject](./emfplusobject) | EmfPlusObject 记录指定用于图形操作的对象。对象定义 可以跨越多条记录，由Flags字段的值表示。 |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | 对象记录类型定义可重用的图形对象。 |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | EmfPlusOffsetClip 记录对世界空间的当前剪辑区域应用平移变换。 新的当前剪辑区域设置为平移变换的结果。 |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | 属性记录类型指定播放设备上下文的属性。 |
| [EmfPlusRecord](./emfplusrecord) | Emf+ 基本记录类型。 |
| [EmfPlusResetClip](./emfplusresetclip) | EmfPlusResetClip 记录将世界空间的当前剪切区域重置为无穷大。 |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | EmfPlusResetWorldTransform 记录将当前世界空间变换重置为识别矩阵。 |
| [EmfPlusRestore](./emfplusrestore) | EmfPlusRestore 记录从保存的图形状态堆栈中恢复由指定索引标识的图形状态。 |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。 |
| [EmfPlusSave](./emfplussave) | EmfPlusSave 记录将由指定索引标识的图形状态保存在已保存图形状态的堆栈上。 |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。 |
| [EmfPlusSerializableObject](./emfplusserializableobject) | EmfPlusSerializableObject 记录定义了一个已 序列化到数据缓冲区中的图像效果参数块。 |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式。 |
| [EmfPlusSetClipPath](./emfplussetclippath) | EmfPlusSetClipPath 记录将当前剪辑区域与图形路径组合在一起。 新的当前剪辑区域设置为 CombineMode 操作的结果。 |
| [EmfPlusSetClipRect](./emfplussetcliprect) | EmfPlusSetClipRect 记录将当前剪辑区域与矩形相结合。 |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | EmfPlusSetClipRegion 记录将当前剪辑区域与另一个图形区域组合。 新的当前剪辑区域设置为对 上一个当前剪辑区域和指定的 EmfPlusRegion 对象执行 CombineMode 操作的结果。 |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | EmfPlusSetCompositingMode 记录指定源颜色如何与背景颜色组合。 |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | EmfPlusSetCompositingQuality 记录指定从多个对象创建 合成图像所需的质量级别。 |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | EmfPlusSetInterpolationMode 记录指定如何执行图像缩放，包括拉伸和收缩。 |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | EmfPlusSetPageTransform 记录指定用于将页面空间 坐标转换为设备空间坐标的缩放因子和单位。 |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | EmfPlusSetPixelOffsetMode 记录指定像素如何相对于绘图表面的 坐标居中。 |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | EmfPlusSetRenderingOrigin 记录指定图形输出的渲染原点。 |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度。 |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | EmfPlusSetTextRenderingHint 记录指定文本渲染的质量，包括抗锯齿的类型。 |
| [EmfPlusSetTsClip](./emfplussettsclip) | EmfPlusSetTSClip 记录为终端服务器指定图形设备上下文中的剪辑区域。 |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文的状态。 |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | EmfPlusSetWorldTransform 记录根据 a 指定变换矩阵中的值设置世界变换。 |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | 状态记录类型指定对播放设备上下文状态的操作。 |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | 终端服务器记录类型指定终端服务器上的图形处理。以下 是EMF+终端服务器记录类型。 |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | 变换记录类型指定坐标空间上的属性和变换。 |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | EmfPlusTranslateWorldTransform 记录对当前世界空间变换执行平移。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
