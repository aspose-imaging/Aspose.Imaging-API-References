---
title: "EmfInvertRgn"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_INVERTRGN 记录反转指定区域中的颜色。"
type: docs
weight: 67
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

EMR\_INVERTRGN 记录反转指定区域的颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfInvertRgn` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。 |
| [getRgnDataSize()](#getRgnDataSize--) | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| [getRgnData()](#getRgnData--) | 获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData 对象。 |
| [setRgnData(byte[] value)](#setRgnData-byte---) | 获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData 对象。 |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


初始化 `EmfInvertRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData 对象。

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


获取或设置一个长度为 RgnDataSize 的字节数组，指定以逻辑单位表示的 RegionData 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

