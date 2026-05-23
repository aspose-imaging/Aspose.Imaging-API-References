---
title: "Enumeración EmfModifyWorldTransformMode"
type: docs
weight: 240
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---

La enumeración ModifyWorldTransformMode define modos para usar los datos de transformación especificados<br/>            para modificar la transformación del espacio mundial al espacio de página que está actualmente definida en el contexto del dispositivo de reproducción.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfModifyWorldTransformMode

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| MWT_IDENTITY | Restablece la transformación actual usando la matriz identidad. En este modo, los datos de transformación especificados se ignoran |
| MWT_LEFTMULTIPLY | Multiplica la transformación actual. En este modo, los datos de transformación especificados son el multiplicando izquierdo, y <br/>            la transformación que está actualmente definida en el contexto del dispositivo de reproducción es el multiplicando derecho |
| MWT_RIGHTMULTIPLY | Multiplique la transformación actual. En este modo, los datos de transformación especificados son el multiplicando derecho, <br/>            y la transformación que está actualmente definida en el contexto del dispositivo de reproducción es el multiplicando izquierdo |
| MWT_SET | Ejecute la función de un registro EMR_SETWORLDTRANSFORM (sección 2.3.12.2). |
