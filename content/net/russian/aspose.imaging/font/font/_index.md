---
title: Font
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новыйFontaspose.imaging/font который использует указанный существующийFontaspose.imaging/font а такжеFontStyleaspose.imaging/fontstyle перечисление.
type: docs
weight: 10
url: /ru/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

Инициализирует новый[`Font`](../../font) который использует указанный существующий[`Font`](../../font) а также[`FontStyle`](../../fontstyle) перечисление.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | Font | Существующий[`Font`](../../font) из которого создать новый[`Font`](../../font). |
| newStyle | FontStyle | [`FontStyle`](../../fontstyle)подать заявку на новый[`Font`](../../font) . Несколько значений[`FontStyle`](../../fontstyle) перечисление можно комбинировать с оператором ИЛИ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *prototype* нулевой. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

Инициализирует новый[`Font`](../../font) используя заданный размер. Набор символов установлен наDefault , графический блок кPoint , стиль шрифта дляRegular .

```csharp
public Font(string fontName, float emSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление[`Font`](../../font) имя. |
| emSize | Single | Размер em нового шрифта в пунктах. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* нулевой. |

### Смотрите также

* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Инициализирует новый[`Font`](../../font) с использованием определенного размера и стиля. Набор символов установлен наDefault , графический блок кPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление[`Font`](../../font) имя. |
| emSize | Single | Размер em нового шрифта в пунктах. |
| style | FontStyle | [`FontStyle`](../../fontstyle) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* нулевой. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Инициализирует новый[`Font`](../../font) используя указанный размер и единицу измерения. Набор символов установлен наDefault , стиль установлен наRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление[`Font`](../../font) имя. |
| emSize | Single | Размер em нового шрифта в единицах, указанных*unit* параметр. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* нулевой. |

### Смотрите также

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Инициализирует новый[`Font`](../../font) используя указанный размер, стиль, единицу измерения и набор символов.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление[`Font`](../../font) имя. |
| emSize | Single | Размер em нового шрифта в единицах, указанных*unit* параметр. |
| style | FontStyle | [`FontStyle`](../../fontstyle) нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit) нового шрифта. |
| characterSet | CharacterSet | Набор символов, используемый для этого шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* нулевой. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Инициализирует новый[`Font`](../../font) используя указанный размер, стиль и единицу измерения.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Строковое представление[`Font`](../../font) имя. |
| emSize | Single | Размер em нового шрифта в единицах, указанных*unit* параметр. |
| style | FontStyle | [`FontStyle`](../../fontstyle) нового шрифта. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit) нового шрифта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* меньше или равно 0, равно бесконечности или не является допустимым числом. |
| ArgumentNullException | *fontName* нулевой. |

### Смотрите также

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* пространство имен [Aspose.Imaging](../../font)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
