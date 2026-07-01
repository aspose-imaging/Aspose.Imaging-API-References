---
title: "EmfPixelFormatDescriptor"
second_title: "Aspose.Imaging for Java API 参考"
description: "PixelFormatDescriptor 对象可用于 EMR_HEADER 记录第 2.3.4.2 节，以指定回放设备上下文的输出表面的像素格式。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

PixelFormatDescriptor 对象可在 EMR\_HEADER 记录（第 2.3.4.2 节）中使用，以指定回放设备上下文的输出表面的像素格式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNSize()](#getNSize--) | 获取或设置一个 16 位整数，指定此数据结构的大小（字节）。 |
| [setNSize(short value)](#setNSize-short-) | 获取或设置一个 16 位整数，指定此数据结构的大小（字节）。 |
| [getNVersion()](#getNVersion--) | 获取或设置一个 16 位整数，必须设置为 0x0001。 |
| [setNVersion(short value)](#setNVersion-short-) | 获取或设置一个 16 位整数，必须设置为 0x0001。 |
| [getDwFlags()](#getDwFlags--) | 获取或设置位标志，指定用于输出到绘图表面的像素缓冲区的属性。 |
| [setDwFlags(int value)](#setDwFlags-int-) | 获取或设置位标志，指定用于输出到绘图表面的像素缓冲区的属性。 |
| [getIPixelType()](#getIPixelType--) | 获取或设置像素数据类型 PFD\_TYPE\_RGBA 0x00 像素格式为 RGBA。 |
| [setIPixelType(byte value)](#setIPixelType-byte-) | 获取或设置像素数据类型 PFD\_TYPE\_RGBA 0x00 像素格式为 RGBA。 |
| [getCColorBits()](#getCColorBits--) | 获取或设置 RGBA 像素类型的每像素位数，不包括 alpha 位平面。 |
| [setCColorBits(byte value)](#setCColorBits-byte-) | 获取或设置 RGBA 像素类型的每像素位数，不包括 alpha 位平面。 |
| [getCRedBits()](#getCRedBits--) | 获取或设置每个 RGBA 颜色缓冲区中的红色位平面数。 |
| [setCRedBits(byte value)](#setCRedBits-byte-) | 获取或设置每个 RGBA 颜色缓冲区中的红色位平面数。 |
| [getCRedShift()](#getCRedShift--) | 获取或设置每个 RGBA 颜色缓冲区中红色位平面的位移计数（位）。 |
| [setCRedShift(byte value)](#setCRedShift-byte-) | 获取或设置每个 RGBA 颜色缓冲区中红色位平面的位移计数（位）。 |
| [getCGreenBits()](#getCGreenBits--) | 获取或设置每个 RGBA 颜色缓冲区中的绿色位平面数。 |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | 获取或设置每个 RGBA 颜色缓冲区中的绿色位平面数。 |
| [getCGreenShift()](#getCGreenShift--) | 获取或设置每个 RGBA 颜色缓冲区中绿色位平面的位移计数。 |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | 获取或设置每个 RGBA 颜色缓冲区中绿色位平面的位移计数。 |
| [getCBlueBits()](#getCBlueBits--) | 获取或设置每个 RGBA 颜色缓冲区中的蓝色位平面数。 |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | 获取或设置每个 RGBA 颜色缓冲区中的蓝色位平面数。 |
| [getCBlueShift()](#getCBlueShift--) | 获取或设置每个 RGBA 颜色缓冲区中蓝色位平面的位移计数。 |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | 获取或设置每个 RGBA 颜色缓冲区中蓝色位平面的位移计数。 |
| [getCAlphaBits()](#getCAlphaBits--) | 获取或设置每个 RGBA 颜色缓冲区中的 alpha 位平面数。 |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | 获取或设置每个 RGBA 颜色缓冲区中的 alpha 位平面数。 |
| [getCAlphaShift()](#getCAlphaShift--) | 获取或设置每个 RGBA 颜色缓冲区中 alpha 位平面的位移计数。 |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | 获取或设置每个 RGBA 颜色缓冲区中 alpha 位平面的位移计数。 |
| [getCAccumBits()](#getCAccumBits--) | 获取或设置指定累积缓冲区中的位平面总数。 |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | 获取或设置指定累积缓冲区中的位平面总数。 |
| [getCAccumRedBits()](#getCAccumRedBits--) | 获取或设置指定累积缓冲区中的红色位平面数量 |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | 获取或设置指定累积缓冲区中的红色位平面数量 |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | 获取或设置指定累积中的绿色位平面数量 |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | 获取或设置指定累积中的绿色位平面数量 |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | 获取或设置指定累积缓冲区中的蓝色位平面数量。 |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | 获取或设置指定累积缓冲区中的蓝色位平面数量。 |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | 获取或设置指定累积缓冲区中的 alpha 位平面数量 |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | 获取或设置指定累积缓冲区中的 alpha 位平面数量 |
| [getCDepthBits()](#getCDepthBits--) | 获取或设置指定深度（z 轴）缓冲区的深度。 |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | 获取或设置指定深度（z 轴）缓冲区的深度。 |
| [getCStencilBits()](#getCStencilBits--) | 获取或设置指定模板缓冲区的深度。 |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | 获取或设置指定模板缓冲区的深度。 |
| [getCAuxBuffers()](#getCAuxBuffers--) | 获取或设置指定辅助缓冲区的数量。 |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | 获取或设置指定辅助缓冲区的数量。 |
| [getILayerType()](#getILayerType--) | 获取或设置 此字段可能被忽略 |
| [setILayerType(byte value)](#setILayerType-byte-) | 获取或设置 此字段可能被忽略 |
| [getBReserved()](#getBReserved--) | 获取或设置指定覆盖层和底层平面的数量。 |
| [setBReserved(byte value)](#setBReserved-byte-) | 获取或设置指定覆盖层和底层平面的数量。 |
| [getDwLayerMask()](#getDwLayerMask--) | 获取或设置 此字段可能被忽略。 |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | 获取或设置 此字段可能被忽略。 |
| [getDwVisibleMask()](#getDwVisibleMask--) | 获取或设置指定底层平面的透明颜色或索引。 |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | 获取或设置指定底层平面的透明颜色或索引。 |
| [getDwDamageMask()](#getDwDamageMask--) | 获取或设置 此字段可能被忽略 |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | 获取或设置 此字段可能被忽略 |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


获取或设置一个 16 位整数，指定此数据结构的大小（字节）。

**Returns:**
短
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


获取或设置一个 16 位整数，指定此数据结构的大小（字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


获取或设置一个 16 位整数，必须设置为 0x0001。

**Returns:**
短
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


获取或设置一个 16 位整数，必须设置为 0x0001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


获取或设置位标志，这些标志指定用于输出到绘图表面的像素缓冲区的属性。这些属性并非全部互斥；允许组合标志，除非另有说明。

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


获取或设置位标志，这些标志指定用于输出到绘图表面的像素缓冲区的属性。这些属性并非全部互斥；允许组合标志，除非另有说明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


获取或设置像素数据的类型 PFD\_TYPE\_RGBA 0x00 像素格式为 RGBA。 PFD\_TYPE\_COLORINDEX 0x01 每个像素是颜色表中的索引。

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


获取或设置像素数据的类型 PFD\_TYPE\_RGBA 0x00 像素格式为 RGBA。 PFD\_TYPE\_COLORINDEX 0x01 每个像素是颜色表中的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


获取或设置 RGBA 像素类型的每像素位数，不包括 alpha 位平面。对于颜色表像素，它是每个颜色表索引的大小。

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


获取或设置 RGBA 像素类型的每像素位数，不包括 alpha 位平面。对于颜色表像素，它是每个颜色表索引的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


获取或设置每个 RGBA 颜色缓冲区中的红色位平面数。

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中的红色位平面数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


获取或设置每个 RGBA 颜色缓冲区中红色位平面的位移计数（位）。

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中红色位平面的位移计数（位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


获取或设置每个 RGBA 颜色缓冲区中的绿色位平面数。

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中的绿色位平面数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


获取或设置每个 RGBA 颜色缓冲区中绿色位平面的位移计数。

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中绿色位平面的位移计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


获取或设置每个 RGBA 颜色缓冲区中的蓝色位平面数。

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中的蓝色位平面数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


获取或设置每个 RGBA 颜色缓冲区中蓝色位平面的位移计数。

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中蓝色位平面的位移计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


获取或设置每个 RGBA 颜色缓冲区中的 alpha 位平面数。

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中的 alpha 位平面数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


获取或设置每个 RGBA 颜色缓冲区中 alpha 位平面的位移计数。

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


获取或设置每个 RGBA 颜色缓冲区中 alpha 位平面的位移计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


获取或设置指定累积缓冲区中的位平面总数。

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


获取或设置指定累积缓冲区中的位平面总数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


获取或设置指定累积缓冲区中的红色位平面数量

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


获取或设置指定累积缓冲区中的红色位平面数量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


获取或设置指定累积中的绿色位平面数量

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


获取或设置指定累积中的绿色位平面数量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


获取或设置指定累积缓冲区中的蓝色位平面数量。

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


获取或设置指定累积缓冲区中的蓝色位平面数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


获取或设置指定累积缓冲区中的 alpha 位平面数量

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


获取或设置指定累积缓冲区中的 alpha 位平面数量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


获取或设置指定深度（z 轴）缓冲区的深度。

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


获取或设置指定深度（z 轴）缓冲区的深度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


获取或设置指定模板缓冲区的深度。

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


获取或设置指定模板缓冲区的深度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


获取或设置指定辅助缓冲区的数量。辅助缓冲区不受支持

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


获取或设置指定辅助缓冲区的数量。辅助缓冲区不受支持

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


获取或设置 此字段可能被忽略

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


获取或设置 此字段可能被忽略

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


获取或设置指定覆盖层和底层平面的数量。位 0 到 3 指定最多 15 个覆盖平面，位 4 到 7 指定最多 15 个底层平面

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


获取或设置指定覆盖层和底层平面的数量。位 0 到 3 指定最多 15 个覆盖平面，位 4 到 7 指定最多 15 个底层平面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


获取或设置 此字段可能被忽略。

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


获取或设置 此字段可能被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


获取或设置指定底层平面的透明颜色或索引。当像素类型为 RGBA 时，dwVisibleMask 是透明的 RGB 颜色值。当像素类型为颜色索引时，它是透明的索引值。

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


获取或设置指定底层平面的透明颜色或索引。当像素类型为 RGBA 时，dwVisibleMask 是透明的 RGB 颜色值。当像素类型为颜色索引时，它是透明的索引值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


获取或设置 此字段可能被忽略

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


获取或设置 此字段可能被忽略

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

