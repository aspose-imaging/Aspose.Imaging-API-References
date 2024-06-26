---
title: DicomImageInfo.DicomInfo
second_title: Aspose.Imaging for .NET API Reference
description: DicomImageInfo property. Gets the header information of the DICOM file
type: docs
weight: 50
url: /net/aspose.imaging.fileformats.dicom/dicomimageinfo/dicominfo/
---
## DicomImageInfo.DicomInfo property

Gets the header information of the DICOM file.

```csharp
public ReadOnlyCollection<string> DicomInfo { get; }
```

## Examples

The following example shows how to read the header information of a DICOM image.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3628";
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, "ttfm.dcm")))
{
    foreach (string s in image.FileInfo.DicomInfo)
    {
        System.Console.WriteLine(s);
    }
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

### See Also

* class [DicomImageInfo](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimageinfo/)
* assembly [Aspose.Imaging](../../../)


