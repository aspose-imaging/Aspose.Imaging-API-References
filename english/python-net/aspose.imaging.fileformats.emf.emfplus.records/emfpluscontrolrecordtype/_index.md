---
title: EmfPlusControlRecordType Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype/
---

The control record types specify global parameters for EMF+ metafile processing.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType

**Inheritance:** EmfPlusRecord

**Aspose.Imaging Version:** 23.6

The EmfPlusControlRecordType type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |

