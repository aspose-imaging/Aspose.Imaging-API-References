---
title: EmfLogFontExDv Class
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/
---

The LogFontExDv object specifies the design vector for an extended logical font.

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontExDv

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfLogFontExDv type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfLogFontExDv(emf_log_font_ex)|Initializes a new instance of the EmfLogFontExDv class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|height|  |
|width|  |
|escapement|  |
|orientation|  |
|weight|  |
|italic|  |
|underline|  |
|strikeout|  |
|char_set|  |
|out_precision|  |
|clip_precision|  |
|quality|  |
|pitch_and_family|  |
|facename|  |
|full_name|Gets or sets a string of 64 Unicode characters that contains the font's full name. If <br/>            the length of this string is less than 64 characters, a terminating NULL MUST be present, after <br/>            which the remainder of this field MUST be ignored.|
|style|Gets or sets a string of 32 Unicode characters that defines the font's style. If the length of <br/>            this string is less than 32 characters, a terminating NULL MUST be present, after which the <br/>            remainder of this field MUST be ignored.|
|script|Gets or sets a string of 32 Unicode characters that defines the character set of the font. <br/>            If the length of this string is less than 32 characters, a terminating NULL MUST be present, <br/>            after which the remainder of this field MUST be ignored.|
|design_vector|Gets or sets a DesignVector object (section 2.2.3). This field MUST NOT be longer than 72 bytes.|
