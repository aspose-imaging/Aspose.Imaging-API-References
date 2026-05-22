---
title: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records"
second_title: "Aspose.Imaging for .NET API 参考"
description: "该命名空间包含类型 MSEMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF 记录"
type: docs
weight: 430
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/
---
该命名空间包含类型 [MS-EMFPLUS]：增强型图元文件格式 Plus 扩展 2.3 EMF+ 记录

## 类

| 类 | 描述 |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer/) | EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定变换。 |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams/) | EmfPlusBeginContainerNoParams 记录打开一个新的图形状态容器。 |
| [EmfPlusClear](./emfplusclear/) | EmfPlusClear 记录清除输出坐标空间并用背景颜色和透明度进行初始化。 |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype/) | 剪裁记录类型指定剪裁区域和操作。 |
| [EmfPlusComment](./emfpluscomment/) | EmfPlusComment 记录指定任意私有数据。 |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype/) | 控制记录类型指定 EMF+ 元文件处理的全局参数。 |
| [EmfPlusDrawArc](./emfplusdrawarc/) | EmfPlusDrawArc 记录指定绘制椭圆的弧线。 |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers/) | EmfPlusDrawBeziers 记录指定绘制一系列相连的贝塞尔曲线。贝塞尔数据点的顺序为起始点、控制点1、控制点2和终点。更多信息请参见 [MSDN-DrawBeziers]。 |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve/) | EmfPlusDrawClosedCurve 记录指定绘制闭合的基数样条曲线。 |
| [EmfPlusDrawCurve](./emfplusdrawcurve/) | EmfPlusDrawCurve 记录指定绘制基数样条曲线。注意：ObjectID（1 字节）：在 EMF+ 对象表中用于绘制曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。 |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring/) | EmfPlusDrawDriverString 记录指定带有字符位置的文本输出。 |
| [EmfPlusDrawEllipse](./emfplusdrawellipse/) | EmfPlusDrawEllipse 记录指定绘制椭圆。 |
| [EmfPlusDrawImage](./emfplusdrawimage/) | EmfPlusDrawImage 记录指定绘制缩放图像。 |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints/) | EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。 |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype/) | 绘图记录类型指定图形输出。 |
| [EmfPlusDrawLines](./emfplusdrawlines/) | EmfPlusDrawlLines 记录指定绘制一系列相连的直线。 |
| [EmfPlusDrawPath](./emfplusdrawpath/) | EmfPlusDrawPath 记录指定绘制图形路径。 |
| [EmfPlusDrawPie](./emfplusdrawpie/) | EmfPlusDrawPie 记录指定绘制椭圆内部的一个扇形。 |
| [EmfPlusDrawRects](./emfplusdrawrects/) | EmfPlusDrawRects 记录指定绘制一系列矩形。 |
| [EmfPlusDrawString](./emfplusdrawstring/) | EmfPlusDrawString 记录指定带有字符串格式化的文本输出。 |
| [EmfPlusEndContainer](./emfplusendcontainer/) | EmfPlusEndContainer 记录关闭先前由 begin container 操作打开的图形状态容器。 |
| [EmfPlusEndOfFile](./emfplusendoffile/) | EmfPlusEndOfFile 记录指定元文件中 EMF+ 数据的结束。 |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve/) | EmfPlusFillClosedCurve 记录指定填充闭合的基数样条曲线内部。 |
| [EmfPlusFillEllipse](./emfplusfillellipse/) | EmfPlusFillEllipse 记录指定填充椭圆的内部。 |
| [EmfPlusFillPath](./emfplusfillpath/) | 填充路径记录 标志：16 位无符号整数，提供有关如何执行操作以及记录结构的信息。 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (1 位)：此位指示 BrushId 字段中的数据类型。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果清除，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。X (1 位)：保留，必须忽略。ObjectId (1 字节)：EMF+ 对象表中用于填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。 |
| [EmfPlusFillPie](./emfplusfillpie/) | EmfPlusFillPie 记录指定填充椭圆内部的一个扇形。 |
| [EmfPlusFillPolygon](./emfplusfillpolygon/) | 此 EmfPlusFillPolygon 记录指定填充多边形的内部。 |
| [EmfPlusFillRects](./emfplusfillrects/) | 此 EmfPlusFillRects 记录指定填充一系列矩形的内部。 |
| [EmfPlusFillRegion](./emfplusfillregion/) | 此 EmfPlusFillRegion 记录指定填充图形区域的内部。 |
| [EmfPlusGetDc](./emfplusgetdc/) | 此 EmfPlusGetDC 记录指定应处理在元文件中遇到的后续 EMF 记录。 |
| [EmfPlusHeader](./emfplusheader/) | 此 EmfPlusHeader 记录指定元文件中 EMF+ 数据的开始。此 EmfPlusHeader 记录必须嵌入在 EMF EMR_COMMENT_EMFPLUS 记录中，该记录必须是元文件中 EMF 头之后紧随的记录。EMR_COMMENT_EMFPLUS 记录在 [MS-EMF] 第 2.3.3.2 节中指定。 |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform/) | 此 EmfPlusMultiplyWorldTransform 记录将当前世界空间变换乘以指定的变换矩阵。 |
| [EmfPlusObject](./emfplusobject/) | 此 EmfPlusObject 记录指定用于图形操作的对象。对象定义可以跨多个记录，由 Flags 字段的值指示。 |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype/) | 对象记录类型定义可重用的图形对象。 |
| [EmfPlusOffsetClip](./emfplusoffsetclip/) | 此 EmfPlusOffsetClip 记录对当前世界空间的剪裁区域应用平移变换。新的当前剪裁区域被设置为平移变换的结果。 |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype/) | 属性记录类型指定回放设备上下文的属性。 |
| [EmfPlusRecord](./emfplusrecord/) | 此 Emf+ 基础记录类型。 |
| [EmfPlusResetClip](./emfplusresetclip/) | 此 EmfPlusResetClip 记录将当前世界空间的剪裁区域重置为无限。 |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform/) | 此 EmfPlusResetWorldTransform 记录将当前世界空间变换重置为单位矩阵。 |
| [EmfPlusRestore](./emfplusrestore/) | 此 EmfPlusRestore 记录从已保存的图形状态栈中恢复由指定索引标识的图形状态。 |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform/) | 此 EmfPlusRotateWorldTransform 记录对当前世界空间变换执行旋转。 |
| [EmfPlusSave](./emfplussave/) | 此 EmfPlusSave 记录在已保存的图形状态栈上保存由指定索引标识的图形状态。 |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform/) | 此 EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。 |
| [EmfPlusSerializableObject](./emfplusserializableobject/) | 此 EmfPlusSerializableObject 记录定义已序列化到数据缓冲区的图像效果参数块。 |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode/) | 此 EmfPlusSetAntiAliasMode 记录指定文本输出的抗锯齿模式。 |
| [EmfPlusSetClipPath](./emfplussetclippath/) | 此 EmfPlusSetClipPath 记录将当前剪裁区域与图形路径合并。新的当前剪裁区域被设置为 CombineMode 操作的结果。 |
| [EmfPlusSetClipRect](./emfplussetcliprect/) | 此 EmfPlusSetClipRect 记录将当前剪裁区域与矩形合并。 |
| [EmfPlusSetClipRegion](./emfplussetclipregion/) | 此 EmfPlusSetClipRegion 记录将当前剪裁区域与另一个图形区域合并。新的当前剪裁区域被设置为对先前的当前剪裁区域和指定的 EmfPlusRegion 对象执行 CombineMode 操作的结果。 |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode/) | 此 EmfPlusSetCompositingMode 记录指定源颜色与背景颜色的合成方式。 |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality/) | 此 EmfPlusSetCompositingQuality 记录指定从多个对象创建复合图像的期望质量水平。 |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode/) | 此 EmfPlusSetInterpolationMode 记录指定图像缩放（包括拉伸和收缩）的执行方式。 |
| [EmfPlusSetPageTransform](./emfplussetpagetransform/) | EmfPlusSetPageTransform 记录指定用于将页面空间坐标转换为设备空间坐标的缩放因子和单位。 |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode/) | EmfPlusSetPixelOffsetMode 记录指定像素相对于绘图表面坐标的居中方式。 |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin/) | EmfPlusSetRenderingOrigin 记录指定图形输出的渲染原点。 |
| [EmfPlusSetTextContrast](./emfplussettextcontrast/) | EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度。 |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint/) | EmfPlusSetTextRenderingHint 记录指定文本渲染的质量，包括抗锯齿的类型。 |
| [EmfPlusSetTsClip](./emfplussettsclip/) | EmfPlusSetTSClip 记录指定终端服务器的图形设备上下文中的裁剪区域。 |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics/) | EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文的状态。 |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform/) | EmfPlusSetWorldTransform 记录根据指定变换矩阵中的数值设置世界变换。 |
| [EmfPlusStateRecordType](./emfplusstaterecordtype/) | State Record Types 指定对回放设备上下文状态的操作。 |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype/) | Terminal Server Record Types 指定终端服务器上的图形处理。以下是 EMF+ 终端服务器记录类型。 |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype/) | Transform Record Types 指定坐标空间上的属性和变换。 |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform/) | EmfPlusTranslateWorldTransform 记录对当前世界空间变换执行平移操作。 |


