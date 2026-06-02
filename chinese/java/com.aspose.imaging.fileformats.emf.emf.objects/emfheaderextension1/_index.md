---
title: "EmfHeaderExtension1"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "HeaderExtension1 对象定义了 EMF 元文件头的第一个扩展。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

HeaderExtension1 对象定义了 EMF 元文件头的第一个扩展。它添加了对 PixelFormatDescriptor 对象（第 2.2.22 节）和 OpenGL [OPENGL] 记录（第 2.3.9 节）的支持。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | 获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。 |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | 获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。 |
| [getOffPixelFormat()](#getOffPixelFormat--) | 获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。 |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | 获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。 |
| [getBOpenGl()](#getBOpenGl--) | 获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。 |
| [setBOpenGl(int value)](#setBOpenGl-int-) | 获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。 |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。如果未设置像素格式，则必须为 0x00000000。

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。如果未设置像素格式，则必须为 0x00000000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。如果未设置像素格式，则必须为 0x00000000。

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。如果未设置像素格式，则必须为 0x00000000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。0x00000000 表示元文件中不存在 OpenGL 记录。0x00000001 表示元文件中存在 OpenGL 记录。

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。0x00000000 表示元文件中不存在 OpenGL 记录。0x00000001 表示元文件中存在 OpenGL 记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

