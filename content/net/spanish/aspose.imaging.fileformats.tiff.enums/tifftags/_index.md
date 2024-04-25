---
title: TiffTags
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La etiqueta tiff enum.
type: docs
weight: 7740
url: /es/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

La etiqueta tiff enum.

```csharp
public enum TiffTags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SubFileType | `254` | Descriptor de datos de subarchivo. |
| OsubfileType | `255` | [obsoleto por TIFF rev. 5.0] Tipo de dato en subfile. |
| ImageWidth | `256` | Ancho de la imagen en píxeles. |
| ImageLength | `257` | Altura de la imagen en píxeles. |
| BitsPerSample | `258` | Bits por canal (muestra). |
| Compression | `259` | Técnica de compresión de datos. |
| Photometric | `262` | Interpretación fotométrica. |
| Thresholding | `263` | [obsoleto por TIFF rev. 5.0] Umbral utilizado en los datos. |
| CellWidth | `264` | [obsoleto por TIFF rev. 5.0] Ancho de matriz de tramado. |
| CellLength | `265` | [obsoleto por TIFF rev. 5.0] Altura de la matriz de tramado. |
| FillOrder | `266` | Orden de datos dentro de un byte. |
| DocumentName | `269` | Nombre del documento que contiene la imagen. |
| ImageDescription | `270` | Información sobre la imagen. |
| Make | `271` | Nombre del fabricante del escáner. |
| Model | `272` | Nombre/número de modelo de escáner. |
| StripOffsets | `273` | Compensaciones a tiras de datos. |
| Orientation | `274` | [obsoleto por TIFF rev. 5.0] Orientación de la imagen. |
| SamplesPerPixel | `277` | Muestras por píxel. |
| RowsPerStrip | `278` | Filas por tira de datos. |
| StripByteCounts | `279` | Recuento de bytes para tiras. |
| MinSampleValue | `280` | [obsoleto por TIFF rev. 5.0] Valor mínimo de muestra. |
| MaxSampleValue | `281` | [obsoleto por TIFF rev. 5.0] Valor máximo de muestra. |
| Xresolution | `282` | Píxeles/resolución en x. |
| Yresolution | `283` | Píxeles/resolución en y. |
| PlanarConfig | `284` | Organización de almacenamiento. |
| PageName | `285` | La imagen del nombre de la página es de. |
| Xposition | `286` | Desplazamiento de página X de la imagen lhs. |
| Yposition | `287` | Desplazamiento de página Y de la imagen lhs. |
| FreeOffsets | `288` | [obsoleto por TIFF rev. 5.0] Desplazamiento de bytes a bloque libre. |
| FreeByteCounts | `289` | [obsoleto por TIFF rev. 5.0] Tamaños de bloques libres. |
| GrayResponseUnit | `290` | [obsoleto por TIFF rev. 6.0] Precisión de la curva de escala de grises. |
| GrayResponseCurve | `291` | [obsoleto por TIFF rev. 6.0] Curva de respuesta de escala de grises. |
| T4Options | `292` | TIFF 6.0 alias de nombre propio para GROUP3OPTIONS. Opciones para la codificación de fax CCITT Grupo 3. 32 bits de bandera. |
| T6Options | `293` | Opciones para la codificación de fax CCITT Grupo 4. 32 bits de marca. TIFF 6.0 alias de nombre propio para GROUP4OPTIONS. |
| ResolutionUnit | `296` | Unidades de resolución. |
| PageNumber | `297` | Números de página de varias páginas. |
| ColorResponseUnit | `300` | [obsoleto por TIFF rev. 6.0] Precisión de la curva de color. |
| TransferFunction | `301` | Información de colorimetría. |
| Software | `305` | Nombre y publicación. |
| DateTime | `306` | Fecha y hora de creación. |
| Artist | `315` | Creador de la imagen. |
| HostComputer | `316` | Máquina donde se creó. |
| Predictor | `317` | Esquema de predicción con LZW. |
| WhitePoint | `318` | Imagen punto blanco. |
| PrimaryChromaticities | `319` | Cromaticidades primarias. |
| ColorMap | `320` | Mapa RGB para imagen de paleta. |
| HalftoneHints | `321` | Información de luces + sombras. |
| TileWidth | `322` | Ancho del mosaico en píxeles. |
| TileLength | `323` | Altura del mosaico en píxeles. |
| TileOffsets | `324` | Desplazamientos a mosaicos de datos. |
| TileByteCounts | `325` | Recuento de bytes para mosaicos. |
| BadFaxLines | `326` | Líneas con recuento de píxeles incorrecto. |
| CleanFaxData | `327` | Información de línea regenerada. |
| ConsecutiveBadFaxLines | `328` | Máximo de líneas incorrectas consecutivas. |
| SubIfd | `330` | Descriptores de subimagen. |
| InkSet | `332` | Tintas en imagen separada. |
| InkNames | `333` | Nombres ASCII de las tintas. |
| NumberOfInks | `334` | Número de tintas. |
| DotRange | `336` | 0% y 100% códigos de puntos. |
| TargetPrinter | `337` | Objetivo de separación. |
| ExtraSamples | `338` | Información sobre muestras adicionales. |
| SampleFormat | `339` | Formato de muestra de datos. |
| SminSampleValue | `340` | Variable MinSampleValue. |
| SmaxSampleValue | `341` | Variable MaxSampleValue. |
| TransferRange | `342` | Rango de transferencia variable |
| ClipPath | `343` | ClipPath. Presentado post TIFF rev 6.0 por Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Presentado post TIFF rev 6.0 por Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Presentado post TIFF rev 6.0 por Adobe TIFF technote 2. |
| Indexed | `346` | indexado. Presentado post TIFF rev 6.0 por Adobe TIFF Technote 3. |
| JpegTables | `347` | Flujo de tabla JPEG. Presentado post TIFF rev 6.0. |
| OpiProxy | `351` | Proxy OPI. Presentado post TIFF rev 6.0 por Adobe TIFF technote. |
| JpegProc | `512` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Algoritmo de procesamiento JPEG. |
| JpegInerchangeFormat | `513` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Puntero al marcador SOI. |
| JpegInterchangeFormatLength | `514` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Longitud de flujo JFIF |
| JpegRestartInterval | `515` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Duración del intervalo de reinicio. |
| JpegLosslessPredictors | `517` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Predictor de proceso sin pérdidas. |
| JpegPointTransform | `518` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Transformación punto sin pérdidas. |
| JpegQTables | `519` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Desplazamientos de matriz Q. |
| JpegDCtables | `520` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Compensaciones de tabla DCT. |
| JpegACtables | `521` | [obsoleto por la Nota técnica n.º 2 que especifica un esquema de JPEG en TIFF revisado] Compensaciones de coeficiente de CA. |
| YcbcrCoefficients | `529` | RGB -&gt; Transformación YCbCr. |
| YcbcrSubSampling | `530` | Factores de submuestreo YCbCr. |
| YcbcrPositioning | `531` | Posicionamiento submuestra. |
| ReferenceBlackWhite | `532` | Información de colorimetría. |
| XmlPacket | `700` | paquete XML. Presentado post TIFF rev 6.0 por Adobe XMP Specification, enero de 2004. |
| OpiImageid | `32781` | ID de imagen OPI. Presentado post TIFF rev 6.0 por Adobe TIFF technote. |
| Refpts | `32953` | Puntos de referencia de la imagen. Etiqueta privada registrada en Island Graphics. |
| Copyright | `33432` | cadena de derechos de autor. Esta etiqueta aparece en el TIFF rev. 6.0 con propietario desconocido. |
| PhotoshopResources | `34377` | Recursos de imagen de Photoshop. |
| IccProfile | `34675` | El perfil de dispositivo ICC integrado |
| ExifIfdPointer | `34665` | Un puntero al Exif IFD. |
| XPTitle | `40091` | Información sobre la imagen, utilizada por Windows Explorer. LaXPTitle es ignorado por el Explorador de Windows si elImageDescription la etiqueta existe. |
| XPComment | `40092` | Comentario sobre la imagen, usado por Windows Explorer. |
| XPAuthor | `40093` | Autor de imagen, utilizado por Windows Explorer. ElXPAuthor es ignorado por el Explorador de Windows si elArtist la etiqueta existe. |
| XPKeywords | `40094` | Palabras clave de imagen, utilizadas por Windows Explorer. |
| XPSubject | `40095` | Imagen del sujeto, utilizada por Windows Explorer. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
