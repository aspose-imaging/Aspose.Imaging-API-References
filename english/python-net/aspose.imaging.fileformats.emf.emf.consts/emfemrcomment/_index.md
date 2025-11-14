---
title: EmfEmrComment Enumeration
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---

The EmrComment enumeration defines the types of data that a public comment record can<br/>            contain, as specified in section 2.3.3.4.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfEmrComment

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EMR_COMMENT_BEGINGROUP | This comment record identifies the beginning of a group of drawing records. It identifies an object within an EMF metafile |
| EMR_COMMENT_ENDGROUP | This comment record identifies the end of a group of drawing records. For every EMR_COMMENT_BEGINGROUP<br/>            record, an EMR_COMMENT_ENDGROUP record MUST be included in the metafile, and they MAY be nested. |
| EMR_COMMENT_MULTIFORMATS | This comment record allows multiple definitions of an image to be included in the metafile. <br/>            Using this comment, for example, an application can include encapsulated PostScript text as well as an EMF definition of an image. |
| EMR_COMMENT_UNICODE_END | This comment record is reserved and MUST NOT be used in an EMF metafile |
| EMR_COMMENT_UNICODE_STRING | This comment record is reserved and MUST NOT be used in an EMF metafile |
| EMR_COMMENT_WINDOWS_METAFILE | This comment record contains a specification of an image in WMF. See [MS-WMF] for more information |
