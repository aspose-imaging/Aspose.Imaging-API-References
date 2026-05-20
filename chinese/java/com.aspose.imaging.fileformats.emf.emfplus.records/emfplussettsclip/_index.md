---
title: "EmfPlusSetTsClip"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusSetTSClip 记录指定终端服务器中图形设备上下文的剪裁区域。"
type: docs
weight: 66
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

该 EmfPlusSetTSClip 记录指定终端服务器中图形设备上下文的剪裁区域。

此记录中数据的压缩方案使用以下算法。每个矩形的每个点要么以单字节编码，要么以 2 字节编码。如果点以单字节编码，则该字节的最高位 (0x80) 必须被置位，值为由低 7 位表示的有符号数。如果最高位未置位，则该值以 2 字节编码，首字节的低 7 位编码高位字节，第二字节编码低位字节。每个点的编码为当前矩形中的点与前一个矩形中的点之间的差值。矩形的底部点编码为当前矩形中底部坐标与顶部坐标之间的差值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetTsClip` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取一个值，指示此 `EmfPlusSetTsClip` 是否已压缩。 |
| [getNumRects()](#getNumRects--) | 获取矩形数量。 |
| [getRects()](#getRects--) | 获取或设置定义裁剪区域的 NumRects 矩形数组。 |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | 获取或设置定义裁剪区域的 NumRects 矩形数组。 |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


初始化 `EmfPlusSetTsClip` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取一个值，指示此 `EmfPlusSetTsClip` 是否已压缩。此位指定 rects 字段中矩形数据的格式。如果设置，则每个矩形占用 4 字节；如果未设置，则每个矩形占用 8 字节。

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


获取矩形数量。此字段指定在 rect 字段中定义的矩形数量。

值：矩形数量。

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


获取或设置定义裁剪区域的 NumRects 矩形数组。此数据的格式由 Flags 字段中的 C 位决定。

值：矩形。

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


获取或设置定义裁剪区域的 NumRects 矩形数组。此数据的格式由 Flags 字段中的 C 位决定。

值：矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

