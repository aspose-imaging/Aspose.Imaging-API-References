---
title: "Clase EmfText"
type: docs
weight: 260
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfText()](#EmfText__1) | Inicializa una nueva instancia de la clase EmfText |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| chars | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la cadena |
| dx_buffer | int[] | r/w | Obtiene o establece el búfer opcional de espaciado de caracteres<br/>            UndefinedSpace2 (variable): Un número opcional de bytes sin usar. No se requiere que el campo OutputDx <br/>            siga inmediatamente a la porción precedente de esta estructura.<br/>            OutputDx (variable): Una matriz de enteros sin signo de 32 bits que especifica el espaciado de salida entre <br/>            los orígenes de celdas de caracteres adyacentes en unidades lógicas. La ubicación de este campo se especifica por <br/>            el valor de offDx en bytes desde el inicio de este registro. Si el espaciado está definido, este campo contiene <br/>            la misma cantidad de valores que caracteres hay en la cadena de salida. Si el campo Options del objeto EmrText <br/>            contiene la bandera ETO_PDY, entonces este búfer contiene el doble de valores que hay caracteres en <br/>            la cadena de salida, un desplazamiento horizontal y uno vertical para cada uno, en ese orden. Si se especifica ETO_RTLREADING, <br/>            los caracteres se disponen de derecha a izquierda en lugar de izquierda a derecha. Ninguna otra opción afecta la interpretación de este campo. |
| glyph_index_buffer | int[] | r/w | Obtiene o establece el búfer opcional de índices de glifos.<br/>            Si las opciones tienen la bandera ETO_GLYPH_INDEX, entonces los códigos de los caracteres en una cadena de texto de salida son en realidad índices<br/>            de los glifos de los caracteres en una fuente TrueType (enumeración ExtTextOutOptions 2.1.11). Los índices de glifos son específicos de la fuente,<br/>            por lo que para mostrar los caracteres correctos durante la reproducción, la fuente que se utiliza DEBE ser idéntica a la fuente usada para<br/>            generar los índices. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo usar el rectángulo especificado en el <br/>            campo Rectangle. Este campo puede ser una combinación de más de un valor de la enumeración ExtTextOutOptions <br/>            (sección 2.1.11). |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL opcional ([MS-WMF] sección 2.2.2.19) que define un rectángulo de recorte <br/>            y/o opacidad en unidades lógicas. Este rectángulo se aplica a la salida de texto <br/>            realizada por el registro contenedor. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece un objeto WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica las coordenadas del <br/>            punto de referencia utilizado para posicionar la cadena. El punto de referencia se define mediante el último <br/>            registro EMR_SETTEXTALIGN (sección 2.3.11.25). Si no se ha establecido dicho registro, <br/>            la alineación predeterminada es TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Obtiene o establece el búfer de cadena de caracteres<br/>            UndefinedSpace1 (variable): Un número opcional de bytes sin usar. <br/>            No se requiere que el campo OutputString siga inmediatamente a la porción precedente de esta estructura.<br/>            OutputString (variable): Una matriz de caracteres que especifica la cadena a emitir. <br/>            La ubicación de este campo se especifica por el valor de offString en bytes desde el inicio de este registro. <br/>            El número de caracteres se especifica mediante el valor de Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Inicializa una nueva instancia de la clase EmfText

