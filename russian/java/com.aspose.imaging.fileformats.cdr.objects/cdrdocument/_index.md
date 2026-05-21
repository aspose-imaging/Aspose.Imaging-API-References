---
title: "CdrDocument"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Корневой объект cdr"
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging/fileformats/cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

Корневой объект cdr
## Методы

| Метод | Описание |
| --- | --- |
| [getArrows()](#getArrows--) | Получает стрелки. |
| [getFills()](#getFills--) | Получает заливки. |
| [getOutLines()](#getOutLines--) | Получает контуры. |
| [getBmps()](#getBmps--) | Получает BMP-файлы. |
| [getBmpMasks()](#getBmpMasks--) | Получает BMP-маски. |
| [getFonts()](#getFonts--) | Получает шрифты. |
| [getStyles()](#getStyles--) | Получает стили. |
| [getTexts()](#getTexts--) | Получает тексты. |
| [getPatterns()](#getPatterns--) | Получает шаблоны. |
| [getVectorPatterns()](#getVectorPatterns--) | Получает векторные шаблоны. |
| [getPowerClips()](#getPowerClips--) | Получает power clips. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Эти power clips. |
| [getClipIds()](#getClipIds--) | Получает идентификаторы клипов. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Устанавливает идентификаторы клипов. |
| [getLastTextIndex()](#getLastTextIndex--) | Получает индексы текста. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Эти индексы текста. |
| [getVersion()](#getVersion--) | Получает версию. |
| [setVersion(int value)](#setVersion-int-) | Устанавливает версию. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Получает стрелки.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - стрелки.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Получает заливки.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - стрелки.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Получает контуры.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - контуры.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Получает BMP-файлы.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP-файлы.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Получает BMP-маски.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP-маски.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Получает шрифты.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - шрифты.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Получает стили.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - стили.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Получает тексты.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Получает шаблоны.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - шаблоны.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Получает векторные шаблоны.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - векторные шаблоны.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Получает power clips.

Значение: Силовые клипы.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - силовые клипы.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Эти power clips.

Значение: Силовые клипы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | силовые клипы. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Получает идентификаторы клипов.

Значение: Идентификаторы клипов.

**Returns:**
java.util.List<java.lang.Short> - идентификаторы клипов.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Устанавливает идентификаторы клипов.

Значение: Идентификаторы клипов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.List<java.lang.Short> | идентификаторы клипов. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Получает индексы текста.

Значение: Индексы текста.

**Returns:**
int - индексы текста.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Эти индексы текста.

Значение: Индексы текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | индексы текста. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает версию.

**Returns:**
int - версия.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Устанавливает версию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | версия. |

