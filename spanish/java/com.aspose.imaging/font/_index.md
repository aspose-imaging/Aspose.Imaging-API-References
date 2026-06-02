---
title: "Fuente"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define un formato particular para el texto que incluye el tamaño de la fuente y los atributos de estilo."
type: docs
weight: 48
url: /es/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Define un formato particular para el texto, incluyendo la fuente, el tamaño y los atributos de estilo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Inicializa una nueva `com.aspose.imaging.Font` que usa la `com.aspose.imaging.Font` existente especificada y la enumeración `com.aspose.imaging.FontStyle`. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño especificado. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño y estilo especificados. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño, estilo, unidad y conjunto de caracteres especificados. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño, estilo y unidad especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño y unidad especificados. |
| [getBold()](#getBold--) | Obtiene un valor que indica si esta `Font` está en negrita. |
| [getCharacterSet()](#getCharacterSet--) | Obtiene un valor de byte que especifica el conjunto de caracteres que usa esta `Font`. |
| [getItalic()](#getItalic--) | Obtiene un valor que indica si esta `Font` está en cursiva. |
| [getName()](#getName--) | Obtiene el nombre de la fuente de esta `Font`. |
| [getStrikeout()](#getStrikeout--) | Obtiene un valor que indica si esta `Font` especifica una línea horizontal a través de la fuente. |
| [getUnderline()](#getUnderline--) | Obtiene un valor que indica si esta `Font` está subrayada. |
| [getStyle()](#getStyle--) | Obtiene información de estilo para esta `Font`. |
| [getSize()](#getSize--) | Obtiene el tamaño em de esta `Font` medido en las unidades especificadas por la propiedad `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | Obtiene la unidad de medida de este `Font`. |
| [deepClone()](#deepClone--) | Crea una copia profunda exacta de este `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica si el objeto especificado es un `com.aspose.imaging.Font` y tiene los mismos valores de propiedades que este `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Obtiene el código hash de este `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Este ejemplo demuestra el uso de las clases Font y SolidBrush para dibujar cadenas en la superficie de Image. El ejemplo crea una nueva Image y dibuja formas usando Figures y GraphicsPath
``` java
//Crea una instancia de BmpOptions y establece sus diversas propiedades.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
//El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crea una instancia de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inicializa una instancia de la clase Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Limpia la superficie de Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea una instancia de Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crea una instancia de SolidBrush con color rojo
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Dibuja una cadena
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // guarda todos los cambios
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inicializa una nueva `com.aspose.imaging.Font` que usa la `com.aspose.imaging.Font` existente especificada y la enumeración `com.aspose.imaging.FontStyle`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | El `com.aspose.imaging.Font` existente del cual crear el nuevo `com.aspose.imaging.Font`. |
| newStyle | int | El `com.aspose.imaging.FontStyle` que se aplicará al nuevo `com.aspose.imaging.Font`. Se pueden combinar múltiples valores de la enumeración `com.aspose.imaging.FontStyle` con el operador OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Inicializa un nuevo `com.aspose.imaging.Font` usando un tamaño especificado. El conjunto de caracteres se establece en `F:Aspose.Imaging.CharacterSet.Default`, la unidad gráfica en `F:Aspose.Imaging.GraphicsUnit.Point` y el estilo de fuente en `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación de cadena del nombre del `com.aspose.imaging.Font`. |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Inicializa un nuevo `com.aspose.imaging.Font` usando un tamaño y estilo especificados. El conjunto de caracteres se establece en `F:Aspose.Imaging.CharacterSet.Default` y la unidad gráfica en `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación de cadena del nombre del `com.aspose.imaging.Font`. |
| emSize | float | El tamaño em, en puntos, de la nueva fuente. |
| style | int | El `com.aspose.imaging.FontStyle` de la nueva fuente. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación de cadena del nombre del `com.aspose.imaging.Font`. |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El `com.aspose.imaging.FontStyle` de la nueva fuente. |
| unit | int | La `com.aspose.imaging.GraphicsUnit` de la nueva fuente. |
| characterSet | int | Un conjunto de caracteres para usar con esta fuente. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Inicializa una nueva `com.aspose.imaging.Font` usando un tamaño, estilo y unidad especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación de cadena del nombre del `com.aspose.imaging.Font`. |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| style | int | El `com.aspose.imaging.FontStyle` de la nueva fuente. |
| unit | int | La `com.aspose.imaging.GraphicsUnit` de la nueva fuente. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Inicializa un nuevo `com.aspose.imaging.Font` usando un tamaño y unidad especificados. El conjunto de caracteres se establece en `F:Aspose.Imaging.CharacterSet.Default`, el estilo se establece en `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Una representación de cadena del nombre del `com.aspose.imaging.Font`. |
| emSize | float | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro `unit`. |
| unit | int | La `com.aspose.imaging.GraphicsUnit` de la nueva fuente. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Obtiene un valor que indica si esta `Font` está en negrita.

**Returns:**
boolean - Verdadero si este `Font` es negrita; de lo contrario, falso.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Obtiene un valor de byte que especifica el conjunto de caracteres que usa esta `Font`.

**Returns:**
int - Un conjunto de caracteres que este `Font` utiliza.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Obtiene un valor que indica si esta `Font` está en cursiva.

**Returns:**
boolean - Verdadero si este `Font` es cursiva; de lo contrario, falso.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre de la fuente de esta `Font`.

**Returns:**
java.lang.String - Una representación en cadena del nombre de la tipografía de este `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Obtiene un valor que indica si esta `Font` especifica una línea horizontal a través de la fuente.

**Returns:**
boolean - Verdadero si este `Font` tiene una línea horizontal; de lo contrario, falso.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Obtiene un valor que indica si esta `Font` está subrayada.

**Returns:**
boolean - Verdadero si este `Font` está subrayado; de lo contrario, falso.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtiene información de estilo para esta `Font`.

**Returns:**
int - Una enumeración `FontStyle` que contiene información de estilo para este `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Obtiene el tamaño em de esta `Font` medido en las unidades especificadas por la propiedad `P:Aspose.Imaging.Font.Unit`.

**Returns:**
float - El tamaño em de este `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Obtiene la unidad de medida de este `Font`.

**Returns:**
int - Un `GraphicsUnit` que representa la unidad de medida para este `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia profunda exacta de este `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica si el objeto especificado es un `com.aspose.imaging.Font` y tiene los mismos valores de propiedades que este `com.aspose.imaging.Font`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto a probar. |

**Returns:**
boolean - Verdadero si el parámetro `obj` es un `com.aspose.imaging.Font` y tiene los mismos valores de propiedad que este `com.aspose.imaging.Font`; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de este `com.aspose.imaging.Font`.

**Returns:**
int - El código hash de este `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - Una cadena que representa este `com.aspose.imaging.Font`.
