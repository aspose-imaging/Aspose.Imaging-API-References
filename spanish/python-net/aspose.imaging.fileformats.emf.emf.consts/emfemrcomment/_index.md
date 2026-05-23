---
title: "Enumeración EmfEmrComment"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

La enumeración EmrComment define los tipos de datos que un registro de comentario público puede<br/>            contener, según lo especificado en la sección 2.3.3.4.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | Este registro de comentario identifica el comienzo de un grupo de registros de dibujo. Identifica un objeto dentro de un metafile EMF |
| EMR_COMMENT_ENDGROUP | Este registro de comentario identifica el final de un grupo de registros de dibujo. Para cada registro EMR_COMMENT_BEGINGROUP<br/>            debe incluirse un registro EMR_COMMENT_ENDGROUP en el metafile, y pueden estar anidados. |
| EMR_COMMENT_MULTIFORMATS | Este registro de comentario permite que se incluyan múltiples definiciones de una imagen en el metafile. <br/>            Usando este comentario, por ejemplo, una aplicación puede incluir texto PostScript encapsulado así como una definición EMF de una imagen. |
| EMR_COMMENT_UNICODE_END | Este registro de comentario está reservado y NO DEBE usarse en un metafile EMF |
| EMR_COMMENT_UNICODE_STRING | Este registro de comentario está reservado y NO DEBE usarse en un metafile EMF |
| EMR_COMMENT_WINDOWS_METAFILE | Este registro de comentario contiene una especificación de una imagen en WMF. Consulte [MS-WMF] para más información |
