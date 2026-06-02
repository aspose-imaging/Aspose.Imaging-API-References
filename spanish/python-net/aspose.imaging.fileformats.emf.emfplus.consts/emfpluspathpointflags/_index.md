---
title: "EmfPlusPathPointFlags Enumeration"
type: docs
weight: 290
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que están definidos por este objeto.<br/>            C  (1 bit): Si está establecido, la matriz PathPoints especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits.<br/>             Si está despejado, la matriz PathPoints especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.<br/>             Nota Si el indicador P (abajo) está establecido, este indicador PUEDE estar despejado y DEBE ser ignorado.<br/>            R (1 bit): Si está establecido, los tipos de punto en la matriz PathPointTypes son especificados por objetos EmfPlusPathPointTypeRle (sección 2.2.2.32), <br/>             que utilizan compresión de codificación por longitud de ejecución (RLE), y/o objetos EmfPlusPathPointType (sección 2.2.2.31). Consulte la sección 3.1.6 de [MS-WMF] para más información sobre la compresión RLE.<br/>             Si está despejado, los tipos de punto en la matriz PathPointTypes son especificados por objetos EmfPlusPathPointType.<br/>            P (1 bit): Si está establecido, cada elemento de la matriz PathPoints especifica una ubicación en el espacio de coordenadas que es relativa a la<br/>             ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento de PathPoints, se asume una ubicación previa en las coordenadas (0,0).<br/>             Si está despejado, cada elemento de la matriz PathPoints especifica una ubicación absoluta.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| C | La bandera c |
| P | La bandera p |
| R | La bandera r |
