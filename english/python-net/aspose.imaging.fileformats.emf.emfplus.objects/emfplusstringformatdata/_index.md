---
title: EmfPlusStringFormatData Class
type: docs
weight: 660
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusStringFormatData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusStringFormatData()|Initializes a new instance of the EmfPlusStringFormatData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|tab_stops|Gets or sets an optional array of floating-point values that specify <br/>            the optional tab stop locations for this object. Each tab <br/>            stop value represents the number of spaces between tab <br/>            stops or, for the first tab stop, the number of spaces <br/>            between the beginning of a line of text and the first tab stop. <br/>            This field MUST be present if the value of the TabStopCount <br/>            field in the EmfPlusStringFormat object is greater than 0.|
|char_range|Gets or sets an optional array of RangeCount EmfPlusCharacterRange <br/>            objects that specify the range of character positions <br/>            within a string of text. The bounding region is defined<br/>            by the area of the display that is occupied by a group <br/>            of characters specified by the character range.<br/>            This field MUST be present if the value of the RangeCount<br/>            field in the EmfPlusStringFormat object is greater than 0.|
