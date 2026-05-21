---
title: "EmfMapMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración MapMode se usa para definir la unidad de medida para transformar unidades del espacio de página en unidades del espacio del dispositivo y para definir la orientación de los ejes de dibujo."
type: docs
weight: 30
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

La enumeración MapMode se usa para definir la unidad de medida para transformar unidades del espacio de página en unidades del espacio del dispositivo y para definir la orientación de los ejes de dibujo.
## Campos

| Campo | Descripción |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Cada unidad lógica se asigna a un píxel del dispositivo. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Cada unidad lógica se asigna a 0,1 milímetro. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Cada unidad lógica se asigna a 0,01 milímetro. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Cada unidad lógica se asigna a 0,01 pulgada. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Cada unidad lógica se asigna a 0,001 pulgada. |
| [MM_TWIPS](#MM-TWIPS) | Cada unidad lógica se asigna a una vigésima parte del punto de una impresora (1/1440 de pulgada, también llamado "twip"). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados de forma equitativa; es decir, una unidad a lo largo del eje x es igual a una unidad a lo largo del eje y. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados arbitrariamente. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Cada unidad lógica se asigna a un píxel del dispositivo. El eje x positivo está a la derecha; el eje y positivo está hacia abajo.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Cada unidad lógica se asigna a 0,1 milímetro. El eje x positivo está a la derecha; el eje y positivo está hacia arriba.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Cada unidad lógica se asigna a 0,01 milímetro. El eje x positivo está a la derecha; el eje y positivo está hacia arriba.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Cada unidad lógica se asigna a 0,01 pulgada. El eje x positivo está a la derecha; el eje y positivo está hacia arriba

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Cada unidad lógica se asigna a 0,001 pulgada. El eje x positivo está a la derecha; el eje y positivo está hacia arriba.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Cada unidad lógica se asigna a una vigésima parte del punto de una impresora (1/1440 de pulgada, también llamado "twip"). El eje x positivo está a la derecha; el eje y positivo está hacia arriba.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados de forma equitativa; es decir, una unidad a lo largo del eje x es igual a una unidad a lo largo del eje y. Los registros EMR\_SETWINDOWEXTEX y EMR\_SETVIEWPORTEXTEX DEBERÍAN usarse para especificar las unidades y la orientación de los ejes. Se DEBEN realizar ajustes según sea necesario para garantizar que las unidades x e y mantengan el mismo tamaño. Por ejemplo, cuando se establece la extensión de la ventana, el viewport DEBE ajustarse para mantener las unidades isotrópicas.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Las unidades lógicas se asignan a unidades arbitrarias con ejes escalados arbitrariamente. Los registros EMR\_SETWINDOWEXTEX y EMR\_SETVIEWPORTEXTEX DEBERÍAN usarse para especificar las unidades, la orientación y el escalado.

