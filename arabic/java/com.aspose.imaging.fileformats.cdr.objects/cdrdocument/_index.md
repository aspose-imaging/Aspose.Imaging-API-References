---
title: "CdrDocument"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن الجذر cdr"
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

كائن الجذر cdr
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArrows()](#getArrows--) | يحصل على الأسهم. |
| [getFills()](#getFills--) | يحصل على التعبئات. |
| [getOutLines()](#getOutLines--) | يحصل على الخطوط الخارجية. |
| [getBmps()](#getBmps--) | يحصل على ملفات BMP. |
| [getBmpMasks()](#getBmpMasks--) | يحصل على أقنعة BMP. |
| [getFonts()](#getFonts--) | يحصل على الخطوط. |
| [getStyles()](#getStyles--) | يحصل على الأنماط. |
| [getTexts()](#getTexts--) | يحصل على النصوص. |
| [getPatterns()](#getPatterns--) | يحصل على القوالب. |
| [getVectorPatterns()](#getVectorPatterns--) | يحصل على أنماط المتجهات. |
| [getPowerClips()](#getPowerClips--) | يحصل على مقاطع الطاقة. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | مقاطع الطاقة. |
| [getClipIds()](#getClipIds--) | يحصل على معرفات المقاطع. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | يضبط معرفات المقاطع. |
| [getLastTextIndex()](#getLastTextIndex--) | يحصل على فهارس النص. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | فهارس النص. |
| [getVersion()](#getVersion--) | يحصل على الإصدار. |
| [setVersion(int value)](#setVersion-int-) | يضبط الإصدار. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


يحصل على الأسهم.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - الأسهم.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


يحصل على التعبئات.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - الأسهم.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


يحصل على الخطوط الخارجية.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - الخطوط الخارجية.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


يحصل على ملفات BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - ملفات BMP.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


يحصل على أقنعة BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - أقنعة BMP.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


يحصل على الخطوط.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - الخطوط.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


يحصل على الأنماط.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - الأنماط.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


يحصل على النصوص.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


يحصل على القوالب.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - الأنماط.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


يحصل على أنماط المتجهات.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - الأنماط المتجهة.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


يحصل على مقاطع الطاقة.

القيمة: مقاطع الطاقة.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - مقاطع الطاقة.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


مقاطع الطاقة.

القيمة: مقاطع الطاقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | مقاطع الطاقة. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


يحصل على معرفات المقاطع.

القيمة: معرفات القص.

**Returns:**
java.util.List<java.lang.Short> - معرفات القص.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


يضبط معرفات المقاطع.

القيمة: معرفات القص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.List<java.lang.Short> | معرفات القص. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


يحصل على فهارس النص.

القيمة: فهارس النص.

**Returns:**
int - فهارس النص.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


فهارس النص.

القيمة: فهارس النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | فهارس النص. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على الإصدار.

**Returns:**
int - الإصدار.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


يضبط الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الإصدار. |

