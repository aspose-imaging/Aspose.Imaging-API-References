---
title: "枚举 WmfMetafileEscapes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfMetafileEscapes 枚举。MetafileEscapes 枚举指定打印机驱动程序功能，这些功能可能无法直接通过在 RecordType 枚举第 2.1.1.1 节中定义的 WMF 记录访问。"
type: docs
weight: 8410
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

此 MetafileEscapes 枚举指定可能无法通过 RecordType 枚举（第 2.1.1.1 节）中定义的 WMF 记录直接访问的打印机驱动程序功能。

```csharp
public enum WmfMetafileEscapes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Newframe | `1` | 通知打印机驱动程序，应用程序已完成对页面的写入。 |
| Abortdoc | `2` | 停止处理当前文档。 |
| Nextband | `3` | 通知打印机驱动程序，应用程序已完成对波段的写入。 |
| Setcolortable | `4` | 设置颜色表值。 |
| Getcolortable | `5` | 获取颜色表值。 |
| Flushout | `6` | 使所有待处理的输出被刷新到输出设备。 |
| Draftmode | `7` | 表明打印机驱动程序应仅打印文本，而不打印图形。 |
| Queryescsupport | `8` | 查询打印机驱动程序，以确定其驱动的输出设备是否支持特定的转义功能。 |
| Setabortproc | `9` | 设置应用程序定义的函数，以便在打印过程中可以取消打印任务。 |
| Startdoc | `10` | 通知打印机驱动程序，新的打印任务即将开始。 |
| Enddoc | `11` | 通知打印机驱动程序当前打印作业即将结束。 |
| Getphyspagesize | `12` | 检索在输出设备上当前选定的物理页面大小。 |
| Getprintingoffset | `13` | 检索从物理页面左上角开始实际打印或绘图的偏移量。 |
| Getscalingfactor | `14` | 检索打印机 X 轴和 Y 轴的缩放因子。 |
| MetaEscapeEnhancedMetafile | `15` | 用于在 WMF 元文件中嵌入增强型元文件格式（EMF）元文件。 |
| Setpenwidth | `16` | 设置笔的宽度（以像素为单位）。 |
| Setcopycount | `17` | 设置副本数量。 |
| Setpapersource | `18` | 设置输出表单的来源，例如打印机上的特定纸盘或纸盒。 |
| Passthrough | `19` | 此记录传递任意数据。 |
| Gettechnology | `20` | 获取设备支持的图形技术信息。 |
| Setlinecap | `21` | 指定在输出到设备时使用的线条绘制模式。 |
| Setlinejoin | `22` | 指定在输出到设备时使用的线段连接模式。 |
| Setmiterlimit | `23` | 设置在输出到设备时使用的斜接连接长度限制。 |
| Bandinfo | `24` | 检索或指定设备上有关分带的设置，例如带的数量。 |
| Drawpatternrect | `25` | 使用定义的图案绘制矩形。 |
| Getvectorpensize | `26` | 检索设备上当前定义的物理笔尺寸。 |
| Getvectorbrushsize | `27` | 检索设备上当前定义的物理刷子尺寸。 |
| Enableduplex | `28` | 启用或禁用设备的双面（双工）打印。 |
| Getsetpaperbins | `29` | 检索或指定设备上输出表单的来源。 |
| Getsetprintorient | `30` | 检索或指定设备上的纸张方向。 |
| Enumpaperbins | `31` | 检索有关输出设备上不同表单来源的信息。 |
| Setdibscaling | `32` | 指定设备无关位图（DIB）的缩放。 |
| Epsprinting | `33` | 指示封装的 PostScript（EPS）段的开始和结束。 |
| Enumpapermetrics | `34` | 查询打印机驱动程序以获取纸张尺寸和其他表单数据。 |
| Getsetpapermetrics | `35` | 检索或指定输出设备上的纸张尺寸和其他表单数据。 |
| PostscriptData | `37` | 将任意 PostScript 数据发送到输出设备。 |
| PostscriptIgnore | `38` | 通知输出设备忽略 PostScript 数据。 |
| Getdeviceunits | `42` | 获取当前在输出设备上配置的设备单位。 |
| Getextendedtextmetrics | `256` | 获取当前在输出设备上配置的扩展文本度量。 |
| Getpairkerntable | `258` | 获取当前在输出设备上定义的字体 kerning 表。 |
| Exttextout | `512` | 使用当前选定的字体、背景颜色和文字颜色绘制文本。 |
| Getfacename | `513` | 获取当前在设备上配置的字体名称。 |
| Downloadface | `514` | 在设备上设置字体名称。 |
| MetafileDriver | `2049` | 查询打印机驱动程序在输出设备上对元文件的支持情况。 |
| Querydibsupport | `3073` | 查询打印机驱动程序在输出设备上对 DIB 的支持情况。 |
| BeginPath | `4096` | 打开路径。 |
| ClipToPath | `4097` | 定义由路径限定的剪裁区域。输入必须是一个 16 位的数值，用于定义要执行的操作。 |
| EndPath | `4098` | 结束路径。 |
| OpenChannel | `4110` | 与使用 NULL 文档和输出文件名、原始模式数据且类型为零的 STARTDOC 相同。 |
| Downloadheader | `4111` | 指示打印机驱动程序下载一组 PostScript 过程。 |
| CloseChannel | `4112` | 与 ENDDOC 相同。参见 OPEN_CHANNEL。 |
| PostscriptPassthrough | `4115` | 直接向打印机驱动程序发送任意数据，预期仅在 PostScript 模式下处理这些数据。PostscriptIdentify。 |
| EncapsulatedPostscript | `4116` | 直接向打印机驱动程序发送任意数据。 |
| PostscriptIdentify | `4117` | 将打印机驱动程序设置为 PostScript 模式或 GDI 模式。 |
| PostscriptInjection | `4118` | 在 PostScript 流中插入一块原始数据。输入必须是一个 32 位的数值，指定要注入的字节数，一个 16 位的数值，指定注入点，以及一个 16 位的数值，指定页码，随后是要注入的字节。 |
| Checkjpegformat | `4119` | 检查打印机是否支持 JPEG 图像。 |
| Checkpngformat | `4120` | 检查打印机是否支持 PNG 图像。 |
| GetPsFeaturesetting | `4121` | 获取针对 PostScript 打印机驱动程序的指定功能设置的信息。 |
| MxdcEscape | `4122` | 使应用程序能够以 XML 纸张规范 (XPS) 格式将文档写入文件或打印机。 |
| Spclpassthrough2 | `4568` | 使应用程序能够在文档中包含私有过程和其他任意数据。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


