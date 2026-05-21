---
title: "OdGradientStyle"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El estilo de degradado"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.opendocument.enums/odgradientstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdGradientStyle extends System.Enum
```

El estilo de degradado
## Campos

| Campo | Descripción |
| --- | --- |
| [Axial](#Axial) | El axial define un degradado bi‑lineal que también se conoce como degradado reflejado o degradado lineal espejo. |
| [Ellipsoid](#Ellipsoid) | El elipsoide define un degradado donde los colores se mezclan a lo largo del radio desde el centro de un elipsoide según lo definido con los atributos draw:cx y draw:cy. |
| [Linear](#Linear) | El lineal define un degradado donde los colores se mezclan a lo largo del eje lineal del degradado. |
| [Radial](#Radial) | El radial define un degradado donde los colores se mezclan a lo largo del radio desde el centro de un círculo según lo definido con los atributos draw:cx y draw:cy. |
| [Rectangle](#Rectangle) | El rectángulo define un degradado que produce una mezcla rectangular desde el centro del rectángulo hasta el borde más corto de los 4. |
| [Square](#Square) | El cuadrado define un degradado que produce una mezcla cuadrada, imitando la perspectiva visual en un corredor o la vista aérea de una pirámide. |
| [None](#None) | El estilo de degradado es ninguno |
### Axial {#Axial}
```
public static final int Axial
```


El axial define un degradado bi‑lineal que también se conoce como degradado reflejado o degradado lineal espejo. Se crea como un degradado lineal que se refleja (o se espeja) a lo largo de su eje.

### Ellipsoid {#Ellipsoid}
```
public static final int Ellipsoid
```


El elipsoide define un degradado donde los colores se mezclan a lo largo del radio desde el centro de un elipsoide según lo definido con los atributos draw:cx y draw:cy. La longitud del eje semi mayor es el ancho del área rellenada y la longitud del eje semi menor

### Linear {#Linear}
```
public static final int Linear
```


El lineal define un degradado donde los colores se mezclan a lo largo del eje lineal del degradado. El eje del degradado se especifica con el atributo draw:angle en sentido horario respecto al eje vertical.

### Radial {#Radial}
```
public static final int Radial
```


El radial define un degradado donde los colores se mezclan a lo largo del radio desde el centro de un círculo según lo definido con los atributos draw:cx y draw:cy. El exterior del círculo se rellena con el color final.

### Rectangle {#Rectangle}
```
public static final int Rectangle
```


El rectángulo define un degradado que produce una mezcla rectangular desde el centro del rectángulo hasta el borde más corto de los 4. El centro del rectángulo se define con los atributos draw:cx y draw:cy. El ancho del rectángulo es el ancho del área rellenada, la altura del rectángulo es la altura del área rellenada. El exterior del cuadrado se rellena con el color final.

### Square {#Square}
```
public static final int Square
```


El cuadrado define un degradado que produce una mezcla cuadrada, imitando la perspectiva visual en un corredor o la vista aérea de una pirámide. También conocido como "box gradient" y "pyramidal gradient". El centro del cuadrado se define con los atributos draw:cx y draw:cy. El ancho y la altura del cuadrado son el valor mínimo entre el ancho o la altura del área rellenada. El exterior del cuadrado se rellena con el color final.

### None {#None}
```
public static final int None
```


El estilo de degradado es ninguno

