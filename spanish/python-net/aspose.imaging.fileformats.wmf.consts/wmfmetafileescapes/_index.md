---
title: "WmfMetafileEscapes Enumeración"
type: docs
weight: 150
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

La enumeración MetafileEscapes especifica la funcionalidad del controlador de impresora que podría no estar<br/>                directamente accesible a través de los registros WMF definidos en la enumeración RecordType (sección 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| ABORTDOC | Detiene el procesamiento del documento actual. |
| BANDINFO | Recupera o especifica configuraciones relacionadas con el banding en un dispositivo, como el<br/>                número de bandas. |
| BEGIN_PATH | Abre una ruta. |
| CHECKJPEGFORMAT | Comprueba si la impresora admite una imagen JPEG. |
| CHECKPNGFORMAT | Comprueba si la impresora admite una imagen PNG. |
| CLIP_TO_PATH | Define una región de recorte delimitada por una ruta. La entrada DEBE ser una cantidad de 16 bits<br/>                que define la acción a realizar. |
| CLOSE_CHANNEL | Lo mismo que ENDDOC. Ver OPEN_CHANNEL. |
| DOWNLOADFACE | Establece el nombre de la fuente en un dispositivo. |
| DOWNLOADHEADER | Instruye al controlador de la impresora para descargar conjuntos de procedimientos PostScript. |
| DRAFTMODE | Indica que el controlador de la impresora DEBE imprimir solo texto y no gráficos. |
| DRAWPATTERNRECT | Dibuja un rectángulo con un patrón definido. |
| ENABLEDUPLEX | Habilita o deshabilita la impresión a doble cara (dúplex) en un dispositivo. |
| ENCAPSULATED_POSTSCRIPT | Envía datos arbitrarios directamente al controlador de la impresora. |
| ENDDOC | Notifica al controlador de la impresora que el trabajo de impresión actual está terminando. |
| END_PATH | Finaliza una ruta. |
| ENUMPAPERBINS | Recupera información sobre las fuentes de diferentes formularios en un<br/>                dispositivo de salida. |
| ENUMPAPERMETRICS | Consulta al controlador de la impresora las dimensiones del papel y otros datos de formularios. |
| EPSPRINTING | Indica el inicio y el final de una sección de PostScript encapsulado (EPS). |
| EXTTEXTOUT | Dibuja texto usando la fuente, el color de fondo y el color de texto actualmente seleccionados. |
| FLUSHOUT | Provoca que toda la salida pendiente se vacíe al dispositivo de salida. |
| GETCOLORTABLE | Obtiene los valores de la tabla de colores. |
| GETDEVICEUNITS | Obtiene las unidades del dispositivo actualmente configuradas en un dispositivo de salida. |
| GETEXTENDEDTEXTMETRICS | Obtiene métricas de texto extendidas actualmente configuradas en una salida<br/>                dispositivo. |
| GETFACENAME | Obtiene el nombre de la familia de fuente actualmente configurado en un dispositivo. |
| GETPAIRKERNTABLE | Obtiene la tabla de kerning de fuentes actualmente definida en un dispositivo de salida. |
| GETPHYSPAGESIZE | Recupera el tamaño físico de página actualmente seleccionado en un dispositivo de salida. |
| GETPRINTINGOFFSET | Recupera el desplazamiento desde la esquina superior izquierda de la página física<br/>                donde comienza la impresión o el dibujo real. |
| GETSCALINGFACTOR | Recupera los factores de escala para el eje x y el eje y de una impresora. |
| GETSETPAPERBINS | Recupera o especifica la fuente de formularios de salida en un dispositivo. |
| GETSETPAPERMETRICS | Recupera o especifica las dimensiones del papel y otros datos de formularios en un<br/>                dispositivo de salida. |
| GETSETPRINTORIENT | Recupera o especifica la orientación del papel en un dispositivo. |
| GETTECHNOLOGY | Obtiene información sobre la tecnología gráfica que es compatible con un<br/>                dispositivo. |
| GETVECTORBRUSHSIZE | Recupera el tamaño físico del pincel actualmente definido en un dispositivo. |
| GETVECTORPENSIZE | Recupera el tamaño físico del lápiz actualmente definido en un dispositivo. |
| GET_PS_FEATURESETTING | Obtiene información sobre una configuración de característica especificada para un controlador de impresora PostScript<br/>                controlador de impresora. |
| METAFILE_DRIVER | Consulta a un controlador de impresora sobre la compatibilidad con metafiles en una salida<br/>                dispositivo. |
| META_ESCAPE_ENHANCED_METAFILE | Se utiliza para incrustar un formato de metafile mejorado (EMF)<br/>                metafile dentro de un metafile WMF. |
| MXDC_ESCAPE | Permite a las aplicaciones escribir documentos en un archivo o en una impresora en el formato XML Paper<br/>                Specification (XPS). |
| NEWFRAME | Notifica al controlador de impresora que la aplicación ha terminado de escribir en una página. |
| NEXTBAND | Notifica al controlador de impresora que la aplicación ha terminado de escribir en una banda. |
| OPEN_CHANNEL | Lo mismo que STARTDOC especificado con un documento NULL y salida<br/>                filename, datos en modo crudo y un tipo de cero. |
| PASSTHROUGH | Este registro pasa datos arbitrarios. |
| POSTSCRIPT_DATA | Envía datos arbitrarios de PostScript a un dispositivo de salida. |
| POSTSCRIPT_IDENTIFY | Establece el controlador de la impresora en modo PostScript o GDI. |
| POSTSCRIPT_IGNORE | Notifica a un dispositivo de salida que ignore los datos PostScript. |
| POSTSCRIPT_INJECTION | Inserta un bloque de datos sin procesar en una secuencia PostScript. La entrada<br/>                DEBE ser una cantidad de 32 bits que especifica el número de bytes a inyectar, una cantidad de 16 bits<br/>                que especifica el punto de inyección, y una cantidad de 16 bits que especifica el número de página, seguida por<br/>                los bytes a inyectar. |
| POSTSCRIPT_PASSTHROUGH | Envía datos arbitrarios directamente a un controlador de impresora, que se<br/>                espera que procese estos datos solo cuando está en modo PostScript. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Consulta al controlador de la impresora sobre su compatibilidad con DIBs en un dispositivo de salida. |
| QUERYESCSUPPORT | Consulta a un controlador de impresora para determinar si una función de escape específica<br/>                es compatible con el dispositivo de salida que controla. |
| SETABORTPROC | Establece la función definida por la aplicación que permite cancelar un trabajo de impresión<br/>                durante la impresión. |
| SETCOLORTABLE | Establece los valores de la tabla de colores. |
| SETCOPYCOUNT | Establece el número de copias. |
| SETDIBSCALING | Especifica el escalado de mapas de bits independientes del dispositivo (DIBs). |
| SETLINECAP | Especifica el modo de dibujo de líneas a usar en la salida a un dispositivo. |
| SETLINEJOIN | Especifica el modo de unión de líneas a usar en la salida a un dispositivo. |
| SETMITERLIMIT | Establece el límite para la longitud de las uniones en inglete a usar en la salida a un dispositivo. |
| SETPAPERSOURCE | Establece la fuente, como una bandeja de papel o contenedor específico en una impresora, para<br/>                formularios de salida. |
| SETPENWIDTH | Establece el ancho de un lápiz en píxeles. |
| SPCLPASSTHROUGH2 | Permite a las aplicaciones incluir procedimientos privados y otros datos arbitrarios<br/>                en documentos. |
| STARTDOC | Notifica al controlador de la impresora que un nuevo trabajo de impresión está comenzando. |
