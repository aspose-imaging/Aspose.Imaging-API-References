---
title: "EmfExtTextOutW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTTEXTOUTW выводит строку ASCII-текста, используя текущий шрифт и цвета текста."
type: docs
weight: 57
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

Запись EMR\_EXTTEXTOUTW рисует строку ASCII‑текста, используя текущий шрифт и цвета текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtTextOutW`. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | Инициализирует новый экземпляр класса `EmfExtTextOutW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Получает или задает 32-битное беззнаковое целое число, которое указывает режим графики из перечисления GraphicsMode (раздел 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Получает или задает 32-битное беззнаковое целое число, которое указывает режим графики из перечисления GraphicsMode (раздел 2.1.16). |
| [getExScale()](#getExScale--) | Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси X для преобразования единиц пространства страницы в единицы .01 мм. |
| [setExScale(float value)](#setExScale-float-) | Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси X для преобразования единиц пространства страницы в единицы .01 мм. |
| [getEyScale()](#getEyScale--) | Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси Y для преобразования единиц пространства страницы в единицы .01 мм. |
| [setEyScale(float value)](#setEyScale-float-) | Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси Y для преобразования единиц пространства страницы в единицы .01 мм. |
| [getWEmrText()](#getWEmrText--) | Получает или задает объект EmrText (раздел 2.2.5), который указывает строку вывода в 16-битных символах Unicode UTF16-LE, с атрибутами текста и значениями интервалов. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Получает или задает объект EmrText (раздел 2.2.5), который указывает строку вывода в 16-битных символах Unicode UTF16-LE, с атрибутами текста и значениями интервалов. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExtTextOutW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


Инициализирует новый экземпляр класса `EmfExtTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19). Он не используется и ДОЛЖЕН быть проигнорирован при получении.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19). Он не используется и ДОЛЖЕН быть проигнорирован при получении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Получает или задает 32-битное беззнаковое целое число, которое указывает режим графики из перечисления GraphicsMode (раздел 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое указывает режим графики из перечисления GraphicsMode (раздел 2.1.16).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси X для преобразования единиц пространства страницы в единицы .01 мм. Это ДОЛЖНО использоваться только если режим графики, указанный в iGraphicsMode, равен GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси X для преобразования единиц пространства страницы в единицы .01 мм. Это ДОЛЖНО использоваться только если режим графики, указанный в iGraphicsMode, равен GM\_COMPATIBLE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси Y для преобразования единиц пространства страницы в единицы .01 мм. Это ДОЛЖНО использоваться только если режим графики, указанный в iGraphicsMode, равен GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое определяет коэффициент масштабирования по оси Y для преобразования единиц пространства страницы в единицы .01 мм. Это ДОЛЖНО использоваться только если режим графики, указанный в iGraphicsMode, равен GM\_COMPATIBLE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


Получает или задает объект EmrText (раздел 2.2.5), который указывает строку вывода в 16-битных символах Unicode UTF16-LE, с атрибутами текста и значениями интервалов.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


Получает или задает объект EmrText (раздел 2.2.5), который указывает строку вывода в 16-битных символах Unicode UTF16-LE, с атрибутами текста и значениями интервалов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

