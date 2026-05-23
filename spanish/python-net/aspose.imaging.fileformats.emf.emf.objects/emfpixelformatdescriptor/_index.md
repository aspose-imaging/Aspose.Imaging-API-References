---
title: "Clase EmfPixelFormatDescriptor"
type: docs
weight: 220
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Inicializa una nueva instancia de la clase EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Obtiene o establece especifica el número de planos de superposición y subyacentes. Los bits 0 a 3 especifican hasta 15 planos de superposición y los bits 4 a 7 especifican hasta 15 planos subyacentes. |
| c_accum_alpha_bits | System.Byte | r/w | Obtiene o establece especifica el número de planos de bits alfa en el búfer de acumulación. |
| c_accum_bits | System.Byte | r/w | Obtiene o establece el número total de planos de bits en el búfer de acumulación. |
| c_accum_blue_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits azules en el búfer de acumulación. |
| c_accum_green_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits verdes en la acumulación |
| c_accum_red_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits rojos en el búfer de acumulación |
| c_alpha_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits alfa en cada búfer de color RGBA |
| c_alpha_shift | System.Byte | r/w | Obtiene o establece la cantidad de desplazamiento para los planos de bits alfa en cada búfer de color RGBA |
| c_aux_buffers | System.Byte | r/w | Obtiene o establece el número de búferes auxiliares. Los búferes auxiliares no son compatibles |
| c_blue_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits azules en cada búfer de color RGBA. |
| c_blue_shift | System.Byte | r/w | Obtiene o establece la cantidad de desplazamiento para los planos de bits azules en cada búfer de color RGBA. |
| c_color_bits | System.Byte | r/w | Obtiene o establece el número de bits por píxel para los tipos de píxel RGBA, excluyendo los planos de bits alfa. Para los píxeles de tabla de colores, es el tamaño de cada índice de la tabla de colores |
| c_depth_bits | System.Byte | r/w | Obtiene o establece la profundidad del búfer de profundidad (eje z). |
| c_green_bits | System.Byte | r/w | Obtiene o establece el número de planos de bits verdes en cada búfer de color RGBA |
| c_green_shift | System.Byte | r/w | Obtiene o establece Especifica el recuento de desplazamiento para los planos de bits verdes en cada búfer de color RGBA. |
| c_red_bits | System.Byte | r/w | Obtiene o establece Especifica el número de planos de bits rojos en cada búfer de color RGBA |
| c_red_shift | System.Byte | r/w | Obtiene o establece Especifica el recuento de desplazamiento en bits para los planos de bits rojos en cada búfer de color RGBA. |
| c_stencil_bits | System.Byte | r/w | Obtiene o establece especifica la profundidad del búfer de plantilla. |
| dw_damage_mask | int | r/w | Obtiene o establece Este campo PUEDE ser ignorado |
| dw_flags | int | r/w | Obtiene o establece banderas de bits que especifican propiedades del búfer de píxeles que se utiliza <br/>            para la salida a la superficie de dibujo. Estas propiedades no son todas mutuamente <br/>            exclusivas; se permiten combinaciones de banderas, excepto donde se indique lo contrario. |
| dw_layer_mask | int | r/w | Obtiene o establece Este campo PUEDE ser ignorado. |
| dw_visible_mask | int | r/w | Obtiene o establece especifica el color transparente o el índice de un plano subyacente. Cuando el tipo de píxel <br/>            es RGBA, dwVisibleMask es un valor de color RGB transparente. Cuando el tipo de píxel <br/>            es índice de color, es un valor de índice transparente. |
| layer_type | System.Byte | r/w | Obtiene o establece Este campo PUEDE ser ignorado |
| n_size | int | r/w | Obtiene o establece un entero de 16 bits que especifica el tamaño, en bytes, de esta estructura de datos. |
| n_version | int | r/w | Obtiene o establece un entero de 16 bits que DEBE establecerse a 0x0001. |
| pixel_type | System.Byte | r/w | Obtiene o establece el tipo de datos de píxel<br/>            PFD_TYPE_RGBA       0x00 El formato de píxel es RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Cada píxel es un índice en una tabla de colores. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Inicializa una nueva instancia de la clase EmfPixelFormatDescriptor

