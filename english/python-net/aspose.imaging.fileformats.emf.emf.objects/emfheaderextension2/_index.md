---
title: EmfHeaderExtension2 Class
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---

The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the<br/>            ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension2

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfHeaderExtension2 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfHeaderExtension2()|Initializes a new instance of the EmfHeaderExtension2 class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive <br/>            bounds in device units of the smallest rectangle that can be drawn around the image stored in <br/>            the metafile|
|frame|Gets or sets a WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter <br/>            units, of a rectangle that surrounds the image stored in the metafile|
|record_signature|Gets or sets a 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA_SIGNATURE, <br/>            from the FormatSignature enumeration (section 2.1.14).|
|version|Gets or sets Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000|
|bytes|Gets or sets  32-bit unsigned integer that specifies the size of the metafile, in bytes.|
|records|Gets or sets a 32-bit unsigned integer that specifies the number of records in the metafile|
|handles|Gets or sets a 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile|
|reserved|Gets or sets a 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored|
|n_desription|Gets or sets a 32-bit unsigned integer that specifies the number of characters in the array <br/>            that contains the description of the metafile's contents. This is zero if there is no description string.|
|off_description|Gets or sets a 32-bit unsigned integer that specifies the offset from the beginning of this <br/>            record to the array that contains the description of the metafile's contents|
|n_pal_entries|Gets or sets a 32-bit unsigned integer that specifies the number of entries in the metafile <br/>            palette. The palette is located in the EMR_EOF record|
|device|Gets or sets a WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels|
|millimeters|Gets or sets a WMF SizeL object that specifies the size of the reference device, in millimeters|
|valid|Gets a value indicating whether this [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) is valid.|
|micrometers_x|Gets or sets the 32-bit horizontal size of the display device for which the metafile image was generated, in micrometers|
|micrometers_y|Gets or sets the 32-bit vertical size of the display device for which the metafile image was generated, in micrometers.|
