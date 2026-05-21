---
title: "WmfSetLayout"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_SETLAYOUT определяет ориентацию макета в контексте устройства воспроизведения."
type: docs
weight: 76
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetlayout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetLayout extends WmfObject
```

Запись META\_SETLAYOUT определяет ориентацию макета в контексте устройства воспроизведения. Ориентация макета определяет направление, в котором рисуются текст и графика.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfSetLayout()](#WmfSetLayout--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getLayoutMode()](#getLayoutMode--) | Получает или задает LayoutMode. |
| [setLayoutMode(int value)](#setLayoutMode-int-) | Получает или задает LayoutMode. |
### WmfSetLayout() {#WmfSetLayout--}
```
public WmfSetLayout()
```


### getLayoutMode() {#getLayoutMode--}
```
public int getLayoutMode()
```


Получает или задает LayoutMode.

Значение: Макет текста и графики. Это ДОЛЖНО быть одним из значений в перечислении Layout (раздел 2.1.1.13).

**Returns:**
int
### setLayoutMode(int value) {#setLayoutMode-int-}
```
public void setLayoutMode(int value)
```


Получает или задает LayoutMode.

Значение: Макет текста и графики. Это ДОЛЖНО быть одним из значений в перечислении Layout (раздел 2.1.1.13).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

