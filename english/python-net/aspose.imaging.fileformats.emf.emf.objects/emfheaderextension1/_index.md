---
title: EmfHeaderExtension1 Class
type: docs
weight: 90
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Initializes a new instance of the EmfHeaderExtension1 class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Gets or sets a 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile.<br/>            0x00000000 OpenGL records are not present in the metafile.<br/>            0x00000001 OpenGL records are present in the metafile. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive <br/>            bounds in device units of the smallest rectangle that can be drawn around the image stored in <br/>            the metafile |
| bytes | int | r/w | Gets or sets  32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| cb_pixel_format | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. <br/>            This MUST be 0x00000000 if no pixel format is set |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter <br/>            units, of a rectangle that surrounds the image stored in the metafile |
| handles | int | r/w | Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters |
| n_desription | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array <br/>            that contains the description of the metafile's contents. This is zero if there is no description string. |
| n_pal_entries | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile <br/>            palette. The palette is located in the EMR_EOF record |
| off_description | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this <br/>            record to the array that contains the description of the metafile's contents |
| off_pixel_format | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object.<br/>            This MUST be 0x00000000 if no pixel format is set. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA_SIGNATURE, <br/>            from the FormatSignature enumeration (section 2.1.14). |
| records | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile |
| reserved | int | r/w | Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| valid | bool | r | Gets a value indicating whether this [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) is valid. |
| version | int | r/w | Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Initializes a new instance of the EmfHeaderExtension1 class

