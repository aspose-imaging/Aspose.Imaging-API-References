---
title: "DicomImageInfo"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller all metainformation från DICOM-filhuvudet."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Innehåller all metainformation från DICOM-filhuvudet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Hämtar dicom-huvudinformationsdata som bytes. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Hämtar den plana konfigurationen. |
| [getSignedImage()](#getSignedImage--) | Hämtar ett värde som indikerar om "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Hämtar rubrikinformationen för DICOM-filen. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Hämtar ett värde för "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Hämtar ett värde för "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Hämtar antalet lagrade bitar. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Hämtar ett värde för "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Hämtar bredden. |
| [getHeight()](#getHeight--) | Hämtar höjden. |
| [getWindowCentre()](#getWindowCentre--) | Hämtar fönstrets centrum. |
| [getWindowWidth()](#getWindowWidth--) | Hämtar fönstrets bredd. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Hämtar ett värde för pixeln "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Hämtar ett värde för "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Hämtar ett värde för "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Hämtar antalet ramar. |
| [isLittleEndian()](#isLittleEndian--) | Hämtar ett värde som indikerar om den här instansen är little endian. |
| [getReds()](#getReds--) | Hämtar färgarrayen för röd |
| [getGreens()](#getGreens--) | Hämtar färgarrayen för grön |
| [getBlues()](#getBlues--) | Hämtar färgarrayen för blå |
| [getOffset()](#getOffset--) | Hämtar förskjutningen. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Lägg till ny Dicom-tag. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Lägg till ny Dicom-tag. |
| [removeTagAt(int index)](#removeTagAt-int-) | Ta bort en befintlig tagg. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Ta bort en befintlig tagg. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Uppdatera en befintlig tagg. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Uppdatera en befintlig tagg. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Hämtar dicom-huvudinformationsdata som bytes.

Värde: DICOM-rubrikinformationen i byte.

**Returns:**
byte[] - DICOM-rubrikinformationen i byte.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Hämtar den plana konfigurationen.

Värde: Den plana konfigurationen.

**Returns:**
int - den plana konfigurationen.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Hämtar ett värde som indikerar om "signedImage".

**Returns:**
boolean - ett värde som indikerar om "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Hämtar rubrikinformationen för DICOM-filen.

**Returns:**
java.util.List<java.lang.String> - rubrikinformationen för DICOM-filen.

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
//Specifikt teckensätt: ISO_IR 100
//Bildtyp: \SECONDARY\INTRAOPERATIVE
//Sop Class Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Studiedatum: 20110824
//Seriedatum: 20110824
//Innehållsdatum: 20110824
//Studietid: 094836.214743984
//Serietid: 094836.214743984
//Innehållstid: 100451.214743816
//Modalitet: US
//Tillverkare: Medistim
//Institutionsnamn: Hospital Name
//Institutionsadress: Hospital Address or Department
//Stationsnamn: VERIQ
//Utförande läkares namn: CA Prof. Debus
//Tillverkarens modellnamn: VeriQ C
//Rekommenderad bildfrekvens för display: 1
//Patientens namn: Femoral trombenarterectomy^Case Report:
//Patient-ID: Fallrapport 1
//Patientens kön: M
//Patientens storlek: 0
//Patientens vikt: 0
//Patientkommentarer: Se fallrapport på www.medistim.com
//Cine-hastighet: 1
//Effektiv varaktighet: 1
//Enhetens serienummer: 0
//Programvaruversion(er): 3.3.0 RC0 built 02 / 23 / 12  09:50:45
//Bildramtid: 1000
//Studieinstans UID: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//Serieinstans UID: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Serienummer: 1
//Instansnummer: 1
//Prover per pixel: 3
//Fotometrisk tolkning: RGB
//Planär konfiguration: 0
//Antal bildrutor: 1
//Ramökning pekare:
//Rader: 768
//Kolumner: 1024
//Tilldelade bitar: 8
//Lagrade bitar: 8
//Högsta bit: 7
//Pixelrepresentation: 0
//Förlustkomprimering av bild: 00
//Pixeldata: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Hämtar ett värde för "samplesPerPixel".

Värde: Värdet för "samplesPerPixel".

**Returns:**
int - ett värde för "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Hämtar ett värde för "bitsAllocated".

Värde: Värdet för "bitsAllocated".

**Returns:**
int - ett värde för "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Hämtar antalet lagrade bitar.

**Returns:**
int - antalet lagrade bitar.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Hämtar ett värde för "PhotoInterpretation".

**Returns:**
java.lang.String - ett värde för "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden.

Värde: Värdet för bredden.

**Returns:**
int - bredden.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar höjden.

Värde: Värdet för höjden.

**Returns:**
int - höjden.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Hämtar fönstrets centrum.

Värde: Värdet för fönstercentrum.

**Returns:**
double - fönstercentrum.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Hämtar fönstrets bredd.

Värde: Bredden på fönstret.

**Returns:**
double - bredden på fönstret.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Hämtar ett värde för pixeln "pixelRepresentation".

Värde: Värdet för "pixelRepresentation".

**Returns:**
int - ett värde för pixel "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Hämtar ett värde för "rescaleIntercept".

Värde: Värdet för "rescaleIntercept".

**Returns:**
double - ett värde för "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Hämtar ett värde för "rescaleSlope".

Värde: Värdet för "rescaleSlope".

**Returns:**
double - ett värde för "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Hämtar antalet ramar.

Värde: Antalet ramar.

**Returns:**
int - antalet ramar.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Hämtar ett värde som indikerar om den här instansen är little endian.

Värde: `true` om detta objekt är little endian; annars `false`.

**Returns:**
boolean - ett värde som indikerar om detta objekt är little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Hämtar färgarrayen för röd

Värde: De röda.

**Returns:**
byte[] - färgarrayen för den röda
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Hämtar färgarrayen för grön

Värde: Den röda färgen.

**Returns:**
byte[] - färgarrayen för den gröna
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Hämtar färgarrayen för blå

Värde: De blåa.

**Returns:**
byte[] - färgarrayen för den blåa
### getOffset() {#getOffset--}
```
public int getOffset()
```


Hämtar förskjutningen.

Värde: Offsetvärdet.

**Returns:**
int - offseten.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Lägg till ny Dicom-tag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagDescription | java.lang.String | Taggbeskrivningen. Får inte vara null eller tom. |
| värde | java.lang.Object | Taggvärdet. Får inte vara null. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Lägg till ny Dicom-tag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tagDescription | java.lang.String | Taggbeskrivningen. Får inte vara null eller tom. |
| värde | java.lang.Object | Taggvärdet. Får inte vara null. |

**Returns:**
boolean - Resultatet av operationen.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Ta bort en befintlig tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för taggen som ska uppdateras. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Ta bort en befintlig tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för taggen som ska uppdateras. |

**Returns:**
boolean - Resultatet av operationen.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Uppdatera en befintlig tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för taggen som ska uppdateras. |
| newValue | java.lang.Object | Taggvärdet. Får inte vara null. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Uppdatera en befintlig tagg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för taggen som ska uppdateras. |
| newValue | java.lang.Object | Taggvärdet. Får inte vara null. |

**Returns:**
boolean - Resultatet av operationen.
