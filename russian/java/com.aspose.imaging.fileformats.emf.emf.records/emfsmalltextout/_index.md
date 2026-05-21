---
title: "EmfSmallTextOut"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SMALLTEXTOUT выводит строку."
type: docs
weight: 147
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

Запись EMR\_SMALLTEXTOUT выводит строку.

Если в поле fuOptions установлен флаг ETO\_SMALL\_CHARS, то TextString содержит 8‑битные коды символов, полученные из младших байтов 16‑битных кодов Unicode UTF16-LE, при этом старший байт считается равным 0. Если в поле fuOptions установлен флаг ETO\_NO\_RECT, поле Bounds не включается в запись.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSmallTextOut`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Получает или задает 32‑битное знаковое целое, указывающее координату x места размещения строки. |
| [setX(int value)](#setX-int-) | Получает или задает 32‑битное знаковое целое, указывающее координату x места размещения строки. |
| [getY()](#getY--) | Получает или задает 32‑битное знаковое целое, указывающее координату y места размещения строки. |
| [setY(int value)](#setY-int-) | Получает или задает 32‑битное знаковое целое, указывающее координату y места размещения строки. |
| [getCChars()](#getCChars--) | Получает или задает 32‑битное беззнаковое целое, определяющее количество 16‑битных символов в строке. |
| [setCChars(int value)](#setCChars-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее количество 16‑битных символов в строке. |
| [getFuOptions()](#getFuOptions--) | Получает или задает 32‑битное беззнаковое целое, определяющее параметры вывода текста, которые следует использовать. |
| [setFuOptions(int value)](#setFuOptions-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее параметры вывода текста, которые следует использовать. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Получает или задает 32‑битное беззнаковое целое, определяющее режим графики, из перечисления GraphicsMode (раздел 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее режим графики, из перечисления GraphicsMode (раздел 2.1.16). |
| [getExScale()](#getExScale--) | Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси x. |
| [setExScale(float value)](#setExScale-float-) | Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси x. |
| [getEyScale()](#getEyScale--) | Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси y. |
| [setEyScale(float value)](#setEyScale-float-) | Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси y. |
| [getBounds()](#getBounds--) | Получает или задает необязательный 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает необязательный 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства. |
| [getTextString()](#getTextString--) | Получает или задает строку переменной длины, содержащую текст для отрисовки, в виде 8‑битных или 16‑битных кодов символов, в зависимости от значения поля fuOptions. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Получает или задает строку переменной длины, содержащую текст для отрисовки, в виде 8‑битных или 16‑битных кодов символов, в зависимости от значения поля fuOptions. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSmallTextOut`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getX() {#getX--}
```
public int getX()
```


Получает или задает 32‑битное знаковое целое, указывающее координату x места размещения строки.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Получает или задает 32‑битное знаковое целое, указывающее координату x места размещения строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


Получает или задает 32‑битное знаковое целое, указывающее координату y места размещения строки.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Получает или задает 32‑битное знаковое целое, указывающее координату y места размещения строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Получает или задает 32‑битное беззнаковое целое, определяющее количество 16‑битных символов в строке. Строка НЕ завершается нулевым символом.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее количество 16‑битных символов в строке. Строка НЕ завершается нулевым символом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Получает или задает 32‑битное беззнаковое целое, определяющее параметры вывода текста, которые следует использовать. Эти параметры задаются одним или комбинацией значений из перечисления ExtTextOutOptions (раздел 2.1.11).

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее параметры вывода текста, которые следует использовать. Эти параметры задаются одним или комбинацией значений из перечисления ExtTextOutOptions (раздел 2.1.11).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Получает или задает 32‑битное беззнаковое целое, определяющее режим графики, из перечисления GraphicsMode (раздел 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее режим графики, из перечисления GraphicsMode (раздел 2.1.16).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси x.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси y.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее степень масштабирования текста по оси y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает необязательный 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает необязательный 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), определяющий ограничивающий прямоугольник в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Получает или задает строку переменной длины, содержащую текст для отрисовки, в виде 8‑битных или 16‑битных кодов символов, в зависимости от значения поля fuOptions.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Получает или задает строку переменной длины, содержащую текст для отрисовки, в виде 8‑битных или 16‑битных кодов символов, в зависимости от значения поля fuOptions.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

