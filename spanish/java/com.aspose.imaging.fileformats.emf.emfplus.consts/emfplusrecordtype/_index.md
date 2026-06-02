---
title: "EmfPlusRecordType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración RecordType define tipos de registro utilizados en metarchivos EMF."
type: docs
weight: 45
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

La enumeración RecordType define los tipos de registro utilizados en los metarchivos EMF+.
## Campos

| Campo | Descripción |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Este registro especifica el inicio de los datos EMF+ en el metarchivo. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Este registro especifica el final de los datos EMF+ en el metarchivo. |
| [EmfPlusComment](#EmfPlusComment) | Este registro especifica datos privados arbitrarios. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Este registro especifica que los registros EMF posteriores encontrados en el metarchivo DEBERÍAN ser procesados. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Este registro está reservado y NO DEBE ser utilizado. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Este registro está reservado y NO DEBE ser utilizado. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Este registro está reservado y NO DEBE ser utilizado. |
| [EmfPlusObject](#EmfPlusObject) | Este registro especifica un objeto para su uso en operaciones gráficas. |
| [EmfPlusClear](#EmfPlusClear) | Este registro borra el `coordinate space` de salida y lo inicializa con un color de fondo y transparencia especificados. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Este registro define cómo rellenar los interiores de una serie de rectángulos, usando un pincel especificado. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Este registro define los trazos de la pluma para dibujar una serie de rectángulos. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Este registro define los datos para rellenar el interior de un polígono, usando un pincel especificado. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Este registro define los trazos de la pluma para dibujar una serie de líneas conectadas. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Este registro define cómo rellenar los interiores de una elipse, usando un pincel especificado. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Este registro define los trazos de la pluma para dibujar una elipse. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Este registro define cómo rellenar una sección interior de una elipse usando un pincel especificado. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Este registro define los trazos de lápiz para dibujar una sección de una elipse. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | El registro define los trazos de lápiz para dibujar un arco de una elipse. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Este registro define cómo rellenar el interior de una región usando un pincel especificado. |
| [EmfPlusFillPath](#EmfPlusFillPath) | El registro define cómo rellenar los interiores de las figuras definidas en una ruta gráfica con un pincel especificado. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | El registro define los trazos de lápiz para dibujar las figuras en una ruta gráfica. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Este registro define cómo rellenar el interior de una spline cardinal cerrada usando un pincel especificado. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Este registro define el lápiz y los trazos para dibujar una spline cardinal cerrada. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Este registro define los trazos de lápiz para dibujar una spline cardinal. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Este registro define los trazos de lápiz para dibujar una spline Bézier. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Este registro define un objeto [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) escalado (sección 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Este registro define un objeto EmfPlusImage escalado dentro de un paralelogramo. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Este registro define una cadena de texto basada en una fuente, un rectángulo de diseño y un formato. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Este registro define el origen del renderizado a las coordenadas horizontales y verticales especificadas. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Este registro define si habilitar o deshabilitar el antialiasing de texto. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Este registro define el proceso utilizado para renderizar texto. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Este registro establece el contraste del texto según el valor gamma de texto especificado. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Este registro define el modo de interpolación de un objeto según el tipo de filtrado de imagen especificado. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Este registro define el modo de desplazamiento de píxeles según el valor de centrado de píxeles especificado. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Este registro define el modo de composición según el estado de la mezcla alfa, que especifica cómo se combinan los colores de origen con los colores de fondo. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Este registro define la calidad de composición, que describe el nivel deseado de calidad para crear imágenes compuestas a partir de varios objetos. |
| [EmfPlusSave](#EmfPlusSave) | Este registro guarda el estado gráfico, identificado por un índice especificado, en una pila de estados gráficos guardados. |
| [EmfPlusRestore](#EmfPlusRestore) | Este registro restaura el estado gráfico, identificado por un índice especificado, desde una pila de estados gráficos guardados. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Este registro abre un nuevo contenedor de estado gráfico y especifica una transformación para él. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Este registro abre un nuevo contenedor de estado gráfico. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Este registro cierra un contenedor de estado gráfico que se abrió previamente mediante una operación de inicio de contenedor. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Este registro define la transformación del espacio mundial actual en el playback device\_context, según una matriz de transformación especificada. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Este registro restablece la transformación del espacio mundial actual a la matriz de identidad. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Este registro multiplica el espacio mundial actual por una matriz de transformación especificada. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Este registro aplica una transformación de traslación al espacio mundial actual mediante distancias horizontales y verticales especificadas. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Este registro aplica una transformación de escala al espacio mundial actual mediante factores de escala horizontales y verticales especificados. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Este registro rota el espacio mundial actual un ángulo especificado. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Este registro especifica factores de escala adicionales para la transformación del espacio mundial actual. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Este registro restablece la región de recorte actual del espacio mundial a infinito. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Este registro combina la región de recorte actual con un rectángulo. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Este registro combina la región de recorte actual con una ruta gráfica. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Este registro combina la región de recorte actual con otra región gráfica. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Este registro aplica una transformación de traslación en la región de recorte actual del espacio mundial. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Este registro especifica la salida de texto con posiciones de caracteres. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando la pluma actual y rellena su interior usando el pincel actual. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Este registro define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Este registro especifica el estado de un contexto de dispositivo gráfico para un servidor terminal. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Este registro especifica áreas de recorte en el contexto de dispositivo gráfico para un servidor terminal. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Este registro especifica el inicio de los datos EMF+ en el metafile. DEBE estar incrustado en el primer registro EMF después del registro [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] sección 2.3.4.2 registro).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Este registro especifica el final de los datos EMF+ en el metarchivo.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Este registro especifica datos privados arbitrarios.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Este registro especifica que los registros EMF posteriores encontrados en el metafile DEBERÍAN ser procesados. Los registros EMF dejan de procesarse cuando se encuentra el siguiente registro EMF+.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Este registro está reservado y NO DEBE ser utilizado.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Este registro está reservado y NO DEBE ser utilizado.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Este registro está reservado y NO DEBE ser utilizado.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Este registro especifica un objeto para su uso en operaciones gráficas.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Este registro borra el `coordinate space` de salida y lo inicializa con un color de fondo y transparencia especificados.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Este registro define cómo rellenar los interiores de una serie de rectángulos, usando un pincel especificado.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Este registro define los trazos de la pluma para dibujar una serie de rectángulos.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Este registro define los datos para rellenar el interior de un polígono, usando un pincel especificado.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Este registro define los trazos de la pluma para dibujar una serie de líneas conectadas.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Este registro define cómo rellenar los interiores de una elipse, usando un pincel especificado.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Este registro define los trazos de la pluma para dibujar una elipse.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Este registro define cómo rellenar una sección interior de una elipse usando un pincel especificado.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Este registro define los trazos de lápiz para dibujar una sección de una elipse.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


El registro define los trazos de lápiz para dibujar un arco de una elipse.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Este registro define cómo rellenar el interior de una región usando un pincel especificado.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


El registro define cómo rellenar los interiores de las figuras definidas en una ruta gráfica con un pincel especificado. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


El registro define los trazos de la pluma para dibujar las figuras en una ruta gráfica. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Este registro define cómo rellenar el interior de una spline cardinal cerrada usando un pincel especificado.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Este registro define el lápiz y los trazos para dibujar una spline cardinal cerrada.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Este registro define los trazos de lápiz para dibujar una spline cardinal.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Este registro define los trazos de lápiz para dibujar una spline Bézier.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Este registro define un objeto [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) escalado (sección 2.2.1.4). Una imagen puede consistir en datos de mapa de bits o de metafile.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Este registro define un objeto EmfPlusImage escalado dentro de un paralelogramo. Una imagen puede consistir en datos de mapa de bits o de metafile.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Este registro define una cadena de texto basada en una fuente, un rectángulo de diseño y un formato.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Este registro define el origen de renderizado a las coordenadas horizontales y verticales especificadas. Esto se aplica a los pinceles de trama y a los patrones de tramado de 8 y 16 bits por píxel.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Este registro define si habilitar o deshabilitar el antialiasing de texto. El antialiasing de texto es un método para que las líneas y bordes de los glifos de caracteres aparezcan más suaves al dibujarse en una superficie de salida.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Este registro define el proceso utilizado para renderizar texto.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Este registro establece el contraste del texto según el valor gamma de texto especificado.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Este registro define el modo de interpolación de un objeto según el tipo especificado de filtrado de imagen. El modo de interpolación influye en cómo se realiza el escalado (estiramiento y reducción).

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Este registro define el modo de desplazamiento de píxeles según el valor de centrado de píxeles especificado.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Este registro define el modo de composición según el estado de la mezcla alfa, que especifica cómo se combinan los colores de origen con los colores de fondo.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Este registro define la calidad de composición, que describe el nivel deseado de calidad para crear imágenes compuestas a partir de varios objetos.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Este registro guarda el estado gráfico, identificado por un índice especificado, en una pila de estados gráficos guardados. Cada índice de la pila está asociado a un estado guardado particular, y el índice es usado por un registro [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (sección 2.3.7.4) para restaurar el estado.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Este registro restaura el estado gráfico, identificado por un índice especificado, de una pila de estados gráficos guardados. Cada índice de la pila está asociado a un estado guardado particular, y el índice es definido por un registro [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (sección 2.3.7.5) para guardar el estado.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Este registro abre un nuevo contenedor de estado gráfico y especifica una transformación para él. Los contenedores gráficos se utilizan para retener elementos del estado gráfico.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Este registro abre un nuevo contenedor de estado gráfico.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Este registro cierra un contenedor de estado gráfico que se abrió previamente mediante una operación de inicio de contenedor.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Este registro define la transformación del espacio mundial actual en el playback device\_context, según una matriz de transformación especificada.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Este registro restablece la transformación del espacio mundial actual a la matriz de identidad.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Este registro multiplica el espacio mundial actual por una matriz de transformación especificada.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Este registro aplica una transformación de traslación al espacio mundial actual mediante distancias horizontales y verticales especificadas.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Este registro aplica una transformación de escala al espacio mundial actual mediante factores de escala horizontales y verticales especificados.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Este registro rota el espacio mundial actual un ángulo especificado.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Este registro especifica factores de escala adicionales para la transformación del espacio mundial actual.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Este registro restablece la región de recorte actual del espacio mundial a infinito.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Este registro combina la región de recorte actual con un rectángulo.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Este registro combina la región de recorte actual con una ruta gráfica.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Este registro combina la región de recorte actual con otra región gráfica.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Este registro aplica una transformación de traslación en la región de recorte actual del espacio mundial.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Este registro especifica la salida de texto con posiciones de caracteres.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Este registro cierra cualquier figura abierta en una ruta, traza el contorno de la ruta usando la pluma actual y rellena su interior usando el pincel actual.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Este registro define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Este registro especifica el estado de un contexto de dispositivo gráfico para un servidor terminal.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Este registro especifica áreas de recorte en el contexto de dispositivo gráfico para un servidor terminal.

