---
title: "SvgResourceKeeperCallback"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El callback del guardián de recursos."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

El callback del guardián de recursos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Se llama cuando el recurso de imagen está listo para exportarse. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Se llama cuando el recurso de fuente está listo para exportarse. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Se llama cuando el documento SVG está listo para exportarse. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Se llama cuando el recurso de imagen está listo para exportarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageData | byte[] | Los datos del recurso. |
| imageType | int | Tipo de la imagen. |
| suggestedFileName | java.lang.String | Nombre del archivo sugerido. |
| useEmbeddedImage | boolean[] | si se establece en `true` la imagen incrustada debe usarse. |

**Returns:**
java.lang.String - Devuelve la ruta al recurso guardado. La ruta debe ser relativa al documento SVG de destino.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Se llama cuando el recurso de fuente está listo para exportarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Las opciones de almacenamiento de fuentes. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Se llama cuando el documento SVG está listo para exportarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlData | byte[] | Los datos SVG. |
| suggestedFileName | java.lang.String | Nombre del archivo sugerido. |

**Returns:**
java.lang.String - Devuelve la ruta al documento SVG guardado.
