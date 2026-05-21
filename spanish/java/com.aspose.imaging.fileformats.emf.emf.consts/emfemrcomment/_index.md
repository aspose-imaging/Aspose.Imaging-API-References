---
title: "EmfEmrComment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración EmrComment define los tipos de datos que un registro de comentario público puede contener según lo especificado en la sección 2.3.3.4."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

La enumeración EmrComment define los tipos de datos que un registro de comentario público puede contener, según lo especificado en la sección 2.3.3.4.
## Campos

| Campo | Descripción |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Este registro de comentario contiene una especificación de una imagen en WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Este registro de comentario identifica el comienzo de un grupo de registros de dibujo. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Este registro de comentario identifica el final de un grupo de registros de dibujo. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Este registro de comentario permite que se incluyan múltiples definiciones de una imagen en el metarchivo. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Este registro de comentario está reservado y NO DEBE usarse en un metafichero EMF |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Este registro de comentario está reservado y NO DEBE usarse en un metafichero EMF |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Este registro de comentario contiene una especificación de una imagen en WMF. Consulte [MS-WMF] para obtener más información

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Este registro de comentario identifica el comienzo de un grupo de registros de dibujo. Identifica un objeto dentro de un metafichero EMF

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Este registro de comentario identifica el final de un grupo de registros de dibujo. Para cada registro EMR\_COMMENT\_BEGINGROUP, se DEBE incluir un registro EMR\_COMMENT\_ENDGROUP en el metafichero, y pueden estar anidados.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Este registro de comentario permite que se incluyan múltiples definiciones de una imagen en el metafichero. Usando este comentario, por ejemplo, una aplicación puede incluir texto PostScript encapsulado así como una definición EMF de una imagen.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Este registro de comentario está reservado y NO DEBE usarse en un metafichero EMF

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Este registro de comentario está reservado y NO DEBE usarse en un metafichero EMF

