---
title: WmfMetafileEscapes
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración MetafileEscapes especifica la funcionalidad del controlador de impresora que podría no ser accesible directamente a través de los registros WMF definidos en la enumeración RecordType sección 2.1.1.1.
type: docs
weight: 8230
url: /es/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

La enumeración MetafileEscapes especifica la funcionalidad del controlador de impresora que podría no ser accesible directamente a través de los registros WMF definidos en la enumeración RecordType (sección 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Newframe | `1` | Notifica al controlador de la impresora que la aplicación ha terminado de escribir en una página. |
| Abortdoc | `2` | Detiene el procesamiento del documento actual. |
| Nextband | `3` | Notifica al controlador de la impresora que la aplicación ha terminado de escribir en una banda. |
| Setcolortable | `4` | Establece los valores de la tabla de colores. |
| Getcolortable | `5` | Obtiene los valores de la tabla de colores. |
| Flushout | `6` | Hace que toda la salida pendiente se vacíe al dispositivo de salida. |
| Draftmode | `7` | Indica que el controlador de la impresora DEBE imprimir solo texto y no gráficos. |
| Queryescsupport | `8` | Consulta un controlador de impresora para determinar si una función de escape específica es compatible con el dispositivo de salida que controla. |
| Setabortproc | `9` | Establece la función definida por la aplicación que permite cancelar un trabajo de impresión durante la impresión. |
| Startdoc | `10` | Notifica al controlador de la impresora que se está iniciando un nuevo trabajo de impresión. |
| Enddoc | `11` | Notifica al controlador de la impresora que el trabajo de impresión actual está finalizando. |
| Getphyspagesize | `12` | Recupera el tamaño de página físico actualmente seleccionado en un dispositivo de salida. |
| Getprintingoffset | `13` | Recupera el desplazamiento desde la esquina superior izquierda de la página física donde comienza la impresión o el dibujo real. |
| Getscalingfactor | `14` | Recupera los factores de escala para el eje x y el eje y de una impresora. |
| MetaEscapeEnhancedMetafile | `15` | Se utiliza para incrustar un metarchivo de formato de metarchivo mejorado (EMF) dentro de un metarchivo WMF. |
| Setpenwidth | `16` | Establece el ancho de un lápiz en píxeles. |
| Setcopycount | `17` | Establece el número de copias. |
| Setpapersource | `18` | Establece el origen, como una bandeja de papel o contenedor particular en una impresora, para formularios de salida. |
| Passthrough | `19` | Este registro pasa por datos arbitrarios. |
| Gettechnology | `20` | Obtiene información sobre la tecnología de gráficos compatible con un dispositivo . |
| Setlinecap | `21` | Especifica el modo de dibujo de líneas que se usará en la salida a un dispositivo. |
| Setlinejoin | `22` | Especifica el modo de unión de línea que se utilizará en la salida a un dispositivo. |
| Setmiterlimit | `23` | Establece el límite para la longitud de las uniones a inglete para usar en la salida a un dispositivo. |
| Bandinfo | `24` | Recupera o especifica la configuración relacionada con las bandas en un dispositivo, como el número de bandas. |
| Drawpatternrect | `25` | Dibuja un rectángulo con un patrón definido. |
| Getvectorpensize | `26` | Recupera el tamaño de bolígrafo físico definido actualmente en un dispositivo. |
| Getvectorbrushsize | `27` | Recupera el tamaño de pincel físico definido actualmente en un dispositivo. |
| Enableduplex | `28` | Activa o desactiva la impresión a doble cara (dúplex) en un dispositivo. |
| Getsetpaperbins | `29` | Recupera o especifica el origen de los formularios de salida en un dispositivo. |
| Getsetprintorient | `30` | Recupera o especifica la orientación del papel en un dispositivo. |
| Enumpaperbins | `31` | Recupera información sobre las fuentes de diferentes formularios en un dispositivo de salida . |
| Setdibscaling | `32` | Especifica la escala de mapas de bits independientes del dispositivo (DIB). |
| Epsprinting | `33` | Indica el inicio y el final de una sección de PostScript encapsulado (EPS). |
| Enumpapermetrics | `34` | Consulta a un controlador de impresora las dimensiones del papel y otros datos de formularios. |
| Getsetpapermetrics | `35` | Recupera o especifica las dimensiones del papel y otros datos de formularios en un dispositivo de salida . |
| PostscriptData | `37` | Envía datos PostScript arbitrarios a un dispositivo de salida. |
| PostscriptIgnore | `38` | Notifica a un dispositivo de salida que ignore los datos PostScript. |
| Getdeviceunits | `42` | Obtiene las unidades de dispositivo actualmente configuradas en un dispositivo de salida. |
| Getextendedtextmetrics | `256` | Obtiene métricas de texto extendidas actualmente configuradas en un dispositivo de salida . |
| Getpairkerntable | `258` | Obtiene la tabla de interletraje de fuentes definida actualmente en un dispositivo de salida. |
| Exttextout | `512` | Dibuja texto utilizando la fuente, el color de fondo y el color de texto seleccionados actualmente. |
| Getfacename | `513` | Obtiene el nombre de la fuente configurada actualmente en un dispositivo. |
| Downloadface | `514` | Establece el nombre de la fuente en un dispositivo. |
| MetafileDriver | `2049` | Consulta a un controlador de impresora sobre la compatibilidad con metarchivos en un dispositivo de salida . |
| Querydibsupport | `3073` | Consulta al controlador de la impresora sobre su compatibilidad con DIB en un dispositivo de salida. |
| BeginPath | `4096` | Abre un camino. |
| ClipToPath | `4097` | Define una región de recorte que está delimitada por una ruta. La entrada DEBE ser una cantidad de 16 bits que define la acción a tomar. |
| EndPath | `4098` | Finaliza un camino. |
| OpenChannel | `4110` | Lo mismo que STARTDOC especificado con un documento NULL y un nombre de archivo de salida , datos en modo sin procesar y un tipo de cero. |
| Downloadheader | `4111` | Indica al controlador de la impresora que descargue conjuntos de procedimientos PostScript. |
| CloseChannel | `4112` | Igual que ENDDOC. Ver OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Envía datos arbitrarios directamente a un controlador de impresora, que se espera que procese estos datos solo en modo PostScript.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | Envía datos arbitrarios directamente al controlador de la impresora. |
| PostscriptIdentify | `4117` | Establece el controlador de la impresora en modo PostScript o GDI. |
| PostscriptInjection | `4118` | Inserta un bloque de datos sin procesar en un flujo PostScript. La entrada DEBE ser una cantidad de 32 bits que especifica el número de bytes a inyectar, una cantidad de 16 bits que especifica el punto de inyección y una cantidad de 16 bits que especifica el número de página, seguida de los bytes a inyectar. |
| Checkjpegformat | `4119` | Comprueba si la impresora admite una imagen JPEG. |
| Checkpngformat | `4120` | Comprueba si la impresora admite una imagen PNG. |
| GetPsFeaturesetting | `4121` | Obtiene información sobre una configuración de función específica para un controlador de impresora PostScript . |
| MxdcEscape | `4122` | Permite que las aplicaciones escriban documentos en un archivo o en una impresora en formato XML Paper Specification (XPS). |
| Spclpassthrough2 | `4568` | Permite que las aplicaciones incluyan procedimientos privados y otros datos arbitrarios en documentos. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
