---
title: EmfPlusRecordType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración RecordType define los tipos de registros utilizados en los metarchivos EMF.
type: docs
weight: 5030
url: /es/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

La enumeración RecordType define los tipos de registros utilizados en los metarchivos EMF+.

```csharp
public enum EmfPlusRecordType : short
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Este registro especifica el inicio de los datos EMF+ en el metarchivo. DEBE estar incrustado en el primer registro EMF después del[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) registro ([MS-EMF] sección 2.3.4.2 registro). |
| EmfPlusEndOfFile | `16386` | Este registro especifica el final de los datos EMF+ en el metarchivo. |
| EmfPlusComment | `16387` | Este registro especifica datos privados arbitrarios. |
| EmfPlusGetDC | `16388` | Este registro especifica que los registros EMF subsiguientes encontrados en el metarchivo DEBERÍAN procesarse. Los registros EMF dejan de procesarse cuando se encuentra el siguiente registro EMF+. |
| EmfPlusMultiFormatStart | `16389` | Este registro está reservado y NO DEBE usarse. |
| EmfPlusMultiFormatSection | `16390` | Este registro está reservado y NO DEBE usarse. |
| EmfPlusMultiFormatEnd | `16391` | Este registro está reservado y NO DEBE usarse. |
| EmfPlusObject | `16392` | Este registro especifica un objeto para uso en operaciones gráficas. |
| EmfPlusClear | `16393` | Este registro borra la salida`espacio de coordenadas` y lo inicializa con un color de fondo y transparencia específicos. |
| EmfPlusFillRects | `16394` | Este registro define cómo rellenar los interiores de una serie de rectángulos, utilizando un pincel especificado. |
| EmfPlusDrawRects | `16395` | Este registro define los trazos de lápiz para dibujar una serie de rectángulos. |
| EmfPlusFillPolygon | `16396` | Este registro define los datos para rellenar el interior de un polígono, usando un pincel especificado. |
| EmfPlusDrawLines | `16397` | Este registro define los trazos de lápiz para dibujar una serie de líneas conectadas. |
| EmfPlusFillEllipse | `16398` | Este registro define cómo rellenar los interiores de una elipse, usando un pincel especificado. |
| EmfPlusDrawEllipse | `16399` | Este registro define los trazos de pluma para dibujar una elipse. |
| EmfPlusFillPie | `16400` | Este registro define cómo rellenar una sección de una sección interior de una elipse usando un pincel especificado. |
| EmfPlusDrawPie | `16401` | Este registro define trazos de pluma para dibujar una sección de una elipse. |
| EmfPlusDrawArc | `16402` | El registro define trazos de pluma para dibujar un arco de elipse. |
| EmfPlusFillRegion | `16403` | Este registro define cómo rellenar el interior de una región usando un pincel especificado. |
| EmfPlusFillPath | `16404` | El registro define cómo rellenar los interiores de las figuras definidas en una ruta de gráficos con un pincel específico. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas. |
| EmfPlusDrawPath | `16405` | El registro define los trazos de lápiz para dibujar las figuras en una ruta de gráficos. Una ruta es un objeto que define una secuencia arbitraria de líneas, curvas y formas. |
| EmfPlusFillClosedCurve | `16406` | Este registro define cómo rellenar el interior de una spline cardinal cerrada utilizando un pincel especificado. |
| EmfPlusDrawClosedCurve | `16407` | Este registro define la pluma y los trazos para dibujar una spline cardinal cerrada. |
| EmfPlusDrawCurve | `16408` | Este registro define los trazos de lápiz para dibujar una spline cardinal. |
| EmfPlusDrawBeziers | `16409` | Este registro define los trazos de lápiz para dibujar una spline Bezier. |
| EmfPlusDrawImage | `16410` | Este registro define una escala[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)objeto (sección 2.2.1.4). Una imagen puede consistir en datos de mapa de bits o de metarchivo. |
| EmfPlusDrawImagePoints | `16411` | Este registro define un objeto EmfPlusImage escalado dentro de un paralelogramo. Una imagen puede consistir en datos de mapa de bits o de metarchivo. |
| EmfPlusDrawString | `16412` | Este registro define una cadena de texto basada en una fuente, un rectángulo de diseño y un formato. |
| EmfPlusSetRenderingOrigin | `16413` | Este registro define el origen del renderizado en las coordenadas horizontales y verticales especificadas. Esto se aplica a los pinceles de sombreado y a los patrones de tramado de 8 y 16 bits por píxel. |
| EmfPlusSetAntiAliasMode | `16414` | Este registro define si habilitar o deshabilitar el suavizado de texto. El suavizado de texto es un método para suavizar las líneas y los bordes de los glifos de los caracteres cuando se dibujan en una superficie de salida. |
| EmfPlusSetTextRenderingHint | `16415` | Este registro define el proceso utilizado para representar el texto. |
| EmfPlusSetTextContrast | `16416` | Este registro establece el contraste del texto de acuerdo con el valor gamma del texto especificado. |
| EmfPlusSetInterpolationMode | `16417` | Este registro define el modo de interpolación de un objeto según el tipo de filtrado de imagen especificado. El modo de interpolación influye en cómo se realiza el escalado (estiramiento y reducción). |
| EmfPlusSetPixelOffsetMode | `16418` | Este registro define el modo de compensación de píxeles de acuerdo con el valor de centrado de píxeles especificado. |
| EmfPlusSetCompositingMode | `16419` | Este registro define el modo de composición según el estado de fusión alfa, que especifica cómo se combinan los colores de origen con los colores de fondo. |
| EmfPlusSetCompositingQuality | `16420` | Este registro define la calidad de composición, que describe el nivel de calidad deseado para crear imágenes compuestas a partir de varios objetos. |
| EmfPlusSave | `16421` | Este registro guarda el estado de los gráficos, identificado por un índice específico, en una pila de estados de gráficos guardados. Cada índice de pila está asociado con un estado guardado particular, y el índice es utilizado por un[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) registro (sección 2.3.7.4) para restaurar el estado. |
| EmfPlusRestore | `16422` | Este registro restaura el estado de los gráficos, identificado por un índice específico, a partir de una pila de estados de gráficos guardados. Cada índice de pila está asociado con un estado guardado particular, y el índice está definido por un[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) registro (sección 2.3.7.5) para guardar el estado. |
| EmfPlusBeginContainer | `16423` | Este registro abre un nuevo contenedor de estado de gráficos y especifica una transformación para él. Los contenedores de gráficos se utilizan para retener elementos del estado de gráficos. |
| EmfPlusBeginContainerNoParams | `16424` | Este registro abre un nuevo contenedor de estado de gráficos. |
| EmfPlusEndContainer | `16425` | Este registro cierra un contenedor de estado de gráficos que se abrió previamente mediante una operación de inicio de contenedor. |
| EmfPlusSetWorldTransform | `16426` | Este registro define la transformación del espacio mundial actual en el contexto_dispositivo de reproducción, según una matriz de transformación especificada. |
| EmfPlusResetWorldTransform | `16427` | Este registro restablece la transformación del espacio mundial actual a la matriz de identificación. |
| EmfPlusMultiplyWorldTransform | `16428` | Este registro multiplica el espacio mundial actual por una matriz de transformación especificada. |
| EmfPlusTranslateWorldTransform | `16429` | Este registro aplica una transformación de traslación al espacio mundial actual por distancias horizontales y verticales especificadas. |
| EmfPlusScaleWorldTransform | `16430` | Este registro aplica una transformación de escala al espacio mundial actual mediante factores de escala horizontal y vertical especificados. |
| EmfPlusRotateWorldTransform | `16431` | Este registro gira el espacio mundial actual en un ángulo especificado. |
| EmfPlusSetPageTransform | `16432` | Este registro especifica factores de escala adicionales para la transformación del espacio mundial actual. |
| EmfPlusResetClip | `16433` | Este registro restablece la región de recorte actual para el espacio mundial a infinito. |
| EmfPlusSetClipRect | `16434` | Este registro combina la región de recorte actual con un rectángulo. |
| EmfPlusSetClipPath | `16435` | Este registro combina la región de recorte actual con una ruta de gráficos. |
| EmfPlusSetClipRegion | `16436` | Este registro combina la región de recorte actual con otra región gráfica. |
| EmfPlusOffsetClip | `16437` | Este registro aplica una transformación de traducción en la región de recorte actual del espacio mundial. |
| EmfPlusDrawDriverString | `16438` | Este registro especifica la salida de texto con posiciones de caracteres. |
| EmfPlusStrokeFillPath | `16439` | Este registro cierra cualquier figura abierta en un trazado, traza el contorno del trazado con el lápiz actual y rellena su interior con el pincel actual. |
| EmfPlusSerializableObject | `16440` | Este registro define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos. |
| EmfPlusSetTSGraphics | `16441` | Este registro especifica el estado de un contexto de dispositivo de gráficos para un servidor terminal. |
| EmfPlusSetTSClip | `16442` | Este registro especifica áreas de recorte en el contexto del dispositivo de gráficos para un servidor de terminales. |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
