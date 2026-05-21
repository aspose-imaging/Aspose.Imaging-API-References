---
title: "EmfHeaderObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект Header определяет заголовок метафайла EMF."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

Объект Header определяет заголовок EMF метафайла. Он указывает свойства устройства, на котором было создано изображение в метафайле.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Инициализирует новый экземпляр класса `EmfHeaderObject`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольные включительно-включительные границы в единицах устройства самого маленького прямоугольника, который может быть нарисован вокруг изображения, хранящегося в метафайле. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольные включительно-включительные границы в единицах устройства самого маленького прямоугольника, который может быть нарисован вокруг изображения, хранящегося в метафайле. |
| [getFrame()](#getFrame--) | Получает или задает объект WMF RectL, который определяет прямоугольные включительно-включительные размеры в единицах 0,01 миллиметра прямоугольника, окружающего изображение, хранящееся в метафайле. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL, который определяет прямоугольные включительно-включительные размеры в единицах 0,01 миллиметра прямоугольника, окружающего изображение, хранящееся в метафайле. |
| [getRecordSignature()](#getRecordSignature--) | Получает или задает 32-битное беззнаковое целое, которое определяет сигнатуру записи. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет сигнатуру записи. |
| [getVersion()](#getVersion--) | Получает или задает Версию (4 байта): 32-битное беззнаковое целое, которое определяет совместимость EMF метафайла. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает Версию (4 байта): 32-битное беззнаковое целое, которое определяет совместимость EMF метафайла. |
| [getBytes()](#getBytes--) | Получает или задает 32-битное беззнаковое целое, которое определяет размер метафайла в байтах. |
| [setBytes(int value)](#setBytes-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет размер метафайла в байтах. |
| [getRecords()](#getRecords--) | Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в метафайле. |
| [setRecords(int value)](#setRecords-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в метафайле. |
| [getHandles()](#getHandles--) | Получает или задает 16-битное беззнаковое целое, которое определяет количество графических объектов, которые будут использоваться при обработке метафайла. |
| [setHandles(short value)](#setHandles-short-) | Получает или задает 16-битное беззнаковое целое, которое определяет количество графических объектов, которые будут использоваться при обработке метафайла. |
| [getReserved()](#getReserved--) | Получает или задает 16-битное беззнаковое целое, которое ДОЛЖНО быть 0x0000 и ДОЛЖНО игнорироваться. |
| [setReserved(short value)](#setReserved-short-) | Получает или задает 16-битное беззнаковое целое, которое ДОЛЖНО быть 0x0000 и ДОЛЖНО игнорироваться. |
| [getNDesription()](#getNDesription--) | Получает или задает 32-битное беззнаковое целое, которое определяет количество символов в массиве, содержащем описание содержимого метафайла. |
| [setNDesription(int value)](#setNDesription-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет количество символов в массиве, содержащем описание содержимого метафайла. |
| [getOffDescription()](#getOffDescription--) | Получает или задает 32-битное беззнаковое целое, которое определяет смещение от начала этой записи до массива, содержащего описание содержимого метафайла. |
| [setOffDescription(int value)](#setOffDescription-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет смещение от начала этой записи до массива, содержащего описание содержимого метафайла. |
| [getNPalEntries()](#getNPalEntries--) | Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в палитре метафайла. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в палитре метафайла. |
| [getDevice()](#getDevice--) | Получает или задает объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который определяет размер эталонного устройства в пикселях. |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Получает или задает объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который определяет размер эталонного устройства в пикселях. |
| [getMillimeters()](#getMillimeters--) | Получает или задает объект WMF SizeL, который определяет размер эталонного устройства в миллиметрах. |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Получает или задает объект WMF SizeL, который определяет размер эталонного устройства в миллиметрах. |
| [getValid()](#getValid--) | Получает значение, указывающее, является ли этот `EmfHeaderObject` действительным. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Инициализирует новый экземпляр класса `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольные включительно-включительные границы в единицах устройства самого маленького прямоугольника, который может быть нарисован вокруг изображения, хранящегося в метафайле.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет прямоугольные включительно-включительные границы в единицах устройства самого маленького прямоугольника, который может быть нарисован вокруг изображения, хранящегося в метафайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Получает или задает объект WMF RectL, который определяет прямоугольные включительно-включительные размеры в единицах 0,01 миллиметра прямоугольника, окружающего изображение, хранящееся в метафайле.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Получает или задает объект WMF RectL, который определяет прямоугольные включительно-включительные размеры в единицах 0,01 миллиметра прямоугольника, окружающего изображение, хранящееся в метафайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Получает или задает 32-битное беззнаковое целое, которое определяет сигнатуру записи. Это ДОЛЖНО быть ENHMETA\\_SIGNATURE из перечисления FormatSignature (раздел 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет сигнатуру записи. Это ДОЛЖНО быть ENHMETA\\_SIGNATURE из перечисления FormatSignature (раздел 2.1.14).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает Версию (4 байта): 32-битное беззнаковое целое, которое определяет совместимость EMF метафайла. Это ДОЛЖНО быть 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает Версию (4 байта): 32-битное беззнаковое целое, которое определяет совместимость EMF метафайла. Это ДОЛЖНО быть 0x00010000.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Получает или задает 32-битное беззнаковое целое, которое определяет размер метафайла в байтах.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет размер метафайла в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в метафайле.

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в метафайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Получает или задает 16-битное беззнаковое целое, которое определяет количество графических объектов, которые будут использоваться при обработке метафайла.

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Получает или задает 16-битное беззнаковое целое, которое определяет количество графических объектов, которые будут использоваться при обработке метафайла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Получает или задает 16-битное беззнаковое целое, которое ДОЛЖНО быть 0x0000 и ДОЛЖНО игнорироваться.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Получает или задает 16-битное беззнаковое целое, которое ДОЛЖНО быть 0x0000 и ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество символов в массиве, содержащем описание содержимого метафайла. Это ноль, если строка описания отсутствует.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество символов в массиве, содержащем описание содержимого метафайла. Это ноль, если строка описания отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Получает или задает 32-битное беззнаковое целое, которое определяет смещение от начала этой записи до массива, содержащего описание содержимого метафайла.

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет смещение от начала этой записи до массива, содержащего описание содержимого метафайла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в палитре метафайла. Палитра находится в записи EMR\\_EOF.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет количество записей в палитре метафайла. Палитра находится в записи EMR\\_EOF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Получает или задает объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который определяет размер эталонного устройства в пикселях.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Получает или задает объект WMF SizeL ([MS-WMF] раздел 2.2.2.22), который определяет размер эталонного устройства в пикселях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Получает или задает объект WMF SizeL, который определяет размер эталонного устройства в миллиметрах.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Получает или задает объект WMF SizeL, который определяет размер эталонного устройства в миллиметрах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Получает значение, указывающее, является ли этот `EmfHeaderObject` действительным.

Значение: `true`, если действителен; иначе `false`.

**Returns:**
boolean
