---
title: "Enumeración WmfCompression"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

La enumeración Compression especifica el tipo de compresión para una imagen bitmap.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BI_BITFIELDS | El mapa de bits no está comprimido y la tabla de colores consta de tres máscaras de color DWORD que<br/>                especifican los componentes rojo, verde y azul, respectivamente, de cada píxel.<br/>                Esto es válido cuando se usa con mapas de bits de 16 y 32 bits por píxel. |
| BI_CMYK | La imagen está en un formato CMYK sin comprimir. |
| BI_CMYKRLE4 | Un formato CMYK que utiliza compresión RLE para mapas de bits de 4 bits por píxel.<br/>                La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de dos índices de color de longitud de palabra. |
| BI_CMYKRLE8 | Un formato CMYK que utiliza compresión RLE para mapas de bits de 8 bits por píxel.<br/>                La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de un byte que contiene un índice de color. |
| BI_JPEG | La imagen es una imagen JPEG, como se especifica en [JFIF]. Este valor DEBERÍA usarse solo en ciertas operaciones de mapa de bits<br/>                , como el paso directo de JPEG. La aplicación DEBE consultar el soporte de paso directo,<br/>                ya que no todos los dispositivos admiten el paso directo de JPEG. Usar mapas de bits no RGB PUEDE limitar la portabilidad<br/>                del metafichero a otros dispositivos. Por ejemplo, los contextos de dispositivo de pantalla generalmente no admiten este paso directo |
| BI_PNG | La imagen es una imagen PNG, como se especifica en [RFC2083]. Este valor DEBERÍA usarse solo en ciertas operaciones de mapa de bits,<br/>                como el paso directo de JPEG/PNG. La aplicación DEBE consultar el soporte de paso directo, porque no todos los dispositivos<br/>                admiten el paso directo de JPEG/PNG. Usar mapas de bits no RGB PUEDE limitar la portabilidad del metafichero a otros dispositivos.<br/>                Por ejemplo, los contextos de dispositivo de pantalla generalmente no admiten este paso directo. |
| BI_RGB | El bitmap está en formato rojo verde azul (RGB) sin comprimir que no está comprimido y no utiliza máscaras de color. |
| BI_RLE4 | Un formato RGB que utiliza compresión RLE para mapas de bits con 4 bits por píxel.<br/>                La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de dos índices de color de longitud de palabra |
| BI_RLE8 | Un formato RGB que utiliza codificación por longitud de carrera (RLE) para mapas de bits con 8 bits por píxel.<br/>                La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de un byte que contiene un índice de color. |
