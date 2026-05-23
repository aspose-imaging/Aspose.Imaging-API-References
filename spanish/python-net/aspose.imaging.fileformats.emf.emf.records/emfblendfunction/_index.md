---
title: "Clase EmfBlendFunction"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Inicializa una nueva instancia de la clase EmfBlendFunction |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Inicializa una nueva instancia de la clase [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Obtiene una estructura que especifica cómo se interpretan los píxeles de origen y destino <br/>            con respecto a la transparencia alfa. |
| blend_flags | System.Byte | r | Obtiene los indicadores de mezcla.<br/>            Este valor DEBE ser 0x00 y DEBE ser ignorado. |
| blend_operation | System.Byte | r | Obtiene el código de operación de mezcla. <br/>            La única operación de mezcla de origen y destino <br/>            que se ha definido es 0x00, que especifica que el mapa de bits de origen <br/>            DEBE combinarse con el mapa de bits de destino basándose en los valores de transparencia alfa <br/>            de los píxeles de origen. Consulte las siguientes ecuaciones para obtener detalles. |
| src_constant_alpha | System.Byte | r | Obtiene un entero sin signo de 8 bits que especifica la transparencia alfa, <br/>            que determina la mezcla de los mapas de bits de origen y destino. Este valor DEBE ser <br/>            usado en todo el mapa de bits de origen. El valor mínimo de transparencia alfa, cero, <br/>            corresponde a completamente transparente y el valor máximo, 0xFF, corresponde a <br/>            completamente opaco. En efecto, un valor de 0xFF especifica que los valores alfa por píxel <br/>            determinan la mezcla de los mapas de bits de origen y destino. Consulte las ecuaciones más adelante en <br/>            esta sección para obtener detalles. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [to_int()](#to_int__1) | Convierte la representación en cadena de un número a un entero. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Inicializa una nueva instancia de la clase EmfBlendFunction

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Inicializa una nueva instancia de la clase [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dword_data | int | Los datos dword. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Convierte la representación en cadena de un número a un entero.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor DWORD de la estructura. |


