---
title: DicomImageInfo
second_title: Aspose.Imaging for Java API Reference
description: Contains all meta-information from Dicom file header
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Contains all meta-information from Dicom file header
## Methods

| Method | Description |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Gets the dicom header information by bytes. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Gets the planar configuration. |
| [getSignedImage()](#getSignedImage--) | Gets a value indicating whether "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Gets the header information of the DICOM file. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Gets a value of the "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Gets a value of the "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Gets the number of stored bits. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Gets a value of the "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Gets the width. |
| [getHeight()](#getHeight--) | Gets the height. |
| [getWindowCentre()](#getWindowCentre--) | Gets the window centre. |
| [getWindowWidth()](#getWindowWidth--) | Gets the width of the window. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Gets a value of the pixel "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Gets a value of the "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Gets a value of the "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Gets the number of frames. |
| [isLittleEndian()](#isLittleEndian--) | Gets a value indicating whether this instance is little endian. |
| [getReds()](#getReds--) | Gets the array colors of the red |
| [getGreens()](#getGreens--) | Gets the array colors of the green |
| [getBlues()](#getBlues--) | Gets the array colors of the blue |
| [getOffset()](#getOffset--) | Gets the offset. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Add new Dicom tag. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Add new Dicom tag. |
| [removeTagAt(int index)](#removeTagAt-int-) | Remove an existing tag. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Remove an existing tag. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Update an existing tag. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Update an existing tag. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Gets the dicom header information by bytes.

Value: The dicom header information by bytes.

**Returns:**
byte[] - the dicom header information by bytes.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Gets the planar configuration.

Value: The planar configuration.

**Returns:**
int - the planar configuration.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Gets a value indicating whether "signedImage".

**Returns:**
boolean - a value indicating whether "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Gets the header information of the DICOM file.

**Returns:**
java.util.List<java.lang.String> - the header information of the DICOM file.

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//Media Storage Sop Class Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Media Storage Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Transfer Syntax Uid: 1.2.840.10008.1.2.4.70
//Implementation Class Uid: 1.2.840.114236
//Specific Character Set: ISO_IR 100
//Image Type: \SECONDARY\INTRAOPERATIVE
//Sop Class Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Study Date: 20110824
//Series Date: 20110824
//Content Date: 20110824
//Study Time: 094836.214743984
//Series Time: 094836.214743984
//Content Time: 100451.214743816
//Modality: US
//Manufacturer: Medistim
//Institution Name: Hospital Name
//Institution Address: Hospital Address or Department
//Station Name: VERIQ
//Performing Physician's Name: CA Prof. Debus
//Manufacturer's Model Name: VeriQ C
//Recommended Display Frame Rate: 1
//Patient's Name: Femoral trombenarterectomy^Case Report:
//Patient Id: Case Report 1
//Patient's Sex: M
//Patient's Size: 0
//Patient's Weight: 0
//Patient Comments: See case report on www.medistim.com
//Cine Rate: 1
//Effective Duration: 1
//Device Serial Number: 0
//Software Versions(s): 3.3.0 RC0 built 02 / 23 / 12  09:50:45
//Frame Time: 1000
//Study Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//Series Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Series Number: 1
//Instance Number: 1
//Samples per Pixel: 3
//Photometric Interpretation: RGB
//Planar Configuration: 0
//Number of Frames: 1
//Frame Increment Pointer:
//Rows: 768
//Columns: 1024
//Bits Allocated: 8
//Bits Stored: 8
//high Bit: 7
//Pixel Representation: 0
//Lossy Image Compression: 00
//Pixel Data: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Gets a value of the "samplesPerPixel".

Value: The value of the "samplesPerPixel".

**Returns:**
int - a value of the "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Gets a value of the "bitsAllocated".

Value: The value of the "bitsAllocated".

**Returns:**
int - a value of the "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Gets the number of stored bits.

**Returns:**
int - the number of stored bits.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Gets a value of the "PhotoInterpretation".

**Returns:**
java.lang.String - a value of the "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width.

Value: The value of the width.

**Returns:**
int - the width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the height.

Value: The value of the height.

**Returns:**
int - the height.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Gets the window centre.

Value: The value of the window centre.

**Returns:**
double - the window centre.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Gets the width of the window.

Value: The width of the window.

**Returns:**
double - the width of the window.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Gets a value of the pixel "pixelRepresentation".

Value: The value of the "pixelRepresentation".

**Returns:**
int - a value of the pixel "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Gets a value of the "rescaleIntercept".

Value: The value of the "rescaleIntercept".

**Returns:**
double - a value of the "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Gets a value of the "rescaleSlope".

Value: The value of the "rescaleSlope".

**Returns:**
double - a value of the "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Gets the number of frames.

Value: The number of frames.

**Returns:**
int - the number of frames.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Gets a value indicating whether this instance is little endian.

Value: `true` if this instance is little endian; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Gets the array colors of the red

Value: The reds.

**Returns:**
byte[] - the array colors of the red
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Gets the array colors of the green

Value: The reds color.

**Returns:**
byte[] - the array colors of the green
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Gets the array colors of the blue

Value: The blues.

**Returns:**
byte[] - the array colors of the blue
### getOffset() {#getOffset--}
```
public int getOffset()
```


Gets the offset.

Value: The value of the offset.

**Returns:**
int - the offset.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Add new Dicom tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagDescription | java.lang.String | The tag description. Can not be null or whitespace. |
| value | java.lang.Object | The tag value. Can not be null. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Add new Dicom tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagDescription | java.lang.String | The tag description. Can not be null or whitespace. |
| value | java.lang.Object | The tag value. Can not be null. |

**Returns:**
boolean - The operation result.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Remove an existing tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the tag to be updated. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Remove an existing tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the tag to be updated. |

**Returns:**
boolean - The operation result.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Update an existing tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the tag to be updated. |
| newValue | java.lang.Object | The tag value. Can not be null. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Update an existing tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the tag to be updated. |
| newValue | java.lang.Object | The tag value. Can not be null. |

**Returns:**
boolean - The operation result.
