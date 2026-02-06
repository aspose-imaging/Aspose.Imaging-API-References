---
title: Enum EmfEmrComment
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfEmrComment enum. The EmrComment enumeration defines the types of data that a public comment record can contain as specified in section 2.3.3.4
type: docs
weight: 2710
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
## EmfEmrComment enumeration

The EmrComment enumeration defines the types of data that a public comment record can contain, as specified in section 2.3.3.4.

```csharp
public enum EmfEmrComment : uint
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EMR_COMMENT_WINDOWS_METAFILE | `2147483649` | This comment record contains a specification of an image in WMF. See [MS-WMF] for more information |
| EMR_COMMENT_BEGINGROUP | `2` | This comment record identifies the beginning of a group of drawing records. It identifies an object within an EMF metafile |
| EMR_COMMENT_ENDGROUP | `3` | This comment record identifies the end of a group of drawing records. For every EMR_COMMENT_BEGINGROUP record, an EMR_COMMENT_ENDGROUP record MUST be included in the metafile, and they MAY be nested. |
| EMR_COMMENT_MULTIFORMATS | `1073741828` | This comment record allows multiple definitions of an image to be included in the metafile. Using this comment, for example, an application can include encapsulated PostScript text as well as an EMF definition of an image. |
| EMR_COMMENT_UNICODE_STRING | `64` | This comment record is reserved and MUST NOT be used in an EMF metafile |
| EMR_COMMENT_UNICODE_END | `128` | This comment record is reserved and MUST NOT be used in an EMF metafile |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


