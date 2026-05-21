---
title: "EmfPlusPixelFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración PixelFormat define los formatos de píxel que son compatibles con los mapas de bits EMF."
type: docs
weight: 43
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

La enumeración PixelFormat define formatos de píxel que son compatibles con los mapas de bits EMF+.
## Campos

| Campo | Descripción |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | El formato no está especificado. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | El formato es monocromo, y se utiliza una tabla de búsqueda de paleta de colores. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | El formato es de 16 colores, y se utiliza una tabla de búsqueda de paleta de colores. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | El formato es de 256 colores, y se utiliza una tabla de búsqueda de paleta de colores. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | El formato es de 16 bits por píxel, en escala de grises. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | El formato es de 16 bits por píxel; se usan 5 bits cada uno para los componentes rojo, verde y azul. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | El formato es de 16 bits por píxel; se usan 5 bits para el componente rojo, 6 bits para el componente verde y 5 bits para el componente azul. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | El formato es de 16 bits por píxel; se usa 1 bit para el componente alfa y 5 bits cada uno para los componentes rojo, verde y azul. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | El formato es de 24 bits por píxel; se usan 8 bits cada uno para los componentes rojo, verde y azul. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes rojo, verde y azul. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes alfa, rojo, verde y azul. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes alfa, rojo, verde y azul. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | El formato es de 48 bits por píxel; se usan 16 bits cada uno para los componentes rojo, verde y azul. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | El formato es de 64 bits por píxel; se usan 16 bits cada uno para los componentes alfa, rojo, verde y azul. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | El formato es de 64 bits por píxel; se usan 16 bits cada uno para los componentes alfa, rojo, verde y azul. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


El formato no está especificado.

--------------------

Los formatos de píxel son especificados por objetos [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap). Se codifican de la siguiente manera: - Bits 0-7: Enumeración de las constantes de formato de píxel, comenzando en cero. - Bits 8-15: El número total de bits por píxel. - Bit 16: Si está establecido, el valor de color se indexa en una paleta. - Bit 17: Si está establecido, el valor de color está en un formato compatible con GDI. - Bit 18: Si está establecido, el valor de color tiene un componente alfa. - Bit 19: Si está establecido, el valor de color tiene un componente alfa premultiplicado. - Bit 20: Si está establecido, se admiten colores extendidos, 16 bits por canal. - Bits 21-31: Reservado.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


El formato es monocromo, y se utiliza una tabla de búsqueda de paleta de colores.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


El formato es de 16 colores, y se utiliza una tabla de búsqueda de paleta de colores.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


El formato es de 256 colores, y se utiliza una tabla de búsqueda de paleta de colores.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


El formato es de 16 bits por píxel, en escala de grises.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


El formato es de 16 bits por píxel; se usan 5 bits cada uno para los componentes rojo, verde y azul. El bit restante no se utiliza.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


El formato es de 16 bits por píxel; se usan 5 bits para el componente rojo, 6 bits para el componente verde y 5 bits para el componente azul.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


El formato es de 16 bits por píxel; se usa 1 bit para el componente alfa y 5 bits cada uno para los componentes rojo, verde y azul.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


El formato es de 24 bits por píxel; se usan 8 bits cada uno para los componentes rojo, verde y azul.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes rojo, verde y azul. Los 8 bits restantes no se utilizan.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes alfa, rojo, verde y azul.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


El formato es de 32 bits por píxel; se usan 8 bits cada uno para los componentes alfa, rojo, verde y azul. Los componentes rojo, verde y azul están premultiplicados según el componente alfa.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


El formato es de 48 bits por píxel; se usan 16 bits cada uno para los componentes rojo, verde y azul.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


El formato es de 64 bits por píxel; se usan 16 bits cada uno para los componentes alfa, rojo, verde y azul.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


El formato es de 64 bits por píxel; se usan 16 bits cada uno para los componentes alfa, rojo, verde y azul. Los componentes rojo, verde y azul están premultiplicados según el componente alfa.

