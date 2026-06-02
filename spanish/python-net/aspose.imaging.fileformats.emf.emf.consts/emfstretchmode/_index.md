---
title: "EmfStretchMode Enumeración"
type: docs
weight: 340
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

La enumeración StretchMode se usa para especificar cómo se añaden o eliminan datos de color de los mapas de bits que se estiran o comprimen.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| STRETCH_ANDSCANS | Realiza una operación Boolean AND utilizando los valores de color de los píxeles eliminados y existentes.<br/>            Si el mapa de bits es monocromo, este modo conserva los píxeles negros a expensas de los píxeles blancos |
| STRETCH_DELETESCANS | Elimina los píxeles. Este modo elimina todas las líneas de píxeles eliminadas sin intentar preservar su información. |
| STRETCH_HALFTONE | Mapea los píxeles del rectángulo de origen a bloques de píxeles en el rectángulo de destino. <br/>            El color promedio del bloque de píxeles de destino aproxima el color de los píxeles de origen. |
| STRETCH_ORSCANS | Realiza una operación Boolean OR utilizando los valores de color de los píxeles eliminados y existentes. <br/>            Si el mapa de bits es monocromo, este modo conserva los píxeles blancos a expensas de los píxeles negros. |
