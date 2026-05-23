---
title: "StretchMode Enumeración"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/
---

La enumeración [StretchMode](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/stretchmode/) especifica el modo de estiramiento del bitmap,<br/>                que define cómo el sistema combina filas o columnas<br/>                de un bitmap con los píxeles existentes.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.StretchMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| BLACK_ON_WHITE | Realiza una operación Boolean AND utilizando los valores de color para los<br/>                píxeles eliminados y existentes. Si el mapa de bits es monocromo<br/>                bitmap, este modo conserva los píxeles negros a expensas de los píxeles blancos |
| COLOR_ON_COLOR | Elimina los píxeles. Este modo elimina todas las líneas de píxeles eliminadas<br/>                sin intentar preservar su información. |
| HALF_TONE | Mapea los píxeles del rectángulo de origen a bloques de píxeles en el<br/>                rectángulo de destino. El color promedio del bloque de destino<br/>                de píxeles aproxima el color de los píxeles de origen. |
| WHITE_ON_BLACK | Realiza una operación OR booleana utilizando los valores de color para los<br/>                píxeles eliminados y existentes. Si el mapa de bits es monocromo<br/>                este modo conserva los píxeles blancos a expensas de los píxeles negros |
