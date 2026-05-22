---
title: "WmfMetafileEscapes 枚举"
type: docs
weight: 150
url: /zh/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

MetafileEscapes 枚举指定打印机驱动程序功能，这些功能可能无法直接通过 RecordType 枚举中定义的 WMF 记录<br/>                （第 2.1.1.1 节）访问。

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| ABORTDOC | 停止处理当前文档。 |
| BANDINFO | 检索或指定有关设备分条的设置，例如<br/>                条带数量。 |
| BEGIN_PATH | 打开路径。 |
| CHECKJPEGFORMAT | 检查打印机是否支持 JPEG 图像。 |
| CHECKPNGFORMAT | 检查打印机是否支持 PNG 图像。 |
| CLIP_TO_PATH | 定义由路径限定的剪裁区域。输入必须是一个 16 位<br/>                用于定义要采取的操作的数量。 |
| CLOSE_CHANNEL | 与 ENDDOC 相同。请参阅 OPEN_CHANNEL。 |
| DOWNLOADFACE | 在设备上设置字体名称。 |
| DOWNLOADHEADER | 指示打印机驱动程序下载一组 PostScript 过程。 |
| DRAFTMODE | 指示打印机驱动程序只能打印文本，不打印图形。 |
| DRAWPATTERNRECT | 使用定义的图案绘制矩形。 |
| ENABLEDUPLEX | 在设备上启用或禁用双面（双工）打印。 |
| ENCAPSULATED_POSTSCRIPT | 直接向打印机驱动程序发送任意数据。 |
| ENDDOC | 通知打印机驱动程序当前打印作业即将结束。 |
| END_PATH | 结束路径。 |
| ENUMPAPERBINS | 检索有关不同表单来源的信息在一个<br/>                输出设备上。 |
| ENUMPAPERMETRICS | 查询打印机驱动程序的纸张尺寸和其他表单数据。 |
| EPSPRINTING | 指示封装的 PostScript (EPS) 部分的开始和结束。 |
| EXTTEXTOUT | 使用当前选定的字体、背景颜色和文字颜色绘制文本。 |
| FLUSHOUT | 导致所有未处理的输出被刷新到输出设备。 |
| GETCOLORTABLE | 获取颜色表值。 |
| GETDEVICEUNITS | 获取当前在输出设备上配置的设备单位。 |
| GETEXTENDEDTEXTMETRICS | 获取当前在输出<br/>                设备上配置的扩展文本度量。 |
| GETFACENAME | 获取当前在设备上配置的字体名称。 |
| GETPAIRKERNTABLE | 获取当前在输出设备上定义的字体字距表。 |
| GETPHYSPAGESIZE | 检索当前在输出设备上选择的物理页面尺寸。 |
| GETPRINTINGOFFSET | 检索物理页面左上角到实际打印或绘制开始位置的偏移量<br/>                。 |
| GETSCALINGFACTOR | 检索打印机的 X 轴和 Y 轴的缩放因子。 |
| GETSETPAPERBINS | 检索或指定设备上输出表单的来源。 |
| GETSETPAPERMETRICS | 检索或指定纸张尺寸及其他表单数据在一个<br/>                输出设备上。 |
| GETSETPRINTORIENT | 检索或指定设备上的纸张方向。 |
| GETTECHNOLOGY | 获取有关在<br/>                设备上受支持的图形技术的信息。 |
| GETVECTORBRUSHSIZE | 检索当前在设备上定义的物理画笔大小。 |
| GETVECTORPENSIZE | 检索当前在设备上定义的物理笔大小。 |
| GET_PS_FEATURESETTING | 获取有关 PostScript<br/>                打印机驱动程序的指定功能设置的信息。 |
| METAFILE_DRIVER | 查询打印机驱动程序关于在输出<br/>                设备上对元文件的支持情况。 |
| META_ESCAPE_ENHANCED_METAFILE | 用于在 WMF 元文件中嵌入增强型元文件格式 (EMF)<br/>                元文件。 |
| MXDC_ESCAPE | 使应用程序能够以 XML Paper<br/>                Specification (XPS) 格式将文档写入文件或打印机。 |
| NEWFRAME | 通知打印机驱动程序应用程序已完成对页面的写入。 |
| NEXTBAND | 通知打印机驱动程序应用程序已完成对波段的写入。 |
| OPEN_CHANNEL | 与使用 NULL 文档和输出<br/>                文件名、原始模式数据以及类型为零的 STARTDOC 相同。 |
| PASSTHROUGH | 此记录传递任意数据。 |
| POSTSCRIPT_DATA | 向输出设备发送任意 PostScript 数据。 |
| POSTSCRIPT_IDENTIFY | 将打印机驱动程序设置为 PostScript 或 GDI 模式。 |
| POSTSCRIPT_IGNORE | 通知输出设备忽略 PostScript 数据。 |
| POSTSCRIPT_INJECTION | 将一块原始数据插入到 PostScript 流中。输入<br/>                必须是一个 32 位数量，指定要注入的字节数，一个 16 位数量，指定注入点，以及一个 16 位数量，指定页码，随后是<br/>                要注入的字节。 |
| POSTSCRIPT_PASSTHROUGH | 将任意数据直接发送到打印机驱动程序，<br/>                该驱动程序仅在 PostScript 模式下才会处理这些数据。 [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/)。 |
| QUERYDIBSUPPORT | 查询打印机驱动程序在输出设备上对 DIB 的支持情况。 |
| QUERYESCSUPPORT | 查询打印机驱动程序，以确定其驱动的输出设备是否支持特定的转义函数<br/>                。 |
| SETABORTPROC | 设置应用程序定义的函数，以便在打印过程中可以取消打印作业<br/>                。 |
| SETCOLORTABLE | 设置颜色表值。 |
| SETCOPYCOUNT | 设置副本数量。 |
| SETDIBSCALING | 指定设备无关位图 (DIB) 的缩放比例。 |
| SETLINECAP | 指定在输出到设备时使用的线条绘制模式。 |
| SETLINEJOIN | 指定在输出到设备时使用的线段连接模式。 |
| SETMITERLIMIT | 设置在输出到设备时使用的斜接连接长度限制。 |
| SETPAPERSOURCE | 设置源，例如打印机上的特定纸盘或纸盒，用于<br/>                输出表单。 |
| SETPENWIDTH | 设置笔的宽度（以像素为单位）。 |
| SPCLPASSTHROUGH2 | 允许应用程序在文档中包含私有过程和其他任意<br/>                数据。 |
| STARTDOC | 通知打印机驱动程序有新的打印作业正在开始。 |
