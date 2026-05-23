---
title: "Clase CmxImageFill"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---

**Summary:** Image fill info

**Module:** [aspose.imaging.fileformats.cmx.objectmodel.styles](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/)

**Full Name:** aspose.imaging.fileformats.cmx.objectmodel.styles.CmxImageFill

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CmxImageFill()](#CmxImageFill__1) | Inicializa una nueva instancia de la clase CmxImageFill |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| images | [CmxRasterImage[]](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/) | r/w | Obtiene o establece las imágenes. |
| is_relative | bool | r/w | Obtiene o establece un valor que indica si los valores de tamaño de los patrones son relativos. |
| offset_type | [TileOffsetTypes](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.enums/tileoffsettypes/) | r/w | Obtiene o establece el tipo de desplazamiento entre los mosaicos adyacentes. |
| pattern_height | float | r/w | Obtiene o establece la altura del patrón.<br/>            Utiliza la unidad de medida de distancia de documento común en caso de que [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) sea <c>false</c>,<br/>            de lo contrario tiene la dimensión de la fracción de altura de píxel de la imagen. |
| pattern_width | float | r/w | Obtiene o establece el ancho del patrón.<br/>            Utiliza la unidad de medida de distancia de documento común en caso de que [CmxImageFill.is_relative](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/) sea <c>false</c>,<br/>            de lo contrario tiene la dimensión de la fracción de ancho de píxel de la imagen. |
| procedure | [CmxProcedure](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure/) | r/w | Obtiene o establece el procedimiento. |
| rcp_offset | float | r/w | Obtiene o establece el desplazamiento relativo entre filas o columnas de mosaicos (depende de [CmxImageFill.offset_type](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/)).<br/>            La dimensión es fracciones de la altura o del ancho. |
| rotate180 | bool | r/w | Obtiene o establece un valor que indica si este [CmxImageSpec](/imaging/python-net/aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/) está invertido. |
| tile_offset_x | float | r/w | Obtiene o establece el desplazamiento X del mosaico. |
| tile_offset_y | float | r/w | Obtiene o establece el desplazamiento Y del mosaico. |


### Constructor: CmxImageFill() {#CmxImageFill__1}


```
 CmxImageFill() 
```

Inicializa una nueva instancia de la clase CmxImageFill

