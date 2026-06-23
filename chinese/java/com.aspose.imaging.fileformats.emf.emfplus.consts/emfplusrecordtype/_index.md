---
title: "EmfPlusRecordType"
second_title: "Aspose.Imaging for Java API 参考"
description: "RecordType 枚举定义了在 EMF 元文件中使用的记录类型。"
type: docs
weight: 45
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

RecordType 枚举定义在 EMF+ 元文件中使用的记录类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | 此记录指定元文件中 EMF+ 数据的开始。 |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | 此记录指定元文件中 EMF+ 数据的结束。 |
| [EmfPlusComment](#EmfPlusComment) | 此记录指定任意私有数据。 |
| [EmfPlusGetDC](#EmfPlusGetDC) | 此记录指定元文件中随后遇到的 EMF 记录 应该 被处理。 |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | 此记录已保留，禁止使用。 |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | 此记录已保留，禁止使用。 |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | 此记录已保留，禁止使用。 |
| [EmfPlusObject](#EmfPlusObject) | 此记录指定用于图形操作的对象。 |
| [EmfPlusClear](#EmfPlusClear) | 此记录清除输出 `coordinate space` 并使用指定的背景颜色和透明度进行初始化。 |
| [EmfPlusFillRects](#EmfPlusFillRects) | 此记录定义如何使用指定的画刷填充一系列矩形的内部。 |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | 此记录定义绘制一系列矩形的笔画。 |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | 此记录定义使用指定画刷填充多边形内部的数据。 |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | 此记录定义绘制一系列相连线条的笔画。 |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | 此记录定义如何使用指定的画刷填充椭圆的内部。 |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | 此记录定义绘制椭圆的笔画。 |
| [EmfPlusFillPie](#EmfPlusFillPie) | 此记录定义如何使用指定的画刷填充椭圆内部的某个区域。 |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | 此记录定义绘制椭圆部分的笔画。 |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | 该记录定义绘制椭圆弧的笔画。 |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | 此记录定义如何使用指定的画刷填充区域的内部。 |
| [EmfPlusFillPath](#EmfPlusFillPath) | 该记录定义如何使用指定的画刷填充图形路径中定义的图形的内部。 |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | 该记录定义绘制图形路径中图形的笔画。 |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | 此记录定义如何使用指定的画刷填充闭合基数样条的内部。 |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | 此记录定义绘制闭合基数样条的笔和笔画。 |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | 此记录定义绘制基数样条的笔画。 |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | 此记录定义绘制贝塞尔样条的笔画。 |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | 此记录定义一个缩放的 [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) 对象（第 2.2.1.4 节）。 |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | 此记录定义在平行四边形内的缩放 EmfPlusImage 对象。 |
| [EmfPlusDrawString](#EmfPlusDrawString) | 此记录定义基于字体、布局矩形和格式的文本字符串。 |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | 此记录定义渲染原点到指定的水平和垂直坐标。 |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | 此记录定义是否启用或禁用文本抗锯齿。 |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | 此记录定义用于渲染文本的过程。 |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | 此记录根据指定的文本伽马值设置文本对比度。 |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | 此记录根据指定的图像过滤类型定义对象的插值模式。 |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | 此记录根据指定的像素居中值定义像素偏移模式。 |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | 此记录根据 alpha 混合状态定义合成模式，该状态指定源颜色如何与背景颜色组合。 |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | 此记录定义合成质量，描述从多个对象创建复合图像所需的质量水平。 |
| [EmfPlusSave](#EmfPlusSave) | 此记录将由指定索引标识的图形状态保存到已保存图形状态的堆栈上。 |
| [EmfPlusRestore](#EmfPlusRestore) | 此记录从已保存图形状态的堆栈中恢复由指定索引标识的图形状态。 |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | 此记录打开一个新的图形状态容器并为其指定变换。 |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | 此记录打开一个新的图形状态容器。 |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | 此记录关闭先前通过开始容器操作打开的图形状态容器。 |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | 此记录根据指定的变换矩阵在 playback device\_context 中定义当前世界空间变换。 |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | 此记录将当前世界空间变换重置为单位矩阵。 |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | 此记录将当前世界空间乘以指定的变换矩阵。 |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | 此记录通过指定的水平和垂直距离对当前世界空间应用平移变换。 |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | 此记录通过指定的水平和垂直缩放因子对当前世界空间应用缩放变换。 |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | 此记录按指定角度旋转当前世界空间。 |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | 此记录为当前世界空间变换指定额外的缩放因子。 |
| [EmfPlusResetClip](#EmfPlusResetClip) | 此记录将世界空间的当前裁剪区域重置为无限。 |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | 此记录将当前裁剪区域与矩形合并。 |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | 此记录将当前裁剪区域与图形路径合并。 |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | 此记录将当前裁剪区域与另一个图形区域合并。 |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | 此记录对世界空间的当前裁剪区域应用平移变换。 |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | 此记录指定带有字符位置的文本输出。 |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | 此记录关闭路径中所有打开的图形，使用当前笔描绘路径轮廓，并使用当前画刷填充其内部。 |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | 此记录定义已序列化到数据缓冲区的图像效果参数块。 |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | 此记录指定终端服务器的图形设备上下文状态。 |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | 此记录指定终端服务器的图形设备上下文中的裁剪区域。 |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


此记录指定元文件中 EMF+ 数据的起始。它必须嵌入在第一个 EMF 记录之后的 [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) 记录中（[MS-EMF] 第 2.3.4.2 节记录）。

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


此记录指定元文件中 EMF+ 数据的结束。

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


此记录指定任意私有数据。

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


此记录指定在元文件中遇到的后续 EMF 记录应被处理。当遇到下一个 EMF+ 记录时，EMF 记录将停止处理。

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


此记录已保留，禁止使用。

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


此记录已保留，禁止使用。

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


此记录已保留，禁止使用。

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


此记录指定用于图形操作的对象。

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


此记录清除输出 `coordinate space` 并使用指定的背景颜色和透明度进行初始化。

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


此记录定义如何使用指定的画刷填充一系列矩形的内部。

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


此记录定义绘制一系列矩形的笔画。

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


此记录定义使用指定画刷填充多边形内部的数据。

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


此记录定义绘制一系列相连线条的笔画。

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


此记录定义如何使用指定的画刷填充椭圆的内部。

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


此记录定义绘制椭圆的笔画。

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


此记录定义如何使用指定的画刷填充椭圆内部的某个区域。

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


此记录定义绘制椭圆部分的笔画。

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


该记录定义绘制椭圆弧的笔画。

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


此记录定义如何使用指定的画刷填充区域的内部。

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


该记录定义如何使用指定的画笔填充图形路径中定义的图形内部。路径是一个定义任意线条、曲线和形状序列的对象。

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


该记录定义用于在图形路径中绘制图形的笔画。路径是一个定义任意线条、曲线和形状序列的对象。

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


此记录定义如何使用指定的画刷填充闭合基数样条的内部。

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


此记录定义绘制闭合基数样条的笔和笔画。

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


此记录定义绘制基数样条的笔画。

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


此记录定义绘制贝塞尔样条的笔画。

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


此记录定义一个缩放的 [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) 对象（第 2.2.1.4 节）。图像可以由位图或元文件数据组成。

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


此记录定义一个缩放的 EmfPlusImage 对象，位于平行四边形内。图像可以由位图或元文件数据组成。

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


此记录定义基于字体、布局矩形和格式的文本字符串。

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


此记录定义渲染的原点为指定的水平和垂直坐标。这适用于交叉线画刷以及每像素 8 位和 16 位的抖动模式。

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


此记录定义是否启用或禁用文本抗锯齿。文本抗锯齿是一种在输出表面上绘制字符字形时，使线条和边缘看起来更平滑的方法。

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


此记录定义用于渲染文本的过程。

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


此记录根据指定的文本伽马值设置文本对比度。

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


此记录根据指定的图像过滤类型定义对象的插值模式。插值模式影响缩放（拉伸和收缩）的执行方式。

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


此记录根据指定的像素居中值定义像素偏移模式。

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


此记录根据 alpha 混合状态定义合成模式，该状态指定源颜色如何与背景颜色组合。

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


此记录定义合成质量，描述从多个对象创建复合图像所需的质量水平。

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


此记录将图形状态（由指定索引标识）保存到已保存图形状态的堆栈上。每个堆栈索引与特定的已保存状态关联，且该索引用于 [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) 记录（第 2.3.7.4 节）以恢复状态。

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


此记录从已保存图形状态的堆栈中恢复图形状态（由指定索引标识）。每个堆栈索引与特定的已保存状态关联，且该索引由 [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) 记录（第 2.3.7.5 节）定义以保存状态。

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


此记录打开一个新的图形状态容器并为其指定变换。图形容器用于保留图形状态的元素。

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


此记录打开一个新的图形状态容器。

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


此记录关闭先前通过开始容器操作打开的图形状态容器。

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


此记录根据指定的变换矩阵在 playback device\_context 中定义当前世界空间变换。

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


此记录将当前世界空间变换重置为单位矩阵。

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


此记录将当前世界空间乘以指定的变换矩阵。

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


此记录通过指定的水平和垂直距离对当前世界空间应用平移变换。

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


此记录通过指定的水平和垂直缩放因子对当前世界空间应用缩放变换。

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


此记录按指定角度旋转当前世界空间。

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


此记录为当前世界空间变换指定额外的缩放因子。

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


此记录将世界空间的当前裁剪区域重置为无限。

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


此记录将当前裁剪区域与矩形合并。

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


此记录将当前裁剪区域与图形路径合并。

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


此记录将当前裁剪区域与另一个图形区域合并。

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


此记录对世界空间的当前裁剪区域应用平移变换。

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


此记录指定带有字符位置的文本输出。

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


此记录关闭路径中所有打开的图形，使用当前笔描绘路径轮廓，并使用当前画刷填充其内部。

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


此记录定义已序列化到数据缓冲区的图像效果参数块。

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


此记录指定终端服务器的图形设备上下文状态。

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


此记录指定终端服务器的图形设备上下文中的裁剪区域。

