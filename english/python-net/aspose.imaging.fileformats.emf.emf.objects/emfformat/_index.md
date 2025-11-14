---
title: EmfFormat Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Initializes a new instance of the EmfFormat class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| off_data | int | r/w | Gets or sets 32-bit unsigned integer that specifies the offset to the data from the <br/>            start of the identifier field in an EMR_COMMENT_PUBLIC record (section 2.3.3.4). <br/>            The offset MUST be 32-bit aligned. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the format of the image data. <br/>            This value MUST be in the FormatSignature enumeration (section 2.1.14). |
| size_data | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes |
| version | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the format version number. <br/>            If the Signature field specifies encapsulated PostScript (EPS), <br/>            this value MUST be 0x00000001; otherwise, this value MUST be ignored |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Initializes a new instance of the EmfFormat class

