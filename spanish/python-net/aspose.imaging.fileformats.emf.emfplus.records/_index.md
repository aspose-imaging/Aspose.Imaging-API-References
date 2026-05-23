---
title: "aspose.imaging.fileformats.emf.emfplus.records"
type: docs
weight: 440
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/
---


El módulo contiene tipos [MS-EMFPLUS]: Extensiones del Formato Metarchivo Mejorado Plus 2.3 Registros EMF+

## **Classes**
| **Clase** | **Descripción** |
| :- | :- |
| [EmfPlusBeginContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/) | El registro EmfPlusBeginContainer abre un nuevo contenedor de estado gráfico y especifica una transformación para él. |
| [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) | El registro EmfPlusBeginContainerNoParams abre un nuevo contenedor de estado gráfico. |
| [EmfPlusClear](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/) | El registro EmfPlusClear borra el espacio de coordenadas de salida y lo inicializa con un color de fondo y transparencia |
| [EmfPlusClippingRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype/) | Los tipos de registro de recorte especifican regiones de recorte y operaciones. |
| [EmfPlusComment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/) | El registro EmfPlusComment especifica datos privados arbitrarios. |
| [EmfPlusControlRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype/) | Los tipos de registro de control especifican parámetros globales para el procesamiento de metarchivos EMF+. |
| [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) | El registro EmfPlusDrawArc especifica el dibujo del arco de una elipse. |
| [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) | El registro EmfPlusDrawBeziers especifica el dibujo de una secuencia de curvas Bézier conectadas. <br/>            El orden de los puntos de datos Bézier es el punto inicial, punto de control 1, <br/>            punto de control 2 y punto final. Para obtener más información, consulte [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) | El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada |
| [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) | El registro EmfPlusDrawCurve especifica dibujar una spline cardinal<br/>            NOTA: ObjectID (1 byte): El índice de un objeto EmfPlusPen (sección 2.2.1.7)<br/>             en la tabla de objetos EMF+ para dibujar la curva. El valor DEBE ser de 0 a 63, inclusive. |
| [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) | El registro EmfPlusDrawDriverString especifica la salida de texto con posiciones de caracteres. |
| [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) | El registro EmfPlusDrawEllipse especifica dibujar una elipse. |
| [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) | El registro EmfPlusDrawImage especifica dibujar una imagen escalada. |
| [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) | El registro EmfPlusDrawImagePoints especifica dibujar una imagen escalada dentro de un paralelogramo. |
| [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) | El registro EmfPlusDrawlLines especifica dibujar una serie de líneas conectadas |
| [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) | El registro EmfPlusDrawPath especifica dibujar una ruta gráfica. |
| [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) | El registro EmfPlusDrawPie especifica dibujar una sección del interior de una elipse. |
| [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) | El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos |
| [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) | El registro EmfPlusDrawString especifica la salida de texto con formato de cadena |
| [EmfPlusDrawingRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype/) | Los tipos de registro de dibujo especifican la salida gráfica. |
| [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/) | El registro EmfPlusEndContainer cierra un contenedor de estado gráfico que fue previamente abierto mediante una operación de inicio de contenedor. |
| [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/) | El registro EmfPlusEndOfFile especifica el final de los datos EMF+ en el metafichero. |
| [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) | El registro EmfPlusFillClosedCurve especifica rellenar el interior de una spline cardinal cerrada |
| [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/) | El registro EmfPlusFillEllipse especifica rellenar el interior de una elipse |
| [EmfPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/) | Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X | ObjectId | <br/>            S (1 bit): Este bit indica el tipo de datos en el campo BrushId.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está despejado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.<br/>            X (1 bit): Reservado y DEBE ser ignorado.<br/>            ObjectId (1 byte): El índice del objeto EmfPlusPath (sección 2.2.1.6) a rellenar, en la tabla de objetos EMF+. El valor DEBE ser de 0 a 63, inclusive. |
| [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/) | El registro EmfPlusFillPie especifica rellenar una sección del interior de una elipse |
| [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) | El registro EmfPlusFillPolygon especifica rellenar el interior de un polígono. |
| [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) | El registro EmfPlusFillRects especifica rellenar los interiores de una serie de rectángulos |
| [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) | El registro EmfPlusFillRegion especifica rellenar el interior de una región gráfica |
| [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/) | El registro EmfPlusGetDC especifica que los registros EMF subsecuentes encontrados en el metafichero DEBERÍAN ser procesados. |
| [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) | El registro EmfPlusHeader especifica el inicio de los datos EMF+ en el metafichero.<br/>            El registro EmfPlusHeader DEBE estar incrustado en un registro EMF EMR_COMMENT_EMFPLUS,<br/>             que DEBE ser el registro que sigue inmediatamente al encabezado EMF en el metafichero. <br/>            El registro EMR_COMMENT_EMFPLUS se especifica en la sección 2.3.3.2 de [MS-EMF]. |
| [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) | El registro EmfPlusMultiplyWorldTransform multiplica la transformación del espacio mundial actual por una<br/>            matriz de transformación especificada. |
| [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/) | El registro EmfPlusObject especifica un objeto para su uso en operaciones gráficas. La definición del objeto<br/>            puede abarcar varios registros, lo que se indica con el valor del campo Flags. |
| [EmfPlusObjectRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype/) | Los tipos de registro de objeto definen objetos gráficos reutilizables. |
| [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/) | El registro EmfPlusOffsetClip aplica una transformación de traslación en la región de recorte actual para el espacio mundial.<br/>
            La nueva región de recorte actual se establece al resultado de la transformación de traslación. |
