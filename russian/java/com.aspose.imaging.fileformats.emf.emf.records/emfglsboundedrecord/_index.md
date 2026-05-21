---
title: "EmfGlsBoundedRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_GLSBOUNDEDRECORD задает функцию OpenGL с ограничивающим прямоугольником для вывода."
type: docs
weight: 63
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

Запись EMR\_GLSBOUNDEDRECORD определяет функцию OpenGL с ограничивающим прямоугольником для вывода.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfGlsBoundedRecord`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода, получаемого при выполнении функции OpenGL. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода, получаемого при выполнении функции OpenGL. |
| [getCbData()](#getCbData--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [setCbData(int value)](#setCbData-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [getData()](#getData--) | Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfGlsBoundedRecord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода, получаемого при выполнении функции OpenGL.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства для вывода, получаемого при выполнении функции OpenGL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. Если это значение равно нулю, к этой записи не прикрепляются данные.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. Если это значение равно нулю, к этой записи не прикрепляются данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

