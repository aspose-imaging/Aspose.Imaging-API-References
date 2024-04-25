---
title: CdrDocument
second_title: Aspose.Imaging for Java API Reference
description: The cdr root object
type: docs
weight: 17
url: /com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

The cdr root object
## Methods

| Method | Description |
| --- | --- |
| [getArrows()](#getArrows--) | Gets the arrows. |
| [getFills()](#getFills--) | Gets the fills. |
| [getOutLines()](#getOutLines--) | Gets the out lines. |
| [getBmps()](#getBmps--) | Gets the BMPS. |
| [getBmpMasks()](#getBmpMasks--) | Gets the BMP masks. |
| [getFonts()](#getFonts--) | Gets the fonts. |
| [getStyles()](#getStyles--) | Gets the styles. |
| [getTexts()](#getTexts--) | Gets the texts. |
| [getPatterns()](#getPatterns--) | Gets the patterns. |
| [getVectorPatterns()](#getVectorPatterns--) | Gets the vector patterns. |
| [getPowerClips()](#getPowerClips--) | Gets the power clips. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | The power clips. |
| [getClipIds()](#getClipIds--) | Gets the clip ids. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Sets the clip ids. |
| [getLastTextIndex()](#getLastTextIndex--) | Gets the text indexes. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | The text indexes. |
| [getVersion()](#getVersion--) | Gets the version. |
| [setVersion(int value)](#setVersion-int-) | Sets the version. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Gets the arrows.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - the arrows.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Gets the fills.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - the arrows.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Gets the out lines.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - the out lines.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Gets the BMPS.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - the BMPS.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Gets the BMP masks.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - the BMP masks.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Gets the fonts.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - the fonts.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Gets the styles.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - the styles.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Gets the texts.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Gets the patterns.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - the patterns.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Gets the vector patterns.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - the vector patterns.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Gets the power clips.

Value: The power clips.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - the power clips.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


The power clips.

Value: The power clips.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | the power clips. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Gets the clip ids.

Value: The clip ids.

**Returns:**
java.util.List<java.lang.Short> - the clip ids.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Sets the clip ids.

Value: The clip ids.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.Short> | the clip ids. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Gets the text indexes.

Value: The text indexes.

**Returns:**
int - the text indexes.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


The text indexes.

Value: The text indexes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the text indexes. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets the version.

**Returns:**
int - the version.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sets the version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the version. |

