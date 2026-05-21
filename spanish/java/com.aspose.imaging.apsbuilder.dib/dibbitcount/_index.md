---
title: "DibBitCount"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración BitCount especifica el número de bits que definen cada píxel y el número máximo de colores en un mapa de bits independiente del dispositivo (DIB)."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

La enumeración BitCount especifica el número de bits que definen cada píxel y el número máximo de colores en un bitmap independiente del dispositivo (DIB).
## Campos

| Campo | Descripción |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | El número de bits por píxel no está definido. |
| [BIT_COUNT_1](#BIT-COUNT-1) | La imagen se especifica con dos colores. Cada píxel en el mapa de bits se representa con un solo bit. |
| [BIT_COUNT_2](#BIT-COUNT-2) | La imagen se especifica con un máximo de 16 colores. |
| [BIT_COUNT_3](#BIT-COUNT-3) | La imagen se especifica con un máximo de 256 colores. |
| [BIT_COUNT_4](#BIT-COUNT-4) | La imagen se especifica con un máximo de 2^16 colores. |
| [BIT_COUNT_5](#BIT-COUNT-5) | El mapa de bits tiene un máximo de 2^24 colores, y el campo Colors del DIB es NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | El bitmap tiene un máximo de 2^24 colores |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


El número de bits por píxel no está definido. La imagen DEBE estar en formato JPEG o PNG. Ninguno de estos formatos incluye una tabla de colores, por lo que este valor indica que no hay tabla de colores presente. Consulte [JFIF] y [RFC2083] para obtener más información sobre los formatos de compresión JPEG y PNG.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


La imagen se especifica con dos colores. Cada píxel en el bitmap está representado por un solo bit. Si el bit está apagado, el píxel se muestra con el color de la primera entrada en la tabla de colores; si el bit está encendido, el píxel tiene el color de la segunda entrada en la tabla.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


La imagen se especifica con un máximo de 16 colores. Cada píxel en el bitmap está representado por un índice de 4 bits en la tabla de colores, y cada byte contiene 2 píxeles.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


La imagen se especifica con un máximo de 256 colores. Cada píxel en el bitmap está representado por un índice de 8 bits en la tabla de colores, y cada byte contiene 1 píxel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


La imagen se especifica con un máximo de 2^16 colores. Cada píxel en el bitmap está representado por un valor de 16 bits.

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


El bitmap tiene un máximo de 2^24 colores, y el campo Colors del DIB es NULL. Cada triplete de 3 bytes en la matriz del bitmap representa las intensidades relativas de azul, verde y rojo, respectivamente, para un píxel. La tabla de colores Colors se utiliza para optimizar los colores usados en dispositivos basados en paletas, y DEBE contener el número de entradas especificado por el campo ColorUsed del objeto BitmapInfoHeader Object

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


El bitmap tiene un máximo de 2^24 colores

