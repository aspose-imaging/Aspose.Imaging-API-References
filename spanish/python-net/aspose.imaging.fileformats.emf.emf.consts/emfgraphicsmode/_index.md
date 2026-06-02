---
title: "Enumeración EmfGraphicsMode"
type: docs
weight: 150
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

La enumeración GraphicsMode se utiliza para especificar cómo interpretar los datos de forma, como las coordenadas de rectángulos.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| GM_ADVANCED | La salida de texto TrueType DEBE ajustarse completamente a la transformación actual de mundo a dispositivo en el contexto del dispositivo de reproducción.<br/>            Los arcos DEBEN dibujarse en dirección antihoraria en el espacio mundial; sin embargo, tanto los puntos de control de los arcos <br/>            como los propios arcos DEBEN respetar plenamente la transformación actual de mundo a dispositivo en el contexto del dispositivo de reproducción.<br/>            La transformación de mundo a dispositivo PUEDE modificarse directamente mediante los registros EMR_MODIFYWORLDTRANSFORM o <br/>            EMR_SETWORLDTRANSFORM, o indirectamente cambiando las extensiones y orígenes de la ventana y la zona de visualización, <br/>            mediante los registros EMR_SETWINDOWEXTEX (sección 2.3.11.30) y EMR_SETVIEWPORTEXTEX (sección 2.3.11.28), <br/>            y los registros EMR_SETWINDOWORGEX (sección 2.3.11.31) y EMR_SETVIEWPORTORGEX (sección 2.3.11.30), respectivamente.<br/>            En el modo gráfico GM_ADVANCED, los bordes inferior y derecho DEBEN incluirse cuando se dibujan rectángulos. |
| GM_COMPATIBLE | El texto TrueType DEBE escribirse de izquierda a derecha y con la parte derecha arriba, incluso si el resto de los gráficos <br/>            están rotados alrededor del eje x o del eje y debido a la transformación actual de mundo a dispositivo en <br/>            el contexto del dispositivo de reproducción. Sólo la altura del texto DEBERÍA escalarse. Los arcos DEBEN dibujarse usando <br/>            la dirección actual del arco en el contexto del dispositivo de reproducción, pero NO DEBEN respetar la transformación actual <br/>            de mundo a dispositivo, lo que podría requerir una rotación alrededor del eje x o del eje y.<br/>            La transformación de mundo a dispositivo SOLO DEBERÍA modificarse cambiando las extensiones y orígenes de la ventana y la zona de visualización, <br/>            mediante los registros EMR_SETWINDOWEXTEX (sección 2.3.11.30) y EMR_SETVIEWPORTEXTEX <br/>            (sección 2.3.11.28), y los registros EMR_SETWINDOWORGEX (sección 2.3.11.31) y EMR_SETVIEWPORTORGEX <br/>            (sección 2.3.11.30), respectivamente. Cambiar la transformación directamente mediante los <br/>            registros EMR_MODIFYWORLDTRANSFORM (sección 2.3.12.1) o EMR_SETWORLDTRANSFORM (sección 2.3.12.2) PODRÍA NO ser compatible.<br/>            En el modo gráfico GM_COMPATIBLE, los bordes inferior y derecho DEBEN excluirse cuando se dibujan rectángulos |
