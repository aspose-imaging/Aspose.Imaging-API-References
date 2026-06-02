---
title: "枚举 EmfPlusRecordType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusRecordType 枚举。RecordType 枚举定义了在 EMF 元文件中使用的记录类型。"
type: docs
weight: 5150
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

RecordType 枚举定义了 EMF+ 元文件中使用的记录类型。

```csharp
public enum EmfPlusRecordType : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| EmfPlusHeader | `16385` | 此记录指定了元文件中 EMF+ 数据的开始。它必须嵌入在 [`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 记录之后的第一个 EMF 记录中（[MS-EMF] 第 2.3.4.2 节记录）。 |
| EmfPlusEndOfFile | `16386` | 此记录指定了元文件中 EMF+ 数据的结束。 |
| EmfPlusComment | `16387` | 此记录指定任意私有数据。 |
| EmfPlusGetDC | `16388` | 此记录指定在元文件中遇到的后续 EMF 记录应当被处理。当遇到下一个 EMF+ 记录时，EMF 记录的处理将停止。 |
| EmfPlusMultiFormatStart | `16389` | 此记录已保留，且不得使用。 |
| EmfPlusMultiFormatSection | `16390` | 此记录已保留，且不得使用。 |
| EmfPlusMultiFormatEnd | `16391` | 此记录已保留，且不得使用。 |
| EmfPlusObject | `16392` | 此记录指定了用于图形操作的对象。 |
| EmfPlusClear | `16393` | 此记录清除输出 `coordinate space` 并使用指定的背景颜色和透明度进行初始化。 |
| EmfPlusFillRects | `16394` | 此记录定义了使用指定画刷填充一系列矩形内部的方式。 |
| EmfPlusDrawRects | `16395` | 此记录定义了绘制一系列矩形的笔画。 |
| EmfPlusFillPolygon | `16396` | 此记录定义了使用指定画刷填充多边形内部的数据。 |
| EmfPlusDrawLines | `16397` | 此记录定义了绘制一系列相连线段的笔画。 |
| EmfPlusFillEllipse | `16398` | 此记录定义了使用指定画刷填充椭圆内部的方式。 |
| EmfPlusDrawEllipse | `16399` | 此记录定义了绘制椭圆的笔画。 |
| EmfPlusFillPie | `16400` | 此记录定义了使用指定画刷填充椭圆内部某个部分的方式。 |
| EmfPlusDrawPie | `16401` | 此记录定义了绘制椭圆某个部分的笔画。 |
| EmfPlusDrawArc | `16402` | 此记录定义了绘制椭圆弧线的笔画。 |
| EmfPlusFillRegion | `16403` | 此记录定义了使用指定画刷填充区域内部的方式。 |
| EmfPlusFillPath | `16404` | 此记录定义了使用指定画刷填充图形路径中定义的图形内部的方式。路径是一个定义任意线条、曲线和形状序列的对象。 |
| EmfPlusDrawPath | `16405` | 此记录定义了绘制图形路径中图形的笔画。路径是一个定义任意线条、曲线和形状序列的对象。 |
| EmfPlusFillClosedCurve | `16406` | 此记录定义了使用指定画刷填充闭合基数样条曲线内部的方式。 |
| EmfPlusDrawClosedCurve | `16407` | 此记录定义了绘制闭合基数样条曲线的笔和笔画。 |
| EmfPlusDrawCurve | `16408` | 此记录定义了绘制基数样条曲线的笔画。 |
| EmfPlusDrawBeziers | `16409` | 此记录定义了绘制贝塞尔样条曲线的笔画。 |
| EmfPlusDrawImage | `16410` | 此记录定义了一个缩放的 [`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) 对象（第 2.2.1.4 节）。图像可以由位图或元文件数据组成。 |
| EmfPlusDrawImagePoints | `16411` | 此记录定义了在平行四边形内的缩放 EmfPlusImage 对象。图像可以由位图或元文件数据组成。 |
| EmfPlusDrawString | `16412` | 此记录基于字体、布局矩形和格式定义文本字符串。 |
| EmfPlusSetRenderingOrigin | `16413` | 此记录将渲染原点定义为指定的水平和垂直坐标。此规则适用于交叉线画刷以及每像素 8 位和 16 位的抖动模式。 |
| EmfPlusSetAntiAliasMode | `16414` | 此记录定义是否启用或禁用文本抗锯齿。文本抗锯齿是一种在输出表面绘制字符字形时，使线条和边缘看起来更平滑的方法。 |
| EmfPlusSetTextRenderingHint | `16415` | 此记录定义用于渲染文本的过程。 |
| EmfPlusSetTextContrast | `16416` | 此记录根据指定的文本伽马值设置文本对比度。 |
| EmfPlusSetInterpolationMode | `16417` | 此记录根据指定的图像过滤类型定义对象的插值模式。插值模式影响缩放（拉伸和收缩）的执行方式。 |
| EmfPlusSetPixelOffsetMode | `16418` | 此记录根据指定的像素居中值定义像素偏移模式。 |
| EmfPlusSetCompositingMode | `16419` | 此记录根据 alpha 混合的状态定义合成模式，该模式指定源颜色如何与背景颜色组合。 |
| EmfPlusSetCompositingQuality | `16420` | 此记录定义合成质量，描述从多个对象创建复合图像所需的质量水平。 |
| EmfPlusSave | `16421` | 此记录将由指定索引标识的图形状态保存到已保存图形状态的堆栈上。每个堆栈索引对应特定的已保存状态，且该索引用于 [`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) 记录（第 2.3.7.4 节）以恢复状态。 |
| EmfPlusRestore | `16422` | 此记录从已保存图形状态的堆栈中恢复由指定索引标识的图形状态。每个堆栈索引对应特定的已保存状态，且该索引由 [`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) 记录（第 2.3.7.5 节）定义，用于保存状态。 |
| EmfPlusBeginContainer | `16423` | 此记录打开一个新的图形状态容器并为其指定变换。图形容器用于保留图形状态的元素。 |
| EmfPlusBeginContainerNoParams | `16424` | 此记录打开一个新的图形状态容器。 |
| EmfPlusEndContainer | `16425` | 此记录关闭先前通过开始容器操作打开的图形状态容器。 |
| EmfPlusSetWorldTransform | `16426` | 此记录根据指定的变换矩阵定义播放 device_context 中的当前世界空间变换。 |
| EmfPlusResetWorldTransform | `16427` | 此记录将当前世界空间变换重置为单位矩阵。 |
| EmfPlusMultiplyWorldTransform | `16428` | 此记录将当前世界空间乘以指定的变换矩阵。 |
| EmfPlusTranslateWorldTransform | `16429` | 此记录通过指定的水平和垂直距离对当前世界空间应用平移变换。 |
| EmfPlusScaleWorldTransform | `16430` | 此记录通过指定的水平和垂直比例因子对当前世界空间应用缩放变换。 |
| EmfPlusRotateWorldTransform | `16431` | 此记录按指定角度旋转当前世界空间。 |
| EmfPlusSetPageTransform | `16432` | 此记录为当前世界空间变换指定额外的缩放因子。 |
| EmfPlusResetClip | `16433` | 此记录将世界空间的当前裁剪区域重置为无限。 |
| EmfPlusSetClipRect | `16434` | 此记录将当前裁剪区域与矩形合并。 |
| EmfPlusSetClipPath | `16435` | 此记录将当前裁剪区域与图形路径合并。 |
| EmfPlusSetClipRegion | `16436` | 此记录将当前裁剪区域与另一个图形区域合并。 |
| EmfPlusOffsetClip | `16437` | 此记录对世界空间的当前裁剪区域应用平移变换。 |
| EmfPlusDrawDriverString | `16438` | 此记录指定带有字符位置的文本输出。 |
| EmfPlusStrokeFillPath | `16439` | 此记录关闭路径中所有打开的图形，使用当前画笔描绘路径轮廓，并使用当前画刷填充其内部。 |
| EmfPlusSerializableObject | `16440` | 此记录定义已序列化到数据缓冲区的图像效果参数块。 |
| EmfPlusSetTSGraphics | `16441` | 此记录指定终端服务器的图形设备上下文的状态。 |
| EmfPlusSetTSClip | `16442` | 此记录指定终端服务器的图形设备上下文中的裁剪区域。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


