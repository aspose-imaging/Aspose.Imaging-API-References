---
title: "CdrDocument"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "cdr 根对象"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

cdr 根对象
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArrows()](#getArrows--) | 获取箭头。 |
| [getFills()](#getFills--) | 获取填充。 |
| [getOutLines()](#getOutLines--) | 获取轮廓线。 |
| [getBmps()](#getBmps--) | 获取 BMP。 |
| [getBmpMasks()](#getBmpMasks--) | 获取 BMP 掩码。 |
| [getFonts()](#getFonts--) | 获取字体。 |
| [getStyles()](#getStyles--) | 获取样式。 |
| [getTexts()](#getTexts--) | 获取文本。 |
| [getPatterns()](#getPatterns--) | 获取图案。 |
| [getVectorPatterns()](#getVectorPatterns--) | 获取矢量图案。 |
| [getPowerClips()](#getPowerClips--) | 获取电源剪辑。 |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | 电源剪辑。 |
| [getClipIds()](#getClipIds--) | 获取剪辑 ID。 |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | 设置剪辑 ID。 |
| [getLastTextIndex()](#getLastTextIndex--) | 获取文本索引。 |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | 文本索引。 |
| [getVersion()](#getVersion--) | 获取版本。 |
| [setVersion(int value)](#setVersion-int-) | 设置版本。 |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


获取箭头。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - 箭头。
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


获取填充。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - 箭头。
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


获取轮廓线。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - 轮廓线。
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


获取 BMP。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP。
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


获取 BMP 掩码。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP 掩码。
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


获取字体。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - 字体。
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


获取样式。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - 样式。
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


获取文本。

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


获取图案。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - 模式。
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


获取矢量图案。

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - 向量模式。
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


获取电源剪辑。

Value: 电源剪辑。

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - 电源剪辑。
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


电源剪辑。

Value: 电源剪辑。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | 电源剪辑。 |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


获取剪辑 ID。

Value: 剪辑 ID。

**Returns:**
java.util.List<java.lang.Short> - 剪辑 ID。
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


设置剪辑 ID。

Value: 剪辑 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.List<java.lang.Short> | 剪辑 ID。 |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


获取文本索引。

Value: 文本索引。

**Returns:**
int - 文本索引。
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


文本索引。

Value: 文本索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 文本索引。 |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取版本。

**Returns:**
int - 版本。
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


设置版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 版本。 |

