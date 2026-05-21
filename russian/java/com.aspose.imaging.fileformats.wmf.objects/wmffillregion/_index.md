---
title: "WmfFillRegion"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_FILLREGION заполняет область, используя указанную кисть."
type: docs
weight: 37
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

Запись META\_FILLREGION заполняет регион, используя указанную кисть.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Инициализирует новый экземпляр класса `WmfFillRegion`. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Инициализирует новый экземпляр класса `WmfFillRegion`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Получает или задаёт индекс области. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Получает или задаёт индекс области. |
| [getBrushIndex()](#getBrushIndex--) | Получает или задаёт индекс кисти. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Получает или задаёт индекс кисти. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Инициализирует новый экземпляр класса `WmfFillRegion`.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Инициализирует новый экземпляр класса `WmfFillRegion`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Область. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Кисть. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Получает или задаёт индекс области.

Значение: Индекс в таблице объектов WMF для получения области, которую нужно заполнить.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Получает или задаёт индекс области.

Значение: Индекс в таблице объектов WMF для получения области, которую нужно заполнить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Получает или задаёт индекс кисти.

Значение: Индекс в таблице объектов WMF для получения кисти, используемой для заполнения области.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Получает или задаёт индекс кисти.

Значение: Индекс в таблице объектов WMF для получения кисти, используемой для заполнения области.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

