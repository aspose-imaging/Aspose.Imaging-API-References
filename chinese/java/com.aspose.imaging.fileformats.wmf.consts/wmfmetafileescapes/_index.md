---
title: "WmfMetafileEscapes"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "MetafileEscapes 枚举指定打印机驱动程序功能，这些功能可能无法直接通过 RecordType 枚举中定义的 WMF 记录（第 2.1.1.1 节）访问。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

MetafileEscapes 枚举指定可能无法通过 RecordType 枚举（第 2.1.1.1 节）中定义的 WMF 记录直接访问的打印机驱动程序功能。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Newframe](#Newframe) | 通知打印机驱动程序，应用程序已完成对页面的写入。 |
| [Abortdoc](#Abortdoc) | 停止处理当前文档。 |
| [Nextband](#Nextband) | 通知打印机驱动程序，应用程序已完成对纸带的写入。 |
| [Setcolortable](#Setcolortable) | 设置颜色表值。 |
| [Getcolortable](#Getcolortable) | 获取颜色表值。 |
| [Flushout](#Flushout) | 导致所有未完成的输出被刷新到输出设备。 |
| [Draftmode](#Draftmode) | 指示打印机驱动程序仅应打印文本，而不打印图形。 |
| [Queryescsupport](#Queryescsupport) | 查询打印机驱动程序，以确定其驱动的输出设备是否支持特定的转义函数。 |
| [Setabortproc](#Setabortproc) | 设置应用程序定义的函数，以便在打印过程中可以取消打印作业。 |
| [Startdoc](#Startdoc) | 通知打印机驱动程序，新的打印作业即将开始。 |
| [Enddoc](#Enddoc) | 通知打印机驱动程序，当前打印作业即将结束。 |
| [Getphyspagesize](#Getphyspagesize) | 检索当前在输出设备上选择的物理页面大小。 |
| [Getprintingoffset](#Getprintingoffset) | 检索实际打印或绘图开始位置相对于物理页面左上角的偏移量。 |
| [Getscalingfactor](#Getscalingfactor) | 检索打印机 X 轴和 Y 轴的缩放因子。 |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | 用于在 WMF 元文件中嵌入增强型元文件格式 (EMF) 元文件。 |
| [Setpenwidth](#Setpenwidth) | 设置笔的宽度（以像素为单位）。 |
| [Setcopycount](#Setcopycount) | 设置副本数量。 |
| [Setpapersource](#Setpapersource) | 设置输出表单的来源，例如打印机上的特定纸盘或纸盒。 |
| [Passthrough](#Passthrough) | 此记录传递任意数据。 |
| [Gettechnology](#Gettechnology) | 获取设备支持的图形技术信息。 |
| [Setlinecap](#Setlinecap) | 指定输出到设备时使用的线条绘制模式。 |
| [Setlinejoin](#Setlinejoin) | 指定输出到设备时使用的线段连接模式。 |
| [Setmiterlimit](#Setmiterlimit) | 设置在输出到设备时使用的斜接连接长度限制。 |
| [Bandinfo](#Bandinfo) | 检索或指定设备上有关分条的设置，例如分条数量。 |
| [Drawpatternrect](#Drawpatternrect) | 使用定义的图案绘制矩形。 |
| [Getvectorpensize](#Getvectorpensize) | 检索当前在设备上定义的物理笔大小。 |
| [Getvectorbrushsize](#Getvectorbrushsize) | 检索当前在设备上定义的物理刷子大小。 |
| [Enableduplex](#Enableduplex) | 在设备上启用或禁用双面（双工）打印。 |
| [Getsetpaperbins](#Getsetpaperbins) | 检索或指定设备上输出表单的来源。 |
| [Getsetprintorient](#Getsetprintorient) | 检索或指定设备上的纸张方向。 |
| [Enumpaperbins](#Enumpaperbins) | 检索有关输出设备上不同表单来源的信息。 |
| [Setdibscaling](#Setdibscaling) | 指定设备无关位图（DIB）的缩放比例。 |
| [Epsprinting](#Epsprinting) | 指示封装的 PostScript (EPS) 部分的开始和结束。 |
| [Enumpapermetrics](#Enumpapermetrics) | 查询打印机驱动程序以获取纸张尺寸和其他表单数据。 |
| [Getsetpapermetrics](#Getsetpapermetrics) | 检索或指定输出设备上的纸张尺寸和其他表单数据。 |
| [PostscriptData](#PostscriptData) | 向输出设备发送任意 PostScript 数据。 |
| [PostscriptIgnore](#PostscriptIgnore) | 通知输出设备忽略 PostScript 数据。 |
| [Getdeviceunits](#Getdeviceunits) | 获取当前在输出设备上配置的设备单位。 |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | 获取当前在输出设备上配置的扩展文本度量。 |
| [Getpairkerntable](#Getpairkerntable) | 获取当前在输出设备上定义的字体字距表。 |
| [Exttextout](#Exttextout) | 使用当前选定的字体、背景色和文字颜色绘制文本。 |
| [Getfacename](#Getfacename) | 获取当前在设备上配置的字体名称。 |
| [Downloadface](#Downloadface) | 在设备上设置字体名称。 |
| [MetafileDriver](#MetafileDriver) | 查询打印机驱动程序关于在输出设备上支持元文件的情况。 |
| [Querydibsupport](#Querydibsupport) | 查询打印机驱动程序关于在输出设备上支持 DIB 的情况。 |
| [BeginPath](#BeginPath) | 打开路径。 |
| [ClipToPath](#ClipToPath) | 定义由路径限定的剪裁区域。 |
| [EndPath](#EndPath) | 结束路径。 |
| [OpenChannel](#OpenChannel) | 与使用 NULL 文档和输出文件名、原始模式数据以及类型为零的 STARTDOC 相同。 |
| [Downloadheader](#Downloadheader) | 指示打印机驱动程序下载一组 PostScript 过程。 |
| [CloseChannel](#CloseChannel) | 与 ENDDOC 相同。 |
| [PostscriptPassthrough](#PostscriptPassthrough) | 将任意数据直接发送到打印机驱动程序，预期仅在 PostScript 模式下处理这些数据。 |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | 将任意数据直接发送到打印机驱动程序。 |
| [PostscriptIdentify](#PostscriptIdentify) | 将打印机驱动程序设置为 PostScript 或 GDI 模式。 |
| [PostscriptInjection](#PostscriptInjection) | 在 PostScript 流中插入一块原始数据。 |
| [Checkjpegformat](#Checkjpegformat) | 检查打印机是否支持 JPEG 图像。 |
| [Checkpngformat](#Checkpngformat) | 检查打印机是否支持 PNG 图像。 |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | 获取针对 PostScript 打印机驱动程序的指定功能设置的信息。 |
| [MxdcEscape](#MxdcEscape) | 使应用程序能够以 XML Paper Specification (XPS) 格式将文档写入文件或打印机。 |
| [Spclpassthrough2](#Spclpassthrough2) | 使应用程序能够在文档中包含私有过程和其他任意数据。 |
### Newframe {#Newframe}
```
public static final int Newframe
```


通知打印机驱动程序，应用程序已完成对页面的写入。

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


停止处理当前文档。

### Nextband {#Nextband}
```
public static final int Nextband
```


通知打印机驱动程序，应用程序已完成对纸带的写入。

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


设置颜色表值。

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


获取颜色表值。

### Flushout {#Flushout}
```
public static final int Flushout
```


导致所有未完成的输出被刷新到输出设备。

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


指示打印机驱动程序仅应打印文本，而不打印图形。

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


查询打印机驱动程序，以确定其驱动的输出设备是否支持特定的转义函数。

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


设置应用程序定义的函数，以便在打印过程中可以取消打印作业。

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


通知打印机驱动程序，新的打印作业即将开始。

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


通知打印机驱动程序，当前打印作业即将结束。

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


检索当前在输出设备上选择的物理页面大小。

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


检索实际打印或绘图开始位置相对于物理页面左上角的偏移量。

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


检索打印机 X 轴和 Y 轴的缩放因子。

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


用于在 WMF 元文件中嵌入增强型元文件格式 (EMF) 元文件。

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


设置笔的宽度（以像素为单位）。

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


设置副本数量。

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


设置输出表单的来源，例如打印机上的特定纸盘或纸盒。

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


此记录传递任意数据。

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


获取设备支持的图形技术信息。

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


指定输出到设备时使用的线条绘制模式。

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


指定输出到设备时使用的线段连接模式。

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


设置在输出到设备时使用的斜接连接长度限制。

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


检索或指定设备上有关分条的设置，例如分条数量。

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


使用定义的图案绘制矩形。

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


检索当前在设备上定义的物理笔大小。

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


检索当前在设备上定义的物理刷子大小。

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


在设备上启用或禁用双面（双工）打印。

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


检索或指定设备上输出表单的来源。

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


检索或指定设备上的纸张方向。

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


检索有关输出设备上不同表单来源的信息。

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


指定设备无关位图（DIB）的缩放比例。

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


指示封装的 PostScript (EPS) 部分的开始和结束。

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


查询打印机驱动程序以获取纸张尺寸和其他表单数据。

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


检索或指定输出设备上的纸张尺寸和其他表单数据。

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


向输出设备发送任意 PostScript 数据。

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


通知输出设备忽略 PostScript 数据。

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


获取当前在输出设备上配置的设备单位。

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


获取当前在输出设备上配置的扩展文本度量。

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


获取当前在输出设备上定义的字体字距表。

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


使用当前选定的字体、背景色和文字颜色绘制文本。

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


获取当前在设备上配置的字体名称。

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


在设备上设置字体名称。

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


查询打印机驱动程序关于在输出设备上支持元文件的情况。

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


查询打印机驱动程序关于在输出设备上支持 DIB 的情况。

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


打开路径。

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


定义由路径限定的剪裁区域。输入必须是一个 16 位量，指定要执行的操作。

### EndPath {#EndPath}
```
public static final int EndPath
```


结束路径。

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


与使用 NULL 文档和输出文件名、原始模式数据以及类型为零的 STARTDOC 相同。

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


指示打印机驱动程序下载一组 PostScript 过程。

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


与 ENDDOC 相同。参见 OPEN\_CHANNEL。

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


将任意数据直接发送到打印机驱动程序，预期仅在 PostScript 模式下处理这些数据。 [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify)。

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


将任意数据直接发送到打印机驱动程序。

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


将打印机驱动程序设置为 PostScript 或 GDI 模式。

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


在 PostScript 流中插入一块原始数据。输入必须是一个 32 位量，指定要注入的字节数；一个 16 位量，指定注入点；以及一个 16 位量，指定页码，随后是要注入的字节。

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


检查打印机是否支持 JPEG 图像。

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


检查打印机是否支持 PNG 图像。

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


获取针对 PostScript 打印机驱动程序的指定功能设置的信息。

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


使应用程序能够以 XML Paper Specification (XPS) 格式将文档写入文件或打印机。

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


使应用程序能够在文档中包含私有过程和其他任意数据。

