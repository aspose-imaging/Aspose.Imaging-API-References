---
title: "WmfMetafileEscapes"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración MetafileEscapes especifica la funcionalidad del controlador de impresora que podría no estar directamente accesible a través de los registros WMF definidos en la enumeración RecordType sección 2.1.1.1."
type: docs
weight: 24
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

La enumeración MetafileEscapes especifica la funcionalidad del controlador de impresora que podría no ser accesible directamente a través de los registros WMF definidos en la enumeración RecordType (sección 2.1.1.1).
## Campos

| Campo | Descripción |
| --- | --- |
| [Newframe](#Newframe) | Notifica al controlador de impresora que la aplicación ha terminado de escribir en una página. |
| [Abortdoc](#Abortdoc) | Detiene el procesamiento del documento actual. |
| [Nextband](#Nextband) | Notifica al controlador de impresora que la aplicación ha terminado de escribir en una banda. |
| [Setcolortable](#Setcolortable) | Establece los valores de la tabla de colores. |
| [Getcolortable](#Getcolortable) | Obtiene los valores de la tabla de colores. |
| [Flushout](#Flushout) | Hace que toda la salida pendiente se vacíe al dispositivo de salida. |
| [Draftmode](#Draftmode) | Indica que el controlador de impresora DEBERÍA imprimir solo texto y no gráficos. |
| [Queryescsupport](#Queryescsupport) | Consulta al controlador de impresora para determinar si una función de escape específica es compatible con el dispositivo de salida que controla. |
| [Setabortproc](#Setabortproc) | Establece la función definida por la aplicación que permite cancelar un trabajo de impresión durante la impresión. |
| [Startdoc](#Startdoc) | Notifica al controlador de impresora que un nuevo trabajo de impresión está comenzando. |
| [Enddoc](#Enddoc) | Notifica al controlador de impresora que el trabajo de impresión actual está finalizando. |
| [Getphyspagesize](#Getphyspagesize) | Recupera el tamaño físico de página actualmente seleccionado en un dispositivo de salida. |
| [Getprintingoffset](#Getprintingoffset) | Recupera el desplazamiento desde la esquina superior izquierda de la página física donde comienza la impresión o el dibujo real. |
| [Getscalingfactor](#Getscalingfactor) | Recupera los factores de escala para el eje x y el eje y de una impresora. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Se utiliza para incrustar un metafile de formato mejorado (EMF) dentro de un metafile WMF. |
| [Setpenwidth](#Setpenwidth) | Establece el ancho de un lápiz en píxeles. |
| [Setcopycount](#Setcopycount) | Establece el número de copias. |
| [Setpapersource](#Setpapersource) | Establece el origen, como una bandeja de papel o contenedor particular en una impresora, para los formularios de salida. |
| [Passthrough](#Passthrough) | Este registro pasa datos arbitrarios. |
| [Gettechnology](#Gettechnology) | Obtiene información sobre la tecnología gráfica que es compatible con un dispositivo. |
| [Setlinecap](#Setlinecap) | Especifica el modo de dibujo de líneas a usar en la salida a un dispositivo. |
| [Setlinejoin](#Setlinejoin) | Especifica el modo de unión de líneas a usar en la salida a un dispositivo. |
| [Setmiterlimit](#Setmiterlimit) | Establece el límite para la longitud de las uniones en inglete a usar en la salida a un dispositivo. |
| [Bandinfo](#Bandinfo) | Recupera o especifica la configuración relacionada con el banding en un dispositivo, como el número de bandas. |
| [Drawpatternrect](#Drawpatternrect) | Dibuja un rectángulo con un patrón definido. |
| [Getvectorpensize](#Getvectorpensize) | Recupera el tamaño físico del lápiz actualmente definido en un dispositivo. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Recupera el tamaño físico del pincel actualmente definido en un dispositivo. |
| [Enableduplex](#Enableduplex) | Habilita o deshabilita la impresión a doble cara (dúplex) en un dispositivo. |
| [Getsetpaperbins](#Getsetpaperbins) | Recupera o especifica la fuente de formularios de salida en un dispositivo. |
| [Getsetprintorient](#Getsetprintorient) | Recupera o especifica la orientación del papel en un dispositivo. |
| [Enumpaperbins](#Enumpaperbins) | Recupera información sobre las fuentes de diferentes formularios en un dispositivo de salida. |
| [Setdibscaling](#Setdibscaling) | Especifica el escalado de mapas de bits independientes del dispositivo (DIBs). |
| [Epsprinting](#Epsprinting) | Indica el inicio y el final de una sección PostScript encapsulada (EPS). |
| [Enumpapermetrics](#Enumpapermetrics) | Consulta al controlador de impresora las dimensiones del papel y otros datos de formularios. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Recupera o especifica las dimensiones del papel y otros datos de formularios en un dispositivo de salida. |
| [PostscriptData](#PostscriptData) | Envía datos PostScript arbitrarios a un dispositivo de salida. |
| [PostscriptIgnore](#PostscriptIgnore) | Notifica a un dispositivo de salida que ignore los datos PostScript. |
| [Getdeviceunits](#Getdeviceunits) | Obtiene las unidades del dispositivo actualmente configuradas en un dispositivo de salida. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Obtiene métricas de texto extendidas actualmente configuradas en un dispositivo de salida. |
| [Getpairkerntable](#Getpairkerntable) | Obtiene la tabla de kerning de fuentes actualmente definida en un dispositivo de salida. |
| [Exttextout](#Exttextout) | Dibuja texto usando la fuente seleccionada actualmente, el color de fondo y el color del texto. |
| [Getfacename](#Getfacename) | Obtiene el nombre del tipo de fuente actualmente configurado en un dispositivo. |
| [Downloadface](#Downloadface) | Establece el nombre del tipo de fuente en un dispositivo. |
| [MetafileDriver](#MetafileDriver) | Consulta al controlador de impresora sobre el soporte de metarchivos en un dispositivo de salida. |
| [Querydibsupport](#Querydibsupport) | Consulta al controlador de impresora sobre su soporte para DIBs en un dispositivo de salida. |
| [BeginPath](#BeginPath) | Abre una ruta. |
| [ClipToPath](#ClipToPath) | Define una región de recorte delimitada por una ruta. |
| [EndPath](#EndPath) | Finaliza una ruta. |
| [OpenChannel](#OpenChannel) | Lo mismo que STARTDOC especificado con un documento NULL y nombre de archivo de salida, datos en modo crudo y un tipo cero. |
| [Downloadheader](#Downloadheader) | Indica al controlador de la impresora que descargue conjuntos de procedimientos PostScript. |
| [CloseChannel](#CloseChannel) | Lo mismo que ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Envía datos arbitrarios directamente al controlador de la impresora, que se espera procese estos datos solo cuando esté en modo PostScript. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Envía datos arbitrarios directamente al controlador de la impresora. |
| [PostscriptIdentify](#PostscriptIdentify) | Configura el controlador de la impresora en modo PostScript o GDI. |
| [PostscriptInjection](#PostscriptInjection) | Inserta un bloque de datos crudos en un flujo PostScript. |
| [Checkjpegformat](#Checkjpegformat) | Comprueba si la impresora admite una imagen JPEG. |
| [Checkpngformat](#Checkpngformat) | Comprueba si la impresora admite una imagen PNG. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Obtiene información sobre una configuración de característica especificada para un controlador de impresora PostScript. |
| [MxdcEscape](#MxdcEscape) | Permite a las aplicaciones escribir documentos en un archivo o en una impresora en formato XML Paper Specification (XPS). |
| [Spclpassthrough2](#Spclpassthrough2) | Permite a las aplicaciones incluir procedimientos privados y otros datos arbitrarios en los documentos. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Notifica al controlador de impresora que la aplicación ha terminado de escribir en una página.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Detiene el procesamiento del documento actual.

### Nextband {#Nextband}
```
public static final int Nextband
```


Notifica al controlador de impresora que la aplicación ha terminado de escribir en una banda.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Establece los valores de la tabla de colores.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Obtiene los valores de la tabla de colores.

### Flushout {#Flushout}
```
public static final int Flushout
```


Hace que toda la salida pendiente se vacíe al dispositivo de salida.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Indica que el controlador de impresora DEBERÍA imprimir solo texto y no gráficos.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Consulta al controlador de impresora para determinar si una función de escape específica es compatible con el dispositivo de salida que controla.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Establece la función definida por la aplicación que permite cancelar un trabajo de impresión durante la impresión.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Notifica al controlador de impresora que un nuevo trabajo de impresión está comenzando.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Notifica al controlador de impresora que el trabajo de impresión actual está finalizando.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Recupera el tamaño físico de página actualmente seleccionado en un dispositivo de salida.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Recupera el desplazamiento desde la esquina superior izquierda de la página física donde comienza la impresión o el dibujo real.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Recupera los factores de escala para el eje x y el eje y de una impresora.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Se utiliza para incrustar un metafile de formato mejorado (EMF) dentro de un metafile WMF.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Establece el ancho de un lápiz en píxeles.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Establece el número de copias.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Establece el origen, como una bandeja de papel o contenedor particular en una impresora, para los formularios de salida.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Este registro pasa datos arbitrarios.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Obtiene información sobre la tecnología gráfica que es compatible con un dispositivo.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Especifica el modo de dibujo de líneas a usar en la salida a un dispositivo.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Especifica el modo de unión de líneas a usar en la salida a un dispositivo.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Establece el límite para la longitud de las uniones en inglete a usar en la salida a un dispositivo.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Recupera o especifica la configuración relacionada con el banding en un dispositivo, como el número de bandas.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Dibuja un rectángulo con un patrón definido.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Recupera el tamaño físico del lápiz actualmente definido en un dispositivo.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Recupera el tamaño físico del pincel actualmente definido en un dispositivo.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Habilita o deshabilita la impresión a doble cara (dúplex) en un dispositivo.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Recupera o especifica la fuente de formularios de salida en un dispositivo.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Recupera o especifica la orientación del papel en un dispositivo.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Recupera información sobre las fuentes de diferentes formularios en un dispositivo de salida.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Especifica el escalado de mapas de bits independientes del dispositivo (DIBs).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Indica el inicio y el final de una sección PostScript encapsulada (EPS).

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Consulta al controlador de impresora las dimensiones del papel y otros datos de formularios.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Recupera o especifica las dimensiones del papel y otros datos de formularios en un dispositivo de salida.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Envía datos PostScript arbitrarios a un dispositivo de salida.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Notifica a un dispositivo de salida que ignore los datos PostScript.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Obtiene las unidades del dispositivo actualmente configuradas en un dispositivo de salida.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Obtiene métricas de texto extendidas actualmente configuradas en un dispositivo de salida.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Obtiene la tabla de kerning de fuentes actualmente definida en un dispositivo de salida.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Dibuja texto usando la fuente seleccionada actualmente, el color de fondo y el color del texto.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Obtiene el nombre del tipo de fuente actualmente configurado en un dispositivo.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Establece el nombre del tipo de fuente en un dispositivo.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Consulta al controlador de impresora sobre el soporte de metarchivos en un dispositivo de salida.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Consulta al controlador de impresora sobre su soporte para DIBs en un dispositivo de salida.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Abre una ruta.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Define una región de recorte delimitada por una ruta. La entrada DEBE ser una cantidad de 16 bits que define la acción a realizar.

### EndPath {#EndPath}
```
public static final int EndPath
```


Finaliza una ruta.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


Lo mismo que STARTDOC especificado con un documento NULL y nombre de archivo de salida, datos en modo crudo y un tipo cero.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Indica al controlador de la impresora que descargue conjuntos de procedimientos PostScript.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


Lo mismo que ENDDOC. Ver OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Envía datos arbitrarios directamente al controlador de la impresora, que se espera procese estos datos solo cuando esté en modo PostScript. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Envía datos arbitrarios directamente al controlador de la impresora.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Configura el controlador de la impresora en modo PostScript o GDI.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Inserta un bloque de datos crudos en un flujo PostScript. La entrada DEBE ser una cantidad de 32 bits que especifica el número de bytes a inyectar, una cantidad de 16 bits que especifica el punto de inyección y una cantidad de 16 bits que especifica el número de página, seguida de los bytes a inyectar.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Comprueba si la impresora admite una imagen JPEG.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Comprueba si la impresora admite una imagen PNG.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Obtiene información sobre una configuración de característica especificada para un controlador de impresora PostScript.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Permite a las aplicaciones escribir documentos en un archivo o en una impresora en formato XML Paper Specification (XPS).

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Permite a las aplicaciones incluir procedimientos privados y otros datos arbitrarios en los documentos.

