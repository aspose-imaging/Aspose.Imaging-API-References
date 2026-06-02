---
title: "EmfPlusRecordType 枚举"
type: docs
weight: 360
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

RecordType 枚举定义了 EMF+ 元文件中使用的记录类型。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | 此记录打开一个新的图形状态容器并为其指定变换。图形容器用于保留图形状态的元素。 |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | 此记录打开一个新的图形状态容器。 |
| EMF_PLUS_CLEAR | 此记录清除输出 <c>coordinate space</c> 并使用指定的背景颜色和透明度进行初始化。 |
| EMF_PLUS_COMMENT | 此记录指定任意私有数据。 |
| EMF_PLUS_DRAW_ARC | 该记录定义用于绘制椭圆弧的笔画。 |
| EMF_PLUS_DRAW_BEZIERS | 此记录定义用于绘制贝塞尔样条的笔画。 |
| EMF_PLUS_DRAW_CLOSED_CURVE | 此记录定义用于绘制闭合基数样条的笔和笔画。 |
| EMF_PLUS_DRAW_CURVE | 此记录定义用于绘制基数样条的笔画。 |
| EMF_PLUS_DRAW_DRIVER_STRING | 此记录指定带有字符位置的文本输出。 |
| EMF_PLUS_DRAW_ELLIPSE | 此记录定义用于绘制椭圆的笔画。 |
| EMF_PLUS_DRAW_IMAGE | 此记录定义一个缩放的 [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) 对象（第 2.2.1.4 节）。图像可以由位图或元文件数据组成。 |
| EMF_PLUS_DRAW_IMAGE_POINTS | 此记录定义在平行四边形内的缩放 EmfPlusImage 对象。图像可以由位图或元文件数据组成。 |
| EMF_PLUS_DRAW_LINES | 此记录定义用于绘制一系列相连线条的笔画。 |
| EMF_PLUS_DRAW_PATH | 该记录定义了在图形路径中绘制图形的笔画。路径是一个定义任意序列的线条、曲线和形状的对象。 |
| EMF_PLUS_DRAW_PIE | 此记录定义了用于绘制椭圆部分的笔画。 |
| EMF_PLUS_DRAW_RECTS | 此记录定义了用于绘制一系列矩形的笔画。 |
| EMF_PLUS_DRAW_STRING | 此记录基于字体、布局矩形和格式定义了文本字符串。 |
| EMF_PLUS_END_CONTAINER | 此记录关闭了先前由开始容器操作打开的图形状态容器。 |
| EMF_PLUS_END_OF_FILE | 此记录指定了元文件中 EMF+ 数据的结束。 |
| EMF_PLUS_FILL_CLOSED_CURVE | 此记录定义了使用指定画刷填充闭合基数样条内部的方法。 |
| EMF_PLUS_FILL_ELLIPSE | 此记录定义了使用指定画刷填充椭圆内部的方法。 |
| EMF_PLUS_FILL_PATH | 该记录定义了使用指定画刷填充图形路径中定义的图形内部的方法。路径是一个定义任意序列的线条、曲线和形状的对象。 |
| EMF_PLUS_FILL_PIE | 此记录定义了使用指定画刷填充椭圆内部某一部分的方法。 |
| EMF_PLUS_FILL_POLYGON | 此记录定义了使用指定画刷填充多边形内部的数据。 |
| EMF_PLUS_FILL_RECTS | 此记录定义了使用指定画刷填充一系列矩形内部的方法。 |
| EMF_PLUS_FILL_REGION | 此记录定义了如何使用指定的画笔填充区域的内部。 |
| EMF_PLUS_GET_DC | 此记录指定在元文件中遇到的后续 EMF 记录应当被处理。当遇到下一个 EMF+ 记录时，EMF 记录的处理将停止。 |
| EMF_PLUS_HEADER | 此记录指定 EMF+ 数据在元文件中的开始。它必须嵌入在第一个 EMF 记录中，位于 [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) 记录之后（[MS-EMF] 第 2.3.4.2 节记录）。 |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | 此记录使用指定的变换矩阵乘以当前的世界空间。 |
| EMF_PLUS_MULTI_FORMAT_END | 此记录已保留，禁止使用。 |
| EMF_PLUS_MULTI_FORMAT_SECTION | 此记录已保留，禁止使用。 |
| EMF_PLUS_MULTI_FORMAT_START | 此记录已保留，禁止使用。 |
| EMF_PLUS_OBJECT | 此记录指定用于图形操作的对象。 |
| EMF_PLUS_OFFSET_CLIP | 此记录对世界空间的当前裁剪区域应用平移变换。 |
| EMF_PLUS_RESET_CLIP | 此记录将世界空间的当前裁剪区域重置为无限。 |
| EMF_PLUS_RESET_WORLD_TRANSFORM | 此记录将当前世界空间的变换重置为单位矩阵。 |
| EMF_PLUS_RESTORE | 此记录从已保存图形状态的堆栈中恢复由指定索引标识的图形状态。每个堆栈索引对应特定的已保存状态，该索引由 [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) 记录（第 2.3.7.5 节）定义，用于保存状态。 |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | 此记录按指定角度旋转当前的世界空间。 |
| EMF_PLUS_SAVE | 此记录将由指定索引标识的图形状态保存到已保存图形状态的堆栈中。每个堆栈索引对应特定的已保存状态，该索引由 [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) 记录（第 2.3.7.4 节）使用，以恢复状态。 |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | 此记录通过指定的水平和垂直缩放因子对当前世界空间应用缩放变换。 |
| EMF_PLUS_SERIALIZABLE_OBJECT | 此记录定义了一个已序列化到数据缓冲区的图像效果参数块。 |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | 此记录定义是否启用或禁用文本抗锯齿。文本抗锯齿是一种在输出表面上绘制字符字形时，使线条和边缘看起来更平滑的方法。 |
| EMF_PLUS_SET_CLIP_PATH | 此记录将当前裁剪区域与图形路径合并。 |
| EMF_PLUS_SET_CLIP_RECT | 此记录将当前裁剪区域与矩形合并。 |
| EMF_PLUS_SET_CLIP_REGION | 此记录将当前裁剪区域与另一个图形区域合并。 |
| EMF_PLUS_SET_COMPOSITING_MODE | 此记录根据 alpha 混合的状态定义合成模式，该模式指定源颜色如何与背景颜色组合。 |
| EMF_PLUS_SET_COMPOSITING_QUALITY | 此记录定义合成质量，描述从多个对象创建复合图像所需的质量水平。 |
| EMF_PLUS_SET_INTERPOLATION_MODE | 此记录根据指定的图像过滤类型定义对象的插值模式。插值模式影响缩放（拉伸和收缩）的执行方式。 |
| EMF_PLUS_SET_PAGE_TRANSFORM | 此记录为当前世界空间变换指定额外的缩放因子。 |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | 此记录根据指定的像素居中值定义像素偏移模式。 |
| EMF_PLUS_SET_RENDERING_ORIGIN | 此记录将渲染原点定义为指定的水平和垂直坐标。这适用于交叉线刷以及每像素 8 位和 16 位的抖动图案。 |
| EMF_PLUS_SET_TEXT_CONTRAST | 此记录根据指定的文本伽马值设置文本对比度。 |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | 此记录定义用于渲染文本的过程。 |
| EMF_PLUS_SET_TS_CLIP | 此记录指定终端服务器的图形设备上下文中的裁剪区域。 |
| EMF_PLUS_SET_TS_GRAPHICS | 此记录指定终端服务器的图形设备上下文的状态。 |
| EMF_PLUS_SET_WORLD_TRANSFORM | 此记录根据指定的变换矩阵定义回放 device_context 中当前的世界空间变换。 |
| EMF_PLUS_STROKE_FILL_PATH | 此记录关闭路径中所有未闭合的图形，使用当前笔描绘路径轮廓，并使用当前刷子填充其内部。 |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | 此记录通过指定的水平和垂直距离对当前世界空间应用平移变换。 |
