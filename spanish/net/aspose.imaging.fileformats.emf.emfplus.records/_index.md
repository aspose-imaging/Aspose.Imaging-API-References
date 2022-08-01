---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El espacio de nombres contiene tipos MS-EMFPLUS Formato de metarchivo mejorado más extensiones 2.3 Registros EMF
type: docs
weight: 390
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/
---
El espacio de nombres contiene tipos [MS-EMFPLUS]: Formato de metarchivo mejorado más extensiones 2.3 Registros EMF+

## Clases

| Clase | Descripción |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | El registro EmfPlusBeginContainer abre un nuevo contenedor de estado de gráficos y especifica una transformación para él. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | El registro EmfPlusBeginContainerNoParams abre un nuevo contenedor de estado de gráficos. |
| [EmfPlusClear](./emfplusclear) | El registro EmfPlusClear borra el espacio de coordenadas de salida y lo inicializa con un color de fondo y transparencia |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Los tipos de registros de recorte especifican regiones y operaciones de recorte. |
| [EmfPlusComment](./emfpluscomment) | El registro EmfPlusComment especifica datos privados arbitrarios. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Los tipos de registros de control especifican parámetros globales para el procesamiento de metarchivos EMF+. |
| [EmfPlusDrawArc](./emfplusdrawarc) | El registro EmfPlusDrawArc especifica dibujar el arco de una elipse. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | El registro EmfPlusDrawBeziers especifica dibujar una secuencia de curvas Bezier conectadas. El orden de los puntos de datos Bezier es el punto inicial, el punto de control 1, el punto de control 2 y el punto final. Para obtener más información, consulte [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | El registro EmfPlusDrawCurve especifica dibujar una spline cardinal NOTA: ObjectID (1 byte): el índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva. El valor DEBE ser cero a 63, inclusive. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | El registro EmfPlusDrawEllipse especifica dibujar una elipse. |
| [EmfPlusDrawImage](./emfplusdrawimage) | El registro EmfPlusDrawImage especifica dibujar una imagen a escala. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | El registro EmfPlusDrawImagePoints especifica dibujar una imagen a escala dentro de un paralelogramo. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Los tipos de registro de dibujo especifican la salida de gráficos. |
| [EmfPlusDrawLines](./emfplusdrawlines) | El registro EmfPlusDrawlLines especifica dibujar una serie de líneas conectadas |
| [EmfPlusDrawPath](./emfplusdrawpath) | El registro EmfPlusDrawPath especifica dibujar una ruta de gráficos. |
| [EmfPlusDrawPie](./emfplusdrawpie) | El registro EmfPlusDrawPie especifica dibujar una sección del interior de una elipse. |
| [EmfPlusDrawRects](./emfplusdrawrects) | El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos |
| [EmfPlusDrawString](./emfplusdrawstring) | El registro EmfPlusDrawString especifica la salida de texto con formato de cadena |
| [EmfPlusEndContainer](./emfplusendcontainer) | El registro EmfPlusEndContainer cierra un contenedor de estado de gráficos que se abrió previamente mediante una operación de inicio de contenedor. |
| [EmfPlusEndOfFile](./emfplusendoffile) | El registro EmfPlusEndOfFile especifica el final de los datos EMF+ en el metarchivo. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | El registro EmfPlusFillClosedCurve especifica el relleno del interior de una spline cardinal cerrada |
| [EmfPlusFillEllipse](./emfplusfillellipse) | El registro EmfPlusFillEllipse especifica el llenado del interior de una elipse |
| [EmfPlusFillPath](./emfplusfillpath) | Rellenar ruta record FLAGS: Entero sin signo de 16 bits que proporciona información sobre cómo se va a realizar la operación, y sobre la estructura del registro. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 bit): este bit indica el tipo de datos en el campo BrushId. Si se establece, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está claro, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+. X (1 bit): reservado y DEBE ignorarse. ObjectId (1 byte): el índice del objeto EmfPlusPath ( sección 2.2.1.6) para completar, en la tabla de objetos EMF+. El valor DEBE ser cero a 63, inclusive. |
| [EmfPlusFillPie](./emfplusfillpie) | El registro EmfPlusFillPie especifica llenar una sección del interior de una elipse |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | El registro EmfPlusFillPolygon especifica el relleno del interior de un polígono. |
| [EmfPlusFillRects](./emfplusfillrects) | El registro EmfPlusFillRects especifica el relleno de los interiores de una serie de rectángulos |
| [EmfPlusFillRegion](./emfplusfillregion) | El registro EmfPlusFillRegion especifica el relleno del interior de una región gráfica |
| [EmfPlusGetDc](./emfplusgetdc) | El registro EmfPlusGetDC especifica que los registros EMF subsiguientes encontrados en el metarchivo DEBERÍAN procesarse. |
| [EmfPlusHeader](./emfplusheader) | El registro EmfPlusHeader especifica el inicio de los datos EMF+ en el metarchivo. El registro EmfPlusHeader DEBE estar incrustado en un registro EMF EMR_COMMENT_EMFPLUS, que DEBE ser el registro que sigue inmediatamente al encabezado EMF en el metarchivo. El registro EMR_COMMENT_EMFPLUS se especifica en [MS-EMF] sección 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | El registro EmfPlusMultiplyWorldTransform multiplica la transformación del espacio mundial actual por una matriz de transformación especificada . |
| [EmfPlusObject](./emfplusobject) | El registro EmfPlusObject especifica un objeto para usar en operaciones gráficas. La definición del objeto puede abarcar varios registros, lo que se indica mediante el valor del campo Indicadores. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Los tipos de registros de objetos definen objetos gráficos reutilizables. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | El registro EmfPlusOffsetClip aplica una transformación de traducción en la región de recorte actual para el espacio mundial. La nueva región de recorte actual se establece en el resultado de la transformación de traducción. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Los tipos de registros de propiedades especifican las propiedades del contexto del dispositivo de reproducción. |
| [EmfPlusRecord](./emfplusrecord) | El tipo de registro base Emf+. |
| [EmfPlusResetClip](./emfplusresetclip) | El registro EmfPlusResetClip restablece la región de recorte actual para el espacio mundial a infinito. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | El registro EmfPlusResetWorldTransform restablece la transformación del espacio mundial actual a la matriz de identificación. |
| [EmfPlusRestore](./emfplusrestore) | El registro EmfPlusRestore restaura el estado de los gráficos, identificado por un índice específico, a partir de una pila de estados de gráficos guardados. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | El registro EmfPlusRotateWorldTransform realiza una rotación en la transformación del espacio mundial actual. |
| [EmfPlusSave](./emfplussave) | El registro EmfPlusSave guarda el estado de los gráficos, identificado por un índice específico, en una pila de estados de gráficos guardados. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | El registro EmfPlusScaleWorldTransform realiza una escala en la transformación del espacio mundial actual. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | El registro EmfPlusSerializableObject define un bloque de parámetros de efectos de imagen que ha sido serializado en un búfer de datos. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | El registro EmfPlusSetAntiAliasMode especifica el modo suavizado para la salida de texto. |
| [EmfPlusSetClipPath](./emfplussetclippath) | El registro EmfPlusSetClipPath combina la región de recorte actual con una ruta de gráficos. La nueva región de recorte actual se establece en el resultado de la operación CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | El registro EmfPlusSetClipRect combina la región de recorte actual con un rectángulo. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | El registro EmfPlusSetClipRegion combina la región de recorte actual con otra región gráfica. La nueva región de recorte actual se establece como el resultado de realizar la operación CombineMode en la región de recorte actual anterior y el objeto EmfPlusRegion especificado. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | El registro EmfPlusSetCompositingMode especifica cómo se combinan los colores de origen con los colores de fondo. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | El registro EmfPlusSetCompositingQuality especifica el nivel de calidad deseado para crear imágenes compuestas a partir de varios objetos. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | El registro EmfPlusSetInterpolationMode especifica cómo se realiza el escalado de la imagen, incluido el estiramiento y la reducción. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | El registro EmfPlusSetPageTransform especifica factores de escala y unidades para convertir coordenadas de espacio de página en coordenadas de espacio de dispositivo. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | El registro EmfPlusSetPixelOffsetMode especifica cómo se centran los píxeles con respecto a las coordenadas de la superficie de dibujo. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | El registro EmfPlusSetRenderingOrigin especifica el origen de representación para la salida de gráficos. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | El registro EmfPlusSetTextContrast especifica el contraste del texto según el valor de corrección gamma. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | El registro EmfPlusSetTextRenderingHint especifica la calidad de la representación del texto, incluido el tipo de suavizado. |
| [EmfPlusSetTsClip](./emfplussettsclip) | El registro EmfPlusSetTSClip especifica áreas de recorte en el contexto del dispositivo de gráficos para un servidor terminal. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo de gráficos para un servidor terminal. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | El registro EmfPlusSetWorldTransform establece la transformación mundial de acuerdo con los valores en una matriz de transformación especificada . |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | Los tipos de registro de estado especifican operaciones en el estado del contexto del dispositivo de reproducción. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Los tipos de registro de servidor de terminal especifican el procesamiento de gráficos en un servidor de terminal. Los siguientes son tipos de registro de servidor de terminal EMF+. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Los tipos de registros de transformación especifican propiedades y transformaciones en espacios de coordenadas. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | El registro EmfPlusTranslateWorldTransform realiza una traducción en la transformación del espacio mundial actual. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
