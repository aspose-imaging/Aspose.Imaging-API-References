---
title: "EmfEmrComment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération EmrComment définit les types de données qu'un enregistrement de commentaire public peut contenir, comme spécifié dans la section 2.3.3.4."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

L'énumération EmrComment définit les types de données qu'un enregistrement de commentaire public peut contenir, comme indiqué dans la section 2.3.3.4.
## Champs

| Champ | Description |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Cet enregistrement de commentaire contient une spécification d'une image au format WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Cet enregistrement de commentaire identifie le début d'un groupe d'enregistrements de dessin. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Cet enregistrement de commentaire identifie la fin d'un groupe d'enregistrements de dessin. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Cet enregistrement de commentaire permet d'inclure plusieurs définitions d'une image dans le métafichier. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Cet enregistrement de commentaire contient une spécification d'une image au format WMF. Voir [MS-WMF] pour plus d'informations

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Cet enregistrement de commentaire identifie le début d'un groupe d'enregistrements de dessin. Il identifie un objet dans un métafichier EMF

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Cet enregistrement de commentaire identifie la fin d'un groupe d'enregistrements de dessin. Pour chaque enregistrement EMR\_COMMENT\_BEGINGROUP, un enregistrement EMR\_COMMENT\_ENDGROUP DOIT être inclus dans le métafichier, et ils PEUVENT être imbriqués.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Cet enregistrement de commentaire permet d'inclure plusieurs définitions d'une image dans le métafichier. En utilisant ce commentaire, par exemple, une application peut inclure du texte PostScript encapsulé ainsi qu'une définition EMF d'une image.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Cet enregistrement de commentaire est réservé et NE DOIT PAS être utilisé dans un métafichier EMF

