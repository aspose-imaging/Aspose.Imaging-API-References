---
title: "Шрифт"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет определённый формат текста, включая размер гарнитуры шрифта и атрибуты стиля."
type: docs
weight: 48
url: /ru/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Определяет определённый формат текста, включая гарнитуру шрифта, размер и атрибуты стиля. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Инициализирует новый `com.aspose.imaging.Font`, который использует указанный существующий `com.aspose.imaging.Font` и перечисление `com.aspose.imaging.FontStyle`. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Инициализирует новый `com.aspose.imaging.Font`, используя указанный размер. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Инициализирует новый `com.aspose.imaging.Font`, используя указанный размер и стиль. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Инициализирует новый `com.aspose.imaging.Font`, используя указанные размер, стиль, единицу измерения и набор символов. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Инициализирует новый `com.aspose.imaging.Font`, используя указанные размер, стиль и единицу измерения. |
## Методы

| Метод | Описание |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Инициализирует новый `com.aspose.imaging.Font`, используя указанные размер и единицу измерения. |
| [getBold()](#getBold--) | Возвращает значение, указывающее, является ли этот `Font` полужирным. |
| [getCharacterSet()](#getCharacterSet--) | Возвращает байтовое значение, указывающее набор символов, используемый этим `Font`. |
| [getItalic()](#getItalic--) | Возвращает значение, указывающее, является ли этот `Font` курсивным. |
| [getName()](#getName--) | Возвращает название гарнитуры этого `Font`. |
| [getStrikeout()](#getStrikeout--) | Возвращает значение, указывающее, задаёт ли этот `Font` горизонтальную линию через шрифт. |
| [getUnderline()](#getUnderline--) | Возвращает значение, указывающее, подчёркнут ли этот `Font`. |
| [getStyle()](#getStyle--) | Возвращает информацию о стиле этого `Font`. |
| [getSize()](#getSize--) | Возвращает размер em этого `Font`, измеренный в единицах, указанных свойством `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | Получает единицу измерения для этого `Font`. |
| [deepClone()](#deepClone--) | Создаёт точную глубокую копию этого `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, является ли указанный объект `com.aspose.imaging.Font` и имеет ли те же значения свойств, что и этот `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Получает хеш‑код для этого `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Этот пример демонстрирует использование классов Font и SolidBrush для рисования строк на поверхности Image. Пример создаёт новое Image и рисует фигуры с помощью Figures и GraphicsPath.
``` java
//Создаёт экземпляр BmpOptions и задаёт его различные свойства.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
//Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Создаёт экземпляр Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Создаёт и инициализирует экземпляр класса Graphics.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Очищает поверхность Graphics.
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Создаёт экземпляр Font.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Создаёт экземпляр SolidBrush с красным цветом.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Рисует строку.
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Инициализирует новый `com.aspose.imaging.Font`, который использует указанный существующий `com.aspose.imaging.Font` и перечисление `com.aspose.imaging.FontStyle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Существующий `com.aspose.imaging.Font`, из которого будет создан новый `com.aspose.imaging.Font`. |
| newStyle | int | `com.aspose.imaging.FontStyle`, который следует применить к новому `com.aspose.imaging.Font`. Несколько значений перечисления `com.aspose.imaging.FontStyle` могут быть объединены оператором OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Инициализирует новый `com.aspose.imaging.Font`, используя указанный размер. Набор символов устанавливается в `F:Aspose.Imaging.CharacterSet.Default`, графическая единица — в `F:Aspose.Imaging.GraphicsUnit.Point`, стиль шрифта — в `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени `com.aspose.imaging.Font`. |
| emSize | float | Размер em в пунктах нового шрифта. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Инициализирует новый `com.aspose.imaging.Font`, используя указанный размер и стиль. Набор символов устанавливается в `F:Aspose.Imaging.CharacterSet.Default`, графическая единица — в `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени `com.aspose.imaging.Font`. |
| emSize | float | Размер em в пунктах нового шрифта. |
| style | int | `com.aspose.imaging.FontStyle` нового шрифта. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Инициализирует новый `com.aspose.imaging.Font`, используя указанные размер, стиль, единицу измерения и набор символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени `com.aspose.imaging.Font`. |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром `unit`. |
| style | int | `com.aspose.imaging.FontStyle` нового шрифта. |
| unit | int | Тип `com.aspose.imaging.GraphicsUnit` нового шрифта. |
| characterSet | int | Набор символов, используемый для этого шрифта. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Инициализирует новый `com.aspose.imaging.Font`, используя указанные размер, стиль и единицу измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени `com.aspose.imaging.Font`. |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром `unit`. |
| style | int | `com.aspose.imaging.FontStyle` нового шрифта. |
| unit | int | Тип `com.aspose.imaging.GraphicsUnit` нового шрифта. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Инициализирует новый `com.aspose.imaging.Font`, используя указанный размер и единицу измерения. Набор символов устанавливается в `F:Aspose.Imaging.CharacterSet.Default`, стиль устанавливается в `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени `com.aspose.imaging.Font`. |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром `unit`. |
| unit | int | Тип `com.aspose.imaging.GraphicsUnit` нового шрифта. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Возвращает значение, указывающее, является ли этот `Font` полужирным.

**Returns:**
boolean - True, если этот `Font` полужирный; иначе false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Возвращает байтовое значение, указывающее набор символов, используемый этим `Font`.

**Returns:**
int — набор символов, который использует этот `Font`.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Возвращает значение, указывающее, является ли этот `Font` курсивным.

**Returns:**
boolean - True, если этот `Font` курсивный; иначе false.
### getName() {#getName--}
```
public String getName()
```


Возвращает название гарнитуры этого `Font`.

**Returns:**
java.lang.String — строковое представление названия гарнитуры этого `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Возвращает значение, указывающее, задаёт ли этот `Font` горизонтальную линию через шрифт.

**Returns:**
boolean - True, если у этого `Font` есть горизонтальная черта; иначе false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Возвращает значение, указывающее, подчёркнут ли этот `Font`.

**Returns:**
boolean - True, если этот `Font` подчёркнут; иначе false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Возвращает информацию о стиле этого `Font`.

**Returns:**
int — перечисление `FontStyle`, содержащее информацию о стиле этого `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Возвращает размер em этого `Font`, измеренный в единицах, указанных свойством `P:Aspose.Imaging.Font.Unit`.

**Returns:**
float — размер em этого `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Получает единицу измерения для этого `Font`.

**Returns:**
int — `GraphicsUnit`, представляющий единицу измерения для этого `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Создаёт точную глубокую копию этого `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, является ли указанный объект `com.aspose.imaging.Font` и имеет ли те же значения свойств, что и этот `com.aspose.imaging.Font`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean - True, если параметр `obj` является `com.aspose.imaging.Font` и имеет такие же значения свойств, как у этого `com.aspose.imaging.Font`; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код для этого `com.aspose.imaging.Font`.

**Returns:**
int — хеш-код этого `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого `com.aspose.imaging.Font`.

**Returns:**
java.lang.String — строка, представляющая этот `com.aspose.imaging.Font`.