| [EmfPlusPropertyRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype/) | Los tipos de registro de propiedad especifican propiedades del contexto del dispositivo de reproducción. |
| [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | El tipo de registro base Emf+. |
| [EmfPlusResetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/) | El registro EmfPlusResetClip restablece la región de recorte actual para el espacio mundial a infinito. |
| [EmfPlusResetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetworldtransform/) | El registro EmfPlusResetWorldTransform restablece la transformación del espacio mundial actual a la matriz de identidad. |
| [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) | El registro EmfPlusRestore restaura el estado gráfico, identificado por un índice especificado, desde una pila de estados gráficos guardados. |
| [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/) | El registro EmfPlusRotateWorldTransform realiza una rotación en la transformación del espacio mundial actual. |
| [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) | El registro EmfPlusSave guarda el estado gráfico, identificado por un índice especificado, en una pila de estados gráficos guardados. |
| [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) | El registro EmfPlusScaleWorldTransform realiza un escalado en la transformación del espacio mundial actual. |
| [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/) | El registro EmfPlusSerializableObject define un bloque de parámetros de efectos de imagen que ha sido<br/>
            serializado en un búfer de datos. |
| [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) | El registro EmfPlusSetAntiAliasMode especifica el modo de anti-aliasing para la salida de texto. |
| [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) | El registro EmfPlusSetClipPath combina la región de recorte actual con una ruta gráfica.<br/>
            La nueva región de recorte actual se establece al resultado de la operación CombineMode. |
| [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/) | El registro EmfPlusSetClipRect combina la región de recorte actual con un rectángulo. |
| [EmfPlusSetClipRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/) | El registro EmfPlusSetClipRegion combina la región de recorte actual con otra región gráfica.<br/>
            La nueva región de recorte actual se establece al resultado de ejecutar la operación CombineMode sobre<br/>
            la región de recorte actual anterior y el objeto EmfPlusRegion especificado. |
| [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) | El registro EmfPlusSetCompositingMode especifica cómo se combinan los colores de origen con los colores de fondo. |
| [EmfPlusSetCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingquality/) | El registro EmfPlusSetCompositingQuality especifica el nivel deseado de calidad para crear<br/>
            imágenes compuestas a partir de múltiples objetos. |
| [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) | El registro EmfPlusSetInterpolationMode especifica cómo se realiza el escalado de imágenes, incluyendo estiramiento y reducción. |
| [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/) | El registro EmfPlusSetPageTransform especifica los factores de escala y unidades para convertir coordenadas del espacio de página<br/>
            a coordenadas del espacio del dispositivo. |
| [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/) | El registro EmfPlusSetPixelOffsetMode especifica cómo se centran los píxeles con respecto a las<br/>
            coordenadas de la superficie de dibujo. |
| [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) | El registro EmfPlusSetRenderingOrigin especifica el origen de renderizado para la salida gráfica. |
| [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/) | El registro EmfPlusSetTextContrast especifica el contraste de texto según el valor de corrección gamma. |
| [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) | El registro EmfPlusSetTextRenderingHint especifica la calidad del renderizado de texto, incluido el tipo de anti-aliasing. |
| [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) | El registro EmfPlusSetTSClip especifica áreas de recorte en el contexto del dispositivo gráfico para un servidor de terminal. |
| [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) | El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo gráfico para un servidor de terminal. |
| [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) | El registro EmfPlusSetWorldTransform establece la transformación mundial según los valores en una<br/>            matriz de transformación especificada. |
| [EmfPlusStateRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype/) | Los tipos de registro de estado especifican operaciones sobre el estado del contexto del dispositivo de reproducción. |
| [EmfPlusTerminalServerRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype/) | Los tipos de registro del servidor terminal especifican el procesamiento gráfico en un servidor terminal. Los siguientes<br/>            son tipos de registro de servidor terminal EMF+. |
| [EmfPlusTransformRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustransformrecordtype/) | Los tipos de registro de transformación especifican propiedades y transformaciones en espacios de coordenadas. |
| [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/) | El registro EmfPlusTranslateWorldTransform realiza una traslación en la transformación del espacio mundial actual. |
