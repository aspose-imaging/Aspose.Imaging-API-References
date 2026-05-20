---
title: "Configuration"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "内存管理全局配置"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

内存管理全局配置
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | 获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


获取缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示（单位：兆字节）。非正值表示内部缓冲区没有内存限制

**Returns:**
int - 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

值：缓冲区大小提示（单位：兆字节）。非正值表示内部缓冲区没有内存限制

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 缓冲区大小提示，定义为所有内部缓冲区的最大允许大小。 |

