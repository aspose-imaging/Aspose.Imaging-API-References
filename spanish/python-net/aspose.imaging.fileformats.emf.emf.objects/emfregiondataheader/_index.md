---
title: "Clase EmfRegionDataHeader"
type: docs
weight: 250
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Inicializa una nueva instancia de la clase EmfRegionDataHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL de 128 bits ([MS-WMF] sección 2.2.2.19), que especifica <br/>            los límites de la región. |
| count_rects | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de rectángulos en esta región. |
| rgn_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del búfer de rectángulos en bytes. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de este objeto en bytes. Esto DEBE ser 0x00000020. |
| tipo | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tipo de región. Esto DEBERÍA ser <br/>            RDH_RECTANGLES (0x00000001). |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Inicializa una nueva instancia de la clase EmfRegionDataHeader

