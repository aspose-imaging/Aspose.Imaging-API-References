---
title: "WmfSetTextCharExtra"
second_title: "Aspose.Imaging for Java API 参考"
description: "META_SETTEXTCHAREXTRA 记录定义了在回放设备上下文中进行文本对齐的字符间距。"
type: docs
weight: 86
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

META\_SETTEXTCHAREXTRA 记录定义了在回放设备上下文中进行文本对齐的字符间距。当输出对齐文本行时，间距会添加到每个字符之间的空白，包括 `` 字符。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | 获取或设置字符额外间距。 |
| [setCharExtra(int value)](#setCharExtra-int-) | 获取或设置字符额外间距。 |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


获取或设置字符额外间距。

值：以逻辑单位表示的每个字符要添加的额外空间量。如果当前映射模式不是 MM\_TEXT，则此值会被转换并四舍五入到最近的像素。有关设置映射模式的详细信息，请参阅 META\_SETMAPMODE（章节 2.3.5.17）。

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


获取或设置字符额外间距。

值：以逻辑单位表示的每个字符要添加的额外空间量。如果当前映射模式不是 MM\_TEXT，则此值会被转换并四舍五入到最近的像素。有关设置映射模式的详细信息，请参阅 META\_SETMAPMODE（章节 2.3.5.17）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

