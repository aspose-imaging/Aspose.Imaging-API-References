---
title: "StringFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Инкапсулирует информацию о размещении текста, такую как выравнивание, ориентация и табуляции, а также манипуляции отображением, такие как вставка многоточия, замена национальных цифр и функции OpenType."
type: docs
weight: 112
url: /ru/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Инкапсулирует информацию о размещении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StringFormat()](#StringFormat--) | Создаёт новый объект `com.aspose.imaging.StringFormat`. |
| [StringFormat(int options)](#StringFormat-int-) | Создаёт новый объект `com.aspose.imaging.StringFormat` с указанным перечислением `com.aspose.imaging.StringFormatFlags` и языком. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Создаёт новый объект `com.aspose.imaging.StringFormat` из указанного существующего объекта `com.aspose.imaging.StringFormat`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Возвращает общий объект `com.aspose.imaging.StringFormat` по умолчанию. |
| [getGenericTypographic()](#getGenericTypographic--) | Получает общий типографический объект `com.aspose.imaging.StringFormat`. |
| [getFormatFlags()](#getFormatFlags--) | Получает перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Устанавливает перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании. |
| [getAlignment()](#getAlignment--) | Получает информацию о выравнивании текста по вертикали. |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает информацию о выравнивании текста по вертикали. |
| [getLineAlignment()](#getLineAlignment--) | Получает выравнивание строк по горизонтали. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Устанавливает выравнивание строк по горизонтали. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Получает объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Устанавливает объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`. |
| [getTrimming()](#getTrimming--) | Получает перечисление `com.aspose.imaging.StringTrimming` для этого объекта `com.aspose.imaging.StringFormat`. |
| [setTrimming(int value)](#setTrimming-int-) | Устанавливает перечисление `com.aspose.imaging.StringTrimming` для этого объекта `com.aspose.imaging.StringFormat`. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Получает метод, используемый для замены цифр. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Устанавливает метод, используемый для замены цифр. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Получает язык, используемый при замене локальных цифр на западные. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Устанавливает язык, используемый при замене локальных цифр на западные. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Получает количество пробелов между началом строки текста и первой табуляцией. |
| [getTabStops()](#getTabStops--) | Получает массив расстояний между табуляциями в единицах, указанных свойством `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Получает пользовательский идентификатор символа. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Устанавливает пользовательский идентификатор символа. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого объекта `com.aspose.imaging.StringFormat`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Устанавливает табуляцию для этого объекта `com.aspose.imaging.StringFormat`. |
| [toString()](#toString--) | Преобразует этот объект `com.aspose.imaging.StringFormat` в читаемую строку. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Создаёт новый объект `com.aspose.imaging.StringFormat`.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Создаёт новый объект `com.aspose.imaging.StringFormat` с указанным перечислением `com.aspose.imaging.StringFormatFlags` и языком.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | int | Перечисление `com.aspose.imaging.StringFormatFlags` для нового объекта `com.aspose.imaging.StringFormat`. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Создаёт новый объект `com.aspose.imaging.StringFormat` из указанного существующего объекта `com.aspose.imaging.StringFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | Объект `com.aspose.imaging.StringFormat`, из которого инициализируется новый объект `com.aspose.imaging.StringFormat`. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Возвращает общий объект `com.aspose.imaging.StringFormat` по умолчанию.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Получает общий типографический объект `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Получает перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании.

**Returns:**
int - Перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Устанавливает перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `com.aspose.imaging.StringFormatFlags`, которое содержит информацию о форматировании. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Получает информацию о выравнивании текста по вертикали.

**Returns:**
int - Перечисление `com.aspose.imaging.StringAlignment`, которое указывает информацию о выравнивании текста.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Устанавливает информацию о выравнивании текста по вертикали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `com.aspose.imaging.StringAlignment`, которое указывает информацию о выравнивании текста. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Получает выравнивание строк по горизонтали.

**Returns:**
int - Перечисление `com.aspose.imaging.StringAlignment`, которое представляет выравнивание строк.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Устанавливает выравнивание строк по горизонтали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `com.aspose.imaging.StringAlignment`, которое представляет выравнивание строк. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Получает объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`.

**Returns:**
int - Объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`, по умолчанию `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Устанавливает объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Объект `com.aspose.imaging.HotkeyPrefix` для этого объекта `com.aspose.imaging.StringFormat`, по умолчанию `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Получает перечисление `com.aspose.imaging.StringTrimming` для этого объекта `com.aspose.imaging.StringFormat`.

**Returns:**
int - Перечисление `com.aspose.imaging.StringTrimming`, которое указывает, как обрезается текст, отрисованный этим объектом `com.aspose.imaging.StringFormat`, когда он выходит за пределы прямоугольника макета.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Устанавливает перечисление `com.aspose.imaging.StringTrimming` для этого объекта `com.aspose.imaging.StringFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `com.aspose.imaging.StringTrimming`, которое указывает, как обрезается текст, отрисованный этим объектом `com.aspose.imaging.StringFormat`, когда он выходит за пределы прямоугольника макета. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Получает метод, используемый для замены цифр.

**Returns:**
int - Значение перечисления `com.aspose.imaging.StringDigitSubstitute`, которое определяет, как заменять символы в строке, которые не могут быть отображены, потому что текущий шрифт их не поддерживает.

Сеттер введён для устаревшего метода SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Устанавливает метод, используемый для замены цифр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Значение перечисления `com.aspose.imaging.StringDigitSubstitute`, которое определяет, как заменять символы в строке, которые не могут быть отображены, потому что текущий шрифт их не поддерживает. |

Сеттер введён для устаревшего метода SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Получает язык, используемый при замене локальных цифр на западные.

**Returns:**
int - Идентификатор языка National Language Support (NLS), который определяет язык, используемый при замене локальных цифр на западные. Вы можете передать свойство `P:System.Globalization.CultureInfo.LCID` объекта `System.Globalization.CultureInfo` в качестве идентификатора языка NLS. Например, предположим, что вы создаёте и задаёте локаль "ar-EG". Если передать `com.aspose.imaging.StringDigitSubstitute.Traditional` в метод `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, то арабско‑индийские цифры будут заменяться на западные при отображении.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Устанавливает язык, используемый при замене локальных цифр на западные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Идентификатор языка National Language Support (NLS), который определяет язык, используемый при замене локальных цифр на западные. Вы можете передать свойство `P:System.Globalization.CultureInfo.LCID` объекта `System.Globalization.CultureInfo` в качестве идентификатора языка NLS. Например, предположим, что вы создаёте и задаёте локаль "ar-EG". Если передать `com.aspose.imaging.StringDigitSubstitute.Traditional` в метод `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, то арабско‑индийские цифры будут заменяться на западные при отображении. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Получает количество пробелов между началом строки текста и первой табуляцией.

**Returns:**
float - Смещение первой табуляции.

Свойство введено для удалённого метода GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Получает массив расстояний между табуляциями в единицах, указанных свойством `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Позиции табуляции.

Свойство введено для удалённого метода GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Получает пользовательский идентификатор символа.

Значение: Идентификатор пользовательского символа.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Устанавливает пользовательский идентификатор символа.

Значение: Идентификатор пользовательского символа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | идентификатор пользовательского символа. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Создаёт глубокую копию этого объекта `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Устанавливает табуляцию для этого объекта `com.aspose.imaging.StringFormat`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstTabOffset | float | Количество пробелов между началом строки текста и первой позицией табуляции. |
| tabStops | float[] | Массив расстояний между позициями табуляции в единицах, указанных свойством `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


Преобразует этот объект `com.aspose.imaging.StringFormat` в читаемую строку.

**Returns:**
java.lang.String - Строковое представление этого объекта `com.aspose.imaging.StringFormat`.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
