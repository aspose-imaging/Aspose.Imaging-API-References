---
title: Font
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa un nuevoFontaspose.imaging/font que utiliza el especificado existenteFontaspose.imaging/font yFontStyleaspose.imaging/fontstyle enumeración.
type: docs
weight: 10
url: /es/net/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

Inicializa un nuevo[`Font`](../../font) que utiliza el especificado existente[`Font`](../../font) y[`FontStyle`](../../fontstyle) enumeración.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| prototype | Font | La existencia[`Font`](../../font) a partir de la cual crear el nuevo[`Font`](../../font). |
| newStyle | FontStyle | los[`FontStyle`](../../fontstyle)para aplicar a la nueva[`Font`](../../font) . Múltiples valores de la[`FontStyle`](../../fontstyle) La enumeración se puede combinar con el operador OR. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *prototype* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

Inicializa un nuevo[`Font`](../../font) usando un tamaño específico. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint , el estilo de fuente paraRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../../font) nombre. |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Inicializa un nuevo[`Font`](../../font) usando un tamaño y estilo especificado. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../../font) nombre. |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |
| style | FontStyle | los[`FontStyle`](../../fontstyle) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Inicializa un nuevo[`Font`](../../font) utilizando un tamaño y una unidad específicos. El conjunto de caracteres se establece enDefault , el estilo se establece enRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../../font) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| unit | GraphicsUnit | los[`GraphicsUnit`](../../graphicsunit) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Inicializa un nuevo[`Font`](../../font) utilizando un tamaño, estilo, unidad y conjunto de caracteres especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../../font) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| style | FontStyle | los[`FontStyle`](../../fontstyle) de la nueva fuente. |
| unit | GraphicsUnit | los[`GraphicsUnit`](../../graphicsunit) de la nueva fuente. |
| characterSet | CharacterSet | Un juego de caracteres para usar con esta fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Inicializa un nuevo[`Font`](../../font) utilizando un tamaño, estilo y unidad especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../../font) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| style | FontStyle | los[`FontStyle`](../../fontstyle) de la nueva fuente. |
| unit | GraphicsUnit | los[`GraphicsUnit`](../../graphicsunit) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* espacio de nombres [Aspose.Imaging](../../font)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
