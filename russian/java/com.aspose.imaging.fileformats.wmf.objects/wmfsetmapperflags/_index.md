---
title: "WmfSetMapperFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_SETMAPPERFLAGS определяет алгоритм, который использует сопоставитель шрифтов при преобразовании логических шрифтов в физические."
type: docs
weight: 78
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

Запись META\_SETMAPPERFLAGS определяет алгоритм, который использует сопоставитель шрифтов при преобразовании логических шрифтов в физические.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Получает или задает значения сопоставителя. |
| [setMapperValues(int value)](#setMapperValues-int-) | Получает или задает значения сопоставителя. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Получает или задает значения сопоставителя.

Значение: Сопоставитель шрифтов пытается согласовать соотношение сторон шрифта с текущим соотношением сторон устройства. Если установлен нулевой бит, сопоставитель выбирает только совпадающие шрифты.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Получает или задает значения сопоставителя.

Значение: Сопоставитель шрифтов пытается согласовать соотношение сторон шрифта с текущим соотношением сторон устройства. Если установлен нулевой бит, сопоставитель выбирает только совпадающие шрифты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

