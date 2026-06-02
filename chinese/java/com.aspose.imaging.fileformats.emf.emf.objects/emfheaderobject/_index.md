---
title: "EmfHeaderObject"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Header 对象定义了 EMF 元文件头。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

Header 对象定义了 EMF 元文件头。它指定了创建该元文件图像的设备的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | 初始化 `EmfHeaderObject` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBounds()](#getBounds--) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定以设备单位表示的可围绕存储在元文件中的图像绘制的最小矩形的包含-包含边界。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定以设备单位表示的可围绕存储在元文件中的图像绘制的最小矩形的包含-包含边界。 |
| [getFrame()](#getFrame--) | 获取或设置 WMF RectL 对象，该对象以 0.01 毫米单位指定围绕存储在元文件中的图像的矩形的包含-包含尺寸。 |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | 获取或设置 WMF RectL 对象，该对象以 0.01 毫米单位指定围绕存储在元文件中的图像的矩形的包含-包含尺寸。 |
| [getRecordSignature()](#getRecordSignature--) | 获取或设置一个 32 位无符号整数，用于指定记录签名。 |
| [setRecordSignature(int value)](#setRecordSignature-int-) | 获取或设置一个 32 位无符号整数，用于指定记录签名。 |
| [getVersion()](#getVersion--) | 获取或设置版本（4 字节）：一个 32 位无符号整数，用于指定 EMF 元文件的互操作性。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本（4 字节）：一个 32 位无符号整数，用于指定 EMF 元文件的互操作性。 |
| [getBytes()](#getBytes--) | 获取或设置 32 位无符号整数，指定元文件的大小（字节）。 |
| [setBytes(int value)](#setBytes-int-) | 获取或设置 32 位无符号整数，指定元文件的大小（字节）。 |
| [getRecords()](#getRecords--) | 获取或设置一个 32 位无符号整数，指定元文件中的记录数。 |
| [setRecords(int value)](#setRecords-int-) | 获取或设置一个 32 位无符号整数，指定元文件中的记录数。 |
| [getHandles()](#getHandles--) | 获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。 |
| [setHandles(short value)](#setHandles-short-) | 获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。 |
| [getReserved()](#getReserved--) | 获取或设置一个 16 位无符号整数，该整数必须为 0x0000，且必须被忽略。 |
| [setReserved(short value)](#setReserved-short-) | 获取或设置一个 16 位无符号整数，该整数必须为 0x0000，且必须被忽略。 |
| [getNDesription()](#getNDesription--) | 获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。 |
| [setNDesription(int value)](#setNDesription-int-) | 获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。 |
| [getOffDescription()](#getOffDescription--) | 获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。 |
| [setOffDescription(int value)](#setOffDescription-int-) | 获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。 |
| [getNPalEntries()](#getNPalEntries--) | 获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。 |
| [setNPalEntries(int value)](#setNPalEntries-int-) | 获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。 |
| [getDevice()](#getDevice--) | 获取或设置 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象以像素为单位指定参考设备的大小。 |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | 获取或设置 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象以像素为单位指定参考设备的大小。 |
| [getMillimeters()](#getMillimeters--) | 获取或设置 WMF SizeL 对象，以毫米为单位指定参考设备的大小。 |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | 获取或设置 WMF SizeL 对象，以毫米为单位指定参考设备的大小。 |
| [getValid()](#getValid--) | 获取一个值，指示此 `EmfHeaderObject` 是否有效。 |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


初始化 `EmfHeaderObject` 类的新实例。

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定以设备单位表示的可围绕存储在元文件中的图像绘制的最小矩形的包含-包含边界。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


获取或设置 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象指定以设备单位表示的可围绕存储在元文件中的图像绘制的最小矩形的包含-包含边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


获取或设置 WMF RectL 对象，该对象以 0.01 毫米单位指定围绕存储在元文件中的图像的矩形的包含-包含尺寸。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


获取或设置 WMF RectL 对象，该对象以 0.01 毫米单位指定围绕存储在元文件中的图像的矩形的包含-包含尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


获取或设置一个 32 位无符号整数，指定记录签名。该值必须是 ENHMETA\_SIGNATURE，来自 FormatSignature 枚举（第 2.1.14 节）。

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


获取或设置一个 32 位无符号整数，指定记录签名。该值必须是 ENHMETA\_SIGNATURE，来自 FormatSignature 枚举（第 2.1.14 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置版本（4 字节）：一个 32 位无符号整数，指定 EMF 元文件的互操作性。该值应为 0x00010000。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置版本（4 字节）：一个 32 位无符号整数，指定 EMF 元文件的互操作性。该值应为 0x00010000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


获取或设置 32 位无符号整数，指定元文件的大小（字节）。

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


获取或设置 32 位无符号整数，指定元文件的大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


获取或设置一个 32 位无符号整数，指定元文件中的记录数。

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


获取或设置一个 32 位无符号整数，指定元文件中的记录数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


获取或设置一个 16 位无符号整数，该整数必须为 0x0000，且必须被忽略。

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


获取或设置一个 16 位无符号整数，该整数必须为 0x0000，且必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。如果没有描述字符串，则为零。

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数。如果没有描述字符串，则为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。调色板位于 EMR\_EOF 记录中。

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


获取或设置一个 32 位无符号整数，指定元文件调色板中的条目数。调色板位于 EMR\_EOF 记录中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


获取或设置 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象以像素为单位指定参考设备的大小。

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


获取或设置 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象以像素为单位指定参考设备的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


获取或设置 WMF SizeL 对象，以毫米为单位指定参考设备的大小。

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


获取或设置 WMF SizeL 对象，以毫米为单位指定参考设备的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


获取一个值，指示此 `EmfHeaderObject` 是否有效。

值：如果有效则为 `true`；否则为 `false`。

**Returns:**
boolean
