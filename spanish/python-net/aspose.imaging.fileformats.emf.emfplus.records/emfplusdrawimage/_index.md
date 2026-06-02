---
title: "Clase EmfPlusDrawImage"
type: docs
weight: 130
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si PointData está comprimido.<br/>            Si se establece, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38).<br/>            Si se limpia, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| image_attributes_id | int | r/w | Obtiene o establece el identificador de los atributos de la imagen<br/>            Un entero sin signo de 32 bits que especifica el índice de un objeto EmfPlusImageAttributes opcional (sección 2.2.1.5) en la tabla de objetos EMF+. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>
            El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>            Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la imagen.<br/>            La porción de la imagen especificada por el campo SrcRect se escala para ajustarse a este rectángulo. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece el rectángulo de origen<br/>            Un objeto EmfPlusRectF que especifica una porción de la imagen a renderizar.<br/>            La porción de la imagen especificada por este rectángulo se escala para ajustarse al rectángulo de destino<br/>            especificado por el campo RectData. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtiene o establece la unidad de origen<br/>            Entero con signo de 32 bits que especifica las unidades del campo SrcRect.<br/>            DEBE ser el miembro UnitTypePixel de la enumeración UnitType (sección 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

