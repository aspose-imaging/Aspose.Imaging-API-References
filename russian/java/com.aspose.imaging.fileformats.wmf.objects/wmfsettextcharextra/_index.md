---
title: "WmfSetTextCharExtra"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_SETTEXTCHAREXTRA определяет межсимвольный интервал для выравнивания текста в контексте устройства воспроизведения."
type: docs
weight: 86
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

Запись META\_SETTEXTCHAREXTRA определяет межсимвольный интервал для выравнивания текста в контексте устройства воспроизведения. Интервал добавляется к пробелу между каждым символом, включая `` символы, когда выводится строка выровненного текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Получает или задает дополнительный интервал символа. |
| [setCharExtra(int value)](#setCharExtra-int-) | Получает или задает дополнительный интервал символа. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Получает или задает дополнительный интервал символа.

Значение: количество дополнительного пространства в логических единицах, которое добавляется к каждому символу. Если текущий режим отображения не MM\_TEXT, это значение преобразуется и округляется до ближайшего пикселя. Подробности о настройке режима отображения см. META\_SETMAPMODE (раздел 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Получает или задает дополнительный интервал символа.

Значение: количество дополнительного пространства в логических единицах, которое добавляется к каждому символу. Если текущий режим отображения не MM\_TEXT, это значение преобразуется и округляется до ближайшего пикселя. Подробности о настройке режима отображения см. META\_SETMAPMODE (раздел 2.3.5.17).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

