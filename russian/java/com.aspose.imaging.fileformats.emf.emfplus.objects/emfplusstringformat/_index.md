---
title: "EmfPlusStringFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusStringFormat определяет манипуляции отображения макета текста и идентификацию языка."
type: docs
weight: 74
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

Объект EmfPlusStringFormat указывает расположение текста, манипуляции отображением и идентификацию языка.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Получает или задает объект EmfPlusLanguageIdentifier, который указывает язык, используемый для числовых цифр в строке. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Получает или задает объект EmfPlusLanguageIdentifier, который указывает язык, используемый для числовых цифр в строке. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Получает или задает 32-битное беззнаковое целое, которое определяет способ замены числовых цифр в строке в соответствии с локалью или языком. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет способ замены числовых цифр в строке в соответствии с локалью или языком. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Получает или задает 32-битное значение с плавающей запятой, которое указывает количество пробелов между началом строки текста и первой табуляцией. |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Получает или задает 32-битное значение с плавающей запятой, которое указывает количество пробелов между началом строки текста и первой табуляцией. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Получает или задает 32-битное знаковое целое, которое определяет тип обработки строки, когда встречается префикс клавиатурного сокращения (то есть амперсанд). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Получает или задает 32-битное знаковое целое, которое определяет тип обработки строки, когда встречается префикс клавиатурного сокращения (то есть амперсанд). |
| [getLanguage()](#getLanguage--) | Получает или задает объект EmfPlusLanguageIdentifier (раздел 2.2.2.23), который указывает язык, используемый для строки. |
| [setLanguage(short value)](#setLanguage-short-) | Получает или задает объект EmfPlusLanguageIdentifier (раздел 2.2.2.23), который указывает язык, используемый для строки. |
| [getLeadingMargin()](#getLeadingMargin--) | Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, добавляемого к начальной позиции строки. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, добавляемого к начальной позиции строки. |
| [getLineAlign()](#getLineAlign--) | Получает или задает 32-битное беззнаковое целое, которое определяет вертикальное выравнивание строки в прямоугольнике макета. |
| [setLineAlign(int value)](#setLineAlign-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет вертикальное выравнивание строки в прямоугольнике макета. |
| [getRangeCount()](#getRangeCount--) | Получает или задает 32-битное знаковое целое, которое указывает количество объектов EmfPlusCharacterRange (раздел 2.2.2.8), определённых в поле StringFormatData. |
| [setRangeCount(int value)](#setRangeCount-int-) | Получает или задает 32-битное знаковое целое, которое указывает количество объектов EmfPlusCharacterRange (раздел 2.2.2.8), определённых в поле StringFormatData. |
| [getStringAlignment()](#getStringAlignment--) | Получает или задает 32-битное беззнаковое целое, которое определяет горизонтальное выравнивание строки в прямоугольнике макета. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет горизонтальное выравнивание строки в прямоугольнике макета. |
| [getStringFormatData()](#getStringFormatData--) | Получает или задает объект EmfPlusStringFormatData (раздел 2.2.2.44), который определяет дополнительные данные макета текста. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Получает или задает объект EmfPlusStringFormatData (раздел 2.2.2.44), который определяет дополнительные данные макета текста. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Получает или задает 32-битное беззнаковое целое, которое указывает параметры макета текста для форматирования, обрезки и обработки шрифтов. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Получает или задает 32-битное беззнаковое целое, которое указывает параметры макета текста для форматирования, обрезки и обработки шрифтов. |
| [getTabstopCount()](#getTabstopCount--) | Получает или задает 32-битное знаковое целое, которое указывает количество табуляций, определённых в поле StringFormatData. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Получает или задает 32-битное знаковое целое, которое указывает количество табуляций, определённых в поле StringFormatData. |
| [getTracking()](#getTracking--) | Получает или задает 32-битное значение с плавающей запятой, которое определяет отношение горизонтального пространства, выделенного каждому символу в указанной строке, к ширине символа, заданной шрифтом. |
| [setTracking(float value)](#setTracking-float-) | Получает или задает 32-битное значение с плавающей запятой, которое определяет отношение горизонтального пространства, выделенного каждому символу в указанной строке, к ширине символа, заданной шрифтом. |
| [getTrailingMargin()](#getTrailingMargin--) | Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, оставляемого после строки. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, оставляемого после строки. |
| [getTrimming()](#getTrimming--) | Получает или задает способ обрезки символов из строки, которая слишком велика, чтобы поместиться в прямоугольник макета. |
| [setTrimming(int value)](#setTrimming-int-) | Получает или задает способ обрезки символов из строки, которая слишком велика, чтобы поместиться в прямоугольник макета. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Получает или задает объект EmfPlusLanguageIdentifier, который указывает язык, используемый для числовых цифр в строке. Например, если строка содержит арабские цифры, это поле ДОЛЖНО содержать идентификатор языка, указывающий на арабский язык.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Получает или задает объект EmfPlusLanguageIdentifier, который указывает язык, используемый для числовых цифр в строке. Например, если строка содержит арабские цифры, это поле ДОЛЖНО содержать идентификатор языка, указывающий на арабский язык.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Получает или задает 32-битное беззнаковое целое, которое определяет способ замены числовых цифр в строке в соответствии с локалью или языком. Это значение ДОЛЖНО быть определено в перечислении StringDigitSubstitution (раздел 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет способ замены числовых цифр в строке в соответствии с локалью или языком. Это значение ДОЛЖНО быть определено в перечислении StringDigitSubstitution (раздел 2.1.1.30).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Получает или задает 32-битное значение с плавающей запятой, которое указывает количество пробелов между началом строки текста и первой табуляцией.

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Получает или задает 32-битное значение с плавающей запятой, которое указывает количество пробелов между началом строки текста и первой табуляцией.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Получает или задает 32-битное знаковое целое, которое определяет тип обработки строки, когда встречается префикс клавиатурного сокращения (то есть амперсанд). По сути, это поле указывает, отображать ли префиксы клавиатурных сокращений, относящиеся к тексту. Значение ДОЛЖНО быть определено в перечислении HotkeyPrefix (раздел 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет тип обработки строки, когда встречается префикс клавиатурного сокращения (то есть амперсанд). По сути, это поле указывает, отображать ли префиксы клавиатурных сокращений, относящиеся к тексту. Значение ДОЛЖНО быть определено в перечислении HotkeyPrefix (раздел 2.1.1.14).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Получает или задает объект EmfPlusLanguageIdentifier (раздел 2.2.2.23), который указывает язык, используемый для строки.

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Получает или задает объект EmfPlusLanguageIdentifier (раздел 2.2.2.23), который указывает язык, используемый для строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, добавляемого к начальной позиции строки. По умолчанию это 1/6 дюйма; для типографических шрифтов значение по умолчанию равно 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Получает или задает 32-битное значение с плавающей запятой, которое указывает длину пробела, добавляемого к начальной позиции строки. По умолчанию это 1/6 дюйма; для типографических шрифтов значение по умолчанию равно 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Получает или задает 32-битное беззнаковое целое, которое определяет вертикальное выравнивание строки в прямоугольнике макета. Это значение ДОЛЖНО быть определено в перечислении StringAlignment.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет вертикальное выравнивание строки в прямоугольнике макета. Это значение ДОЛЖНО быть определено в перечислении StringAlignment.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Получает или задает 32-битное знаковое целое, которое указывает количество объектов EmfPlusCharacterRange (раздел 2.2.2.8), определённых в поле StringFormatData.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает количество объектов EmfPlusCharacterRange (раздел 2.2.2.8), определённых в поле StringFormatData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как выравнивать строку по горизонтали в прямоугольнике размещения. Это значение ДОЛЖНО быть определено в перечислении StringAlignment (раздел 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как выравнивать строку по горизонтали в прямоугольнике размещения. Это значение ДОЛЖНО быть определено в перечислении StringAlignment (раздел 2.1.1.29).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Получает или задает объект EmfPlusStringFormatData (раздел 2.2.2.44), который определяет дополнительные данные макета текста.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Получает или задает объект EmfPlusStringFormatData (раздел 2.2.2.44), который определяет дополнительные данные макета текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Получает или задает 32-битное беззнаковое целое, которое определяет параметры размещения текста для форматирования, обрезки и обработки шрифтов. Это значение ДОЛЖНО состоять из флагов StringFormat (раздел 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет параметры размещения текста для форматирования, обрезки и обработки шрифтов. Это значение ДОЛЖНО состоять из флагов StringFormat (раздел 2.1.2.8).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Получает или задает 32-битное знаковое целое, которое указывает количество табуляций, определённых в поле StringFormatData.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает количество табуляций, определённых в поле StringFormatData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Получает или задает 32-битное число с плавающей запятой, которое определяет отношение горизонтального пространства, выделенного каждому символу в указанной строке, к ширине символа, определенной шрифтом. Большие значения этого свойства указывают на обильный интервал между символами; значения меньше 1 могут приводить к наложению символов. Значение по умолчанию — 1.03; для типографических шрифтов значение по умолчанию — 1.00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Получает или задает 32-битное число с плавающей запятой, которое определяет отношение горизонтального пространства, выделенного каждому символу в указанной строке, к ширине символа, определенной шрифтом. Большие значения этого свойства указывают на обильный интервал между символами; значения меньше 1 могут приводить к наложению символов. Значение по умолчанию — 1.03; для типографических шрифтов значение по умолчанию — 1.00.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Получает или задает 32-битное число с плавающей запятой, которое определяет длину пробела, оставляемого после строки. Значение по умолчанию — 1/6 дюйма; для типографических шрифтов значение по умолчанию — 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Получает или задает 32-битное число с плавающей запятой, которое определяет длину пробела, оставляемого после строки. Значение по умолчанию — 1/6 дюйма; для типографических шрифтов значение по умолчанию — 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Получает или задает способ обрезки символов из строки, которая слишком велика, чтобы поместиться в прямоугольник размещения. Это значение ДОЛЖНО быть определено в перечислении StringTrimming (раздел 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Получает или задает способ обрезки символов из строки, которая слишком велика, чтобы поместиться в прямоугольник размещения. Это значение ДОЛЖНО быть определено в перечислении StringTrimming (раздел 2.1.1.31).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

