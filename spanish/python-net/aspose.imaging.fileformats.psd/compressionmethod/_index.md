---
title: "Enumeración CompressionMethod"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Define el método de compresión utilizado para los datos de imagen.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| RAW | Sin compresión. Los datos de la imagen se almacenan como bytes sin procesar en orden planar RGBA.<br/>            Eso significa que primero se escribe todo el dato R, luego todo el dato G, después todo el dato B y finalmente todo el dato A. |
| RLE | Los datos de la imagen comprimidos con RLE comienzan con los recuentos de bytes para todas las líneas de escaneo (filas * canales), con cada<br/>            recuento almacenado como un valor de dos bytes. A continuación se encuentran los datos comprimidos con RLE, con cada línea de escaneo comprimida por separado.<br/>            La compresión RLE es el mismo algoritmo de compresión utilizado por la rutina PackBits del ROM de Macintosh y el estándar TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP sin predicción. |
| ZIP_WITH_PREDICTION | ZIP con predicción. |
