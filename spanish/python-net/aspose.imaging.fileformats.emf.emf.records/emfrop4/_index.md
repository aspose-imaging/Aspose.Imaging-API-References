---
title: "EmfRop4 Clase"
type: docs
weight: 1010
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Inicializa una nueva instancia de la clase [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Obtiene el ROP3 de fondo.<br/>            Los 8 bits más significativos sin signo de un valor de operación raster ternaria de 24 bits de la enumeración WMF Ternary Raster Operation ([MS-WMF] sección 2.1.1.31). Este código define cómo combinar los datos de color de fondo de <br/>            los mapas de bits de origen y destino y el patrón de pincel. |
| foreground_rop3 | System.Byte | r | Obtiene el ROP3 de primer plano.<br/>            Los 8 bits más significativos sin signo de un valor de operación raster ternaria de 24 bits de la enumeración WMF Ternary Raster Operation. Este <br/>            código define cómo combinar los datos de color de primer plano del origen y del destino <br/>            de los mapas de bits y el patrón de pincel. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Inicializa una nueva instancia de la clase [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dword_data | int | Los datos dword. |

