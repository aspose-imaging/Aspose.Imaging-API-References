---
title: EmfEmrComment
second_title: Aspose.Imaging for Java API Reference
description: The EmrComment enumeration defines the types of data that a public comment record can contain as specified in section 2.3.3.4.
type: docs
weight: 18
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

The EmrComment enumeration defines the types of data that a public comment record can contain, as specified in section 2.3.3.4.
## Fields

| Field | Description |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | This comment record contains a specification of an image in WMF. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | This comment record identifies the beginning of a group of drawing records. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | This comment record identifies the end of a group of drawing records. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | This comment record allows multiple definitions of an image to be included in the metafile. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | This comment record is reserved and MUST NOT be used in an EMF metafile |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | This comment record is reserved and MUST NOT be used in an EMF metafile |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


This comment record contains a specification of an image in WMF. See [MS-WMF] for more information

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


This comment record identifies the beginning of a group of drawing records. It identifies an object within an EMF metafile

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


This comment record identifies the end of a group of drawing records. For every EMR\_COMMENT\_BEGINGROUP record, an EMR\_COMMENT\_ENDGROUP record MUST be included in the metafile, and they MAY be nested.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


This comment record allows multiple definitions of an image to be included in the metafile. Using this comment, for example, an application can include encapsulated PostScript text as well as an EMF definition of an image.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


This comment record is reserved and MUST NOT be used in an EMF metafile

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


This comment record is reserved and MUST NOT be used in an EMF metafile

