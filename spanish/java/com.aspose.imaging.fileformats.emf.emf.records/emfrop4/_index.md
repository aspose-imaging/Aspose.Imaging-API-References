---
title: "EmfRop4"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Una operación raster cuaternaria que especifica operaciones raster ternarias para los colores de primer plano y de fondo de un mapa de bits."
type: docs
weight: 110
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Una operación raster cuaternaria, que especifica operaciones raster ternarias para los colores de primer plano y de fondo de un mapa de bits. Estos valores definen cómo se deben combinar los datos de color del rectángulo de origen con los datos de color del rectángulo de destino.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Inicializa una nueva instancia de la clase `EmfRop4`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Obtiene el ROP3 de fondo. |
| [getForegroundRop3()](#getForegroundRop3--) | Obtiene el ROP3 de primer plano. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Inicializa una nueva instancia de la clase `EmfRop4`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dwordData | int | Los datos dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Obtiene el ROP3 de fondo. Los 8 bits sin signo más significativos de un valor de operación raster ternaria de 24 bits de la enumeración WMF Ternary Raster Operation ([MS-WMF] sección 2.1.1.31). Este código define cómo combinar los datos de color de fondo de los mapas de bits de origen y destino y el patrón de pincel.

Valor: El ROP3 de fondo.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Obtiene el ROP3 de primer plano. Los 8 bits sin signo más significativos de un valor de operación raster ternaria de 24 bits de la enumeración WMF Ternary Raster Operation. Este código define cómo combinar los datos de color de primer plano de los mapas de bits de origen y destino y el patrón de pincel.

Valor: El ROP3 de primer plano.

**Returns:**
byte
