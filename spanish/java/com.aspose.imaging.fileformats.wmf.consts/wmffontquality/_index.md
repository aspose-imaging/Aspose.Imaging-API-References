---
title: "WmfFontQuality"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración FontQuality especifica cuán de cerca deben coincidir los atributos de la fuente lógica con los de la fuente física al renderizar texto."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

La enumeración FontQuality especifica cuán de cerca deben coincidir los atributos de la fuente lógica con los de la fuente física al renderizar texto.
## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Especifica que la calidad de los caracteres de la fuente no importa, por lo que se puede usar DRAFT. |
| [Draft](#Draft) | Especifica que la calidad de los caracteres de la fuente es menos importante que la coincidencia de los atributos lógicos. |
| [Proof](#Proof) | Especifica que la calidad de los caracteres de la fuente es más importante que la coincidencia de los atributos lógicos. |
| [Nonantialiased](#Nonantialiased) | Especifica que el anti-aliasing NO DEBERÍA usarse al renderizar texto |
| [Antialiased](#Antialiased) | Especifica que el anti-aliasing DEBERÍA usarse al renderizar texto, si la fuente lo soporta. |
| [Cleartype](#Cleartype) | Especifica que el anti-aliasing ClearType DEBERÍA usarse al renderizar texto, si la fuente lo soporta. |
### Default {#Default}
```
public static final byte Default
```


Especifica que la calidad de los caracteres de la fuente no importa, por lo que se puede usar DRAFT.

### Draft {#Draft}
```
public static final byte Draft
```


Especifica que la calidad de los caracteres de la fuente es menos importante que la coincidencia de los atributos lógicos. Para fuentes rasterizadas, el escalado DEBERÍA estar habilitado, lo que significa que hay más tamaños de fuente disponibles.

### Proof {#Proof}
```
public static final byte Proof
```


Especifica que la calidad de los caracteres de la fuente es más importante que la coincidencia de los atributos lógicos. Para fuentes rasterizadas, el escalado DEBERÍA estar deshabilitado, y se DEBERÍA elegir la fuente más cercana en tamaño.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Especifica que el anti-aliasing NO DEBERÍA usarse al renderizar texto

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Especifica que el anti-aliasing DEBERÍA usarse al renderizar texto, si la fuente lo soporta.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Especifica que el anti-aliasing ClearType DEBERÍA usarse al renderizar texto, si la fuente lo soporta.

