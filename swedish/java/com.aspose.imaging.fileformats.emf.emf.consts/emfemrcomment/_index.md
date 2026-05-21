---
title: "EmfEmrComment"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmrComment-enumerationen definierar de datatyper som en offentlig kommentarspost kan innehålla enligt avsnitt 2.3.3.4."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

EmrComment-enumerationen definierar de datatyper som en offentlig kommentarspost kan innehålla, enligt avsnitt 2.3.3.4.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Denna kommentarspost innehåller en specifikation av en bild i WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Denna kommentarspost identifierar början på en grupp ritposter. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Denna kommentarspost identifierar slutet på en grupp ritposter. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Denna kommentarspost tillåter att flera definitioner av en bild inkluderas i metafilen. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Denna kommentarspost är reserverad och FÅR INTE användas i en EMF-metafil |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Denna kommentarspost är reserverad och FÅR INTE användas i en EMF-metafil |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Denna kommentarspost innehåller en specifikation av en bild i WMF. Se [MS-WMF] för mer information

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Denna kommentarspost identifierar början av en grupp ritningsposter. Den identifierar ett objekt inom en EMF-metafil

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Denna kommentarspost identifierar slutet på en grupp ritningsposter. För varje EMR\_COMMENT\_BEGINGROUP-post måste en EMR\_COMMENT\_ENDGROUP-post inkluderas i metafilen, och de får vara nästlade.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Denna kommentarspost möjliggör att flera definitioner av en bild inkluderas i metafilen. Genom att använda denna kommentar kan en applikation till exempel inkludera innesluten PostScript-text samt en EMF-definition av en bild.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Denna kommentarspost är reserverad och FÅR INTE användas i en EMF-metafil

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Denna kommentarspost är reserverad och FÅR INTE användas i en EMF-metafil

