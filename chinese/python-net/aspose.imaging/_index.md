---
title: "aspose.imaging"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging/
---


该模块是嵌套模块的核心，也是用于 Aspose.Imaging 处理的最基本对象。

## **Classes**
| **Class** | **描述** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | 定义混合模式。此类不可被继承。 |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | 基础画刷类。 |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | 包含当前构建版本信息。 |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | 包含缓存设置。 |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | 像素的 CMYK 颜色。 |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | 用于处理以有符号 32 位整数表示的 CMYK 颜色的辅助方法。<br/>            提供与 [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) 结构体类似的 API。<br/>            由于 CMYK 颜色仅以 Int32 而非包含内部字段的结构体呈现，因而更轻量。<br/>            请在可能的情况下优先使用此类的静态方法，而不是已弃用的<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) 结构体。 |
| [Color](/imaging/python-net/aspose.imaging/color/) | 像素的颜色。 |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | 定义用于在多色渐变中进行颜色混合插值的颜色和位置数组。此类不可被继承。 |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | 定义用于转换颜色的映射表。多个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 类的方法通过使用颜色重新映射表（即 [ColorMap](/imaging/python-net/aspose.imaging/colormap/) 结构数组）来调整图像颜色。此类不可继承。 |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | 定义一个 5 x 5 矩阵，包含 RGBA 空间的坐标。多个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 类的方法通过使用颜色矩阵来调整图像颜色。此类不可被继承。 |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | 定义组成调色板的颜色数组。这些颜色为 32 位 ARGB 颜色。此类不可继承。 |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | 用于调色板操作的辅助类。 |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | 在 GDI+ Color 结构之间转换颜色。此类不可被继承。 |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | 封装自定义用户定义的线帽。 |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | 数据流容器。 |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | 表示可释放的对象。 |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | 嵌入式图像类 |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | 图形。形状的容器。 |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | 用于文件流处理的辅助工具。 |
| [Font](/imaging/python-net/aspose.imaging/font/) | 定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。 |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | 通用成像矢量格式渲染器的字体设置。 |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | 根据当前程序集使用的图形引擎表示图形。 |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | 表示一系列相连的直线和曲线。此类不可被继承。 |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | 高级缓冲区处理器。 |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | 动画帧 |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | 缓冲区处理器。 |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | 颜色转换器。 |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 调色板接口。 |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | 图像元数据接口。 |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | 图像创建器。 |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | 指定创建器属性的图像创建器描述符。创建器描述符用于克服<br/>            必须在内存中保留每个图像创建器实例以及多线程问题的需求。 |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | 图像描述符。包含所有其他图像描述符类型的基础属性和方法。 |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | 图像导出器。可以将内部 `aspose.imaging` 格式的数据导出为指定的数据格式。 |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | 表示图像导出器描述符。导出器描述符用于克服必须在内存中保留每个导出器实例以及多线程问题的需求<br/>            用于克服必须在内存中保留每个导出器实例以及多线程问题的需求。 |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | 图像加载器。 |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | 指定加载器属性的图像加载器描述符。加载器描述符用于克服<br/>            必须在内存中保留每个图像加载器实例以及多线程问题的需求。 |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | 索引图像格式的颜色转换器。 |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | 图像元数据容器接口。 |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | 多页图像接口 |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | 扩展多页图像接口 |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | 表示具有边界的对象。 |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | 表示有序形状。有序形状是一组具有起点和终点的连续点集合。<br/>            使用特定规则连接的连续点集合。 |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 符合部分加载的 32 位 ARGB 像素。 |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | 符合部分加载的像素。 |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | 部分数据加载器。 |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | 光栅图像 32 位 ARGB 像素加载器。 |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | 光栅图像 64 位 ARGB 像素加载器。 |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | 光栅图像像素加载器。 |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | 光栅图像原始数据加载器。 |
| [Image](/imaging/python-net/aspose.imaging/image/) | 图像是所有类型图像的基类。 |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | 一个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象包含有关在渲染过程中位图和元文件颜色如何被操作的信息。一个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染期间，颜色可以被校正、变暗、变亮或移除。要应用这些操作，请初始化一个 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象，并将该 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 对象的路径（以及 [Image](/imaging/python-net/aspose.imaging/image/) 的路径）传递给 DrawImage 方法。 |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | 表示图像创建者注册表。 |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | 表示图像导出器注册表。 |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | 表示图像加载器注册表。 |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像基础选项。 |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像缩放设置类 |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | 表示元素序列的类 |
| [License](/imaging/python-net/aspose.imaging/license/) | 提供对组件授权的方法。 |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 表示加载选项。 |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 替代 GDI+ 矩阵。 |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | 提供计量方法以进行集成 |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | 表示非泛型字典。 |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | 非泛型对象列表 |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | 具有边界的对象。 |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | 系统中已安装的 OpenType 字体缓存。 |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | 定义用于绘制线条、曲线和图形的对象。 |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | 像素数据格式。这是一个不可变对象。 |
| [Point](/imaging/python-net/aspose.imaging/point/) | 表示整数 x 和 y 坐标的有序对，定义二维平面中的一点。 |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | 表示浮点数 x 和 y 坐标的有序对，定义二维平面中的一点。 |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | 表示支持光栅图形操作的光栅图像。需要时此图像会缓存像素数据。 |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | 光栅多页图像 |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 表示支持光栅图形操作的光栅图像。 |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 原始数据设置 |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 存储表示矩形位置和大小的四个整数。 |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 存储表示矩形位置和大小的四个浮点数。 |
| [Region](/imaging/python-net/aspose.imaging/region/) | 描述由矩形和路径组成的图形形状的内部。此类不可被继承。 |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | 移除背景设置 |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | 图像保存选项的分辨率设置。 |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | 形状。使用特定规则连接的连续点集。 |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | 表示形状段。段是连接两个点的直线或曲线。 |
| [Size](/imaging/python-net/aspose.imaging/size/) | 表示大小。 |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | 存储一对有序的浮点数，通常是矩形的宽度和高度。 |
| [Source](/imaging/python-net/aspose.imaging/source/) | 该源用于包含对象管道的所有相关信息。 |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | 表示拆分流容器，包含流并提供流处理例程。 |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | 表示流容器，包含流并提供流处理例程。 |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 封装文本布局信息（如对齐、方向和制表位）、显示操作（如省略号插入和国家数字替换）以及 OpenType 功能。此类不可被继承。 |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | 支持透明度的对象。 |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | 矢量图像是所有类型矢量图像的基类。 |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | 矢量多页图像 |
## **Enumerations**
| **Enumeration** | **描述** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | 指示图形在显示后应如何处理。 |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | 指定要使用的缓存类型。 |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | 表示使用的字符集。 |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | 指定哪些对象使用颜色调整信息。 |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | 指定 CMYK（青色、品红、黄色、黑色）颜色空间中的各个通道。此枚举由 SetOutputChannel 方法使用。 |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | 用于调整到最近邻的颜色比较方法。 |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | 指定将受到 [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) 的颜色和灰度调整设置影响的图像和颜色类型。 |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | 颜色量化方法 |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | 指定合成期间使用的质量级别。 |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | 指定在虚线的每段破折号两端使用的图形形状类型。 |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | 指定使用 [Pen](/imaging/python-net/aspose.imaging/pen/) 对象绘制的虚线样式。 |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | 数据恢复模式。 |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | 用于控制颜色转换的抖动方法。 |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | 受支持的图像文件格式之一。 |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | 指定封闭路径内部的填充方式。 |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | 指定应用于文本的样式信息。 |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | 指定给定数据的计量单位。 |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | 指定 [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/) 对象可用的不同图案。 |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | 指定与文本相关的快捷键前缀的显示类型。 |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | 要使用的图像过滤器 |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | 枚举 [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) 指定在对图像进行缩放或旋转时使用的算法。 |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | 指定已知的系统颜色。 |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | 指定 [Pen](/imaging/python-net/aspose.imaging/pen/) 对象可以用于线段结束的可用帽子样式。 |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | 指定如何在 [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) 对象中包含的图形（子路径）中连接连续的直线或曲线段。 |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | 指定矩阵变换操作的顺序。 |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | 图像调色板挖掘方法 |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | 指定输出文件的 PDF 合规级别。 |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | 指定 [Pen](/imaging/python-net/aspose.imaging/pen/) 对象相对于理论的零宽度线的对齐方式。 |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | 指定 [Pen](/imaging/python-net/aspose.imaging/pen/) 对象用于填充线条的填充类型。 |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | 像素数据格式的实际含义。 |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | 处理类型。 |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 指定调整大小的类型。 |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | 分辨率单位枚举。 |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 指定图像旋转的角度以及用于翻转图像的轴。 |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | 提供表示 [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) 中用于定位的参考点的字段。 |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | 指定是否对线条、曲线以及填充区域的边缘应用平滑（抗锯齿）。 |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | 指定文本字符串相对于其布局矩形的对齐方式。 |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | 枚举指定如何根据用户的区域设置或语言在字符串中替换数字。 |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | 指定文本字符串的显示和布局信息。 |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | 指定如何从未完全适合布局形状的字符串中修剪字符。 |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | 指定文本渲染的质量。 |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | 指定所应用的扭曲变换类型。 |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | 指定当纹理或渐变小于填充区域时的平铺方式。 |
