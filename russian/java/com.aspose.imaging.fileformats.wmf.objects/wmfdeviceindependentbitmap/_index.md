---
title: "WmfDeviceIndependentBitmap"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект DeviceIndependentBitmap определяет изображение в формате независимого от устройства bitmap (DIB)."
type: docs
weight: 27
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

Объект DeviceIndependentBitmap определяет изображение в формате независимого от устройства растрового изображения (DIB).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeader()](#getHeader--) | Получает или задает объект BitmapCoreHeader (раздел 2.2.2.2) либо объект BitmapInfoHeader (раздел 2.2.2.3), который содержит информацию об изображении. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Получает или задает объект BitmapCoreHeader (раздел 2.2.2.2) либо объект BitmapInfoHeader (раздел 2.2.2.3), который содержит информацию об изображении. |
| [getColorsData()](#getColorsData--) | Получает или задает необязательный массив из объектов RGBQuad (раздел 2.2.2.20) либо 16‑битных беззнаковых целых, определяющих таблицу цветов. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Получает или задает необязательный массив из объектов RGBQuad (раздел 2.2.2.20) либо 16‑битных беззнаковых целых, определяющих таблицу цветов. |
| [getAData()](#getAData--) | Получает или задает массив байтов, определяющих изображение. |
| [setAData(byte[] value)](#setAData-byte---) | Получает или задает массив байтов, определяющих изображение. |
| [getCachedImage()](#getCachedImage--) | Получает кэшированное растровое изображение. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Задаёт кэшированное растровое изображение. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Получает или задает объект BitmapCoreHeader (раздел 2.2.2.2) либо объект BitmapInfoHeader (раздел 2.2.2.3), который содержит информацию об изображении.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Получает или задает объект BitmapCoreHeader (раздел 2.2.2.2) либо объект BitmapInfoHeader (раздел 2.2.2.3), который содержит информацию об изображении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Получает или задает необязательный массив из объектов RGBQuad (раздел 2.2.2.20) либо 16‑битных беззнаковых целых, определяющих таблицу цветов. Размер и содержимое этого поля ДОЛЖНЫ определяться из записи метафайла или объекта, содержащего этот DeviceIndependentBitmap, а также из информации в поле DIBHeaderInfo. См. перечисление ColorUsage (раздел 2.1.1.6) и перечисление BitCount (раздел 2.1.1.3) для получения дополнительных сведений.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Получает или задает необязательный массив из объектов RGBQuad (раздел 2.2.2.20) либо 16‑битных беззнаковых целых, определяющих таблицу цветов. Размер и содержимое этого поля ДОЛЖНЫ определяться из записи метафайла или объекта, содержащего этот DeviceIndependentBitmap, а также из информации в поле DIBHeaderInfo. См. перечисление ColorUsage (раздел 2.1.1.6) и перечисление BitCount (раздел 2.1.1.3) для получения дополнительных сведений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Получает или задает массив байтов, определяющих изображение. Размер и формат этих данных определяются информацией в поле DIBHeaderInfo.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Получает или задает массив байтов, определяющих изображение. Размер и формат этих данных определяются информацией в поле DIBHeaderInfo.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Получает кэшированное растровое изображение.

Значение: Кэшированное изображение.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Задаёт кэшированное растровое изображение.

Значение: Кэшированное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

