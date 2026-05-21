---
title: "WmfDibCreatePatternBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_DIBCREATEPATTERNBRUSH создает раздел Brush Object 2.2.1.1 с шаблоном, указанным объектом DeviceIndependentBitmap DIB раздела 2.2.2.9."
type: docs
weight: 29
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

Запись META\_DIBCREATEPATTERNBRUSH создает объект Brush (раздел 2.2.1.1) с узором, заданным объектом DeviceIndependentBitmap (DIB) (раздел 2.2.2.9).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getStyle()](#getStyle--) | Получает или задает стиль. |
| [setStyle(int value)](#setStyle-int-) | Получает или задает стиль. |
| [getColorUsage()](#getColorUsage--) | Получает или задает использование цвета. |
| [setColorUsage(int value)](#setColorUsage-int-) | Получает или задает использование цвета. |
| [getSourceBitmap()](#getSourceBitmap--) | Получает или задает исходный битмап. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает исходный битмап. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Получает или задает стиль.

Значение: Допустимые значения для этого поля определены следующим образом: если значение не BS\_PATTERN, необходимо предположить BS\_DIBPATTERNPT. Эти значения указаны в перечислении BrushStyle (раздел 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Получает или задает стиль.

Значение: Допустимые значения для этого поля определены следующим образом: если значение не BS\_PATTERN, необходимо предположить BS\_DIBPATTERNPT. Эти значения указаны в перечислении BrushStyle (раздел 2.1.1.4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Получает или задает использование цвета.

Значение: Поле Colors объекта DIB содержит явные значения RGB или индексы в палитру.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Получает или задает использование цвета.

Значение: Поле Colors объекта DIB содержит явные значения RGB или индексы в палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Получает или задает исходный битмап.

Значение: Данные объекта DIB переменной разрядности, определяющие шаблон, используемый в кисти.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Получает или задает исходный битмап.

Значение: Данные объекта DIB переменной разрядности, определяющие шаблон, используемый в кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

