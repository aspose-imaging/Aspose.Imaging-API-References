---
title: "DicomImageInfo"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält alle Metainformationen aus dem DICOM-Dateikopf."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Enthält alle Metainformationen aus dem DICOM-Dateikopf.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Ermittelt die DICOM‑Header‑Informationen als Bytes. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ruft die planare Konfiguration ab. |
| [getSignedImage()](#getSignedImage--) | Ruft einen Wert ab, der angibt, ob \"signedImage\". |
| [getDicomInfo()](#getDicomInfo--) | Ruft die Header-Informationen der DICOM-Datei ab. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ruft einen Wert von \"samplesPerPixel\" ab. |
| [getBitsAllocated()](#getBitsAllocated--) | Ruft einen Wert von \"bitsAllocated\" ab. |
| [getBitsStored()](#getBitsStored--) | Ruft die Anzahl der gespeicherten Bits ab. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Ruft einen Wert von \"PhotoInterpretation\" ab. |
| [getWidth()](#getWidth--) | Liest die Breite. |
| [getHeight()](#getHeight--) | Liest die Höhe. |
| [getWindowCentre()](#getWindowCentre--) | Ruft das Fensterzentrum ab. |
| [getWindowWidth()](#getWindowWidth--) | Ruft die Breite des Fensters ab. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Ruft einen Wert von \"pixelRepresentation\" des Pixels ab. |
| [getRescaleIntercept()](#getRescaleIntercept--) | Ruft einen Wert von \"rescaleIntercept\" ab. |
| [getRescaleSlope()](#getRescaleSlope--) | Ruft einen Wert von \"rescaleSlope\" ab. |
| [getNumberOfFrames()](#getNumberOfFrames--) | Ruft die Anzahl der Frames ab. |
| [isLittleEndian()](#isLittleEndian--) | Ruft einen Wert ab, der angibt, ob diese Instanz little endian ist. |
| [getReds()](#getReds--) | Ruft das Farbarray des Roten ab. |
| [getGreens()](#getGreens--) | Ruft das Farbarray des Grüns ab. |
| [getBlues()](#getBlues--) | Ruft das Farbarray des Blaus ab. |
| [getOffset()](#getOffset--) | Ruft den Offset ab. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Fügt ein neues DICOM-Tag hinzu. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Fügt ein neues DICOM-Tag hinzu. |
| [removeTagAt(int index)](#removeTagAt-int-) | Entfernt ein vorhandenes Tag. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Entfernt ein vorhandenes Tag. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Aktualisiert ein vorhandenes Tag. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Aktualisiert ein vorhandenes Tag. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Ermittelt die DICOM‑Header‑Informationen als Bytes.

Wert: Die DICOM-Header-Informationen in Bytes.

**Returns:**
byte[] - die DICOM-Header-Informationen in Bytes.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ruft die planare Konfiguration ab.

Wert: Die planare Konfiguration.

**Returns:**
int - die planare Konfiguration.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Ruft einen Wert ab, der angibt, ob \"signedImage\".

**Returns:**
boolean - ein Wert, der angibt, ob \"signedImage\".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Ruft die Header-Informationen der DICOM-Datei ab.

**Returns:**
java.util.List<java.lang.String> - die Kopfzeileninformationen der DICOM-Datei.

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
//Modalität: US
//Hersteller: Medistim
//Institutionsname: Hospital Name
//Institutionsadresse: Hospital Address or Department
//Stationsname: VERIQ
//Name des ausführenden Arztes: CA Prof. Debus
//Modellname des Herstellers: VeriQ C
//Empfohlene Bildwiederholrate: 1
//Patientenname: Femoral trombenarterectomy^Case Report:
//Patienten-ID: Fallbericht 1
//Geschlecht des Patienten: M
//Größe des Patienten: 0
//Gewicht des Patienten: 0
//Patientenkommentare: Siehe Fallbericht auf www.medistim.com
//Cine-Rate: 1
//Effektive Dauer: 1
//Geräte-Seriennummer: 0
//Software-Version(en): 3.3.0 RC0 gebaut am 02 / 23 / 12  09:50:45
//Frame-Zeit: 1000
//Studieninstanz-Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//Serieninstanz-Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Seriennummer: 1
//Instanznummer: 1
//Samples pro Pixel: 3
//Photometrische Interpretation: RGB
//Planare Konfiguration: 0
//Anzahl der Frames: 1
//Frame-Inkrement-Pointer:
//Zeilen: 768
//Spalten: 1024
//Zugewiesene Bits: 8
//Gespeicherte Bits: 8
//Höchstbit: 7
//Pixel-Darstellung: 0
//Verlustbehaftete Bildkompression: 00
//Pixel-Daten: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ruft einen Wert von \"samplesPerPixel\" ab.

Wert: Der Wert von "samplesPerPixel".

**Returns:**
int - ein Wert von "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Ruft einen Wert von \"bitsAllocated\" ab.

Wert: Der Wert von "bitsAllocated".

**Returns:**
int - ein Wert von "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Ruft die Anzahl der gespeicherten Bits ab.

**Returns:**
int - die Anzahl der gespeicherten Bits.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Ruft einen Wert von \"PhotoInterpretation\" ab.

**Returns:**
java.lang.String - ein Wert von "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest die Breite.

Wert: Der Wert der Breite.

**Returns:**
int - die Breite.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest die Höhe.

Wert: Der Wert der Höhe.

**Returns:**
int - die Höhe.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Ruft das Fensterzentrum ab.

Wert: Der Wert des Fensterzentrums.

**Returns:**
double - das Fensterzentrum.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Ruft die Breite des Fensters ab.

Wert: Die Breite des Fensters.

**Returns:**
double - die Breite des Fensters.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Ruft einen Wert von \"pixelRepresentation\" des Pixels ab.

Wert: Der Wert von "pixelRepresentation".

**Returns:**
int - ein Wert des Pixels "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Ruft einen Wert von \"rescaleIntercept\" ab.

Wert: Der Wert von "rescaleIntercept".

**Returns:**
double - ein Wert von "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Ruft einen Wert von \"rescaleSlope\" ab.

Wert: Der Wert von "rescaleSlope".

**Returns:**
double - ein Wert von "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Ruft die Anzahl der Frames ab.

Wert: Die Anzahl der Frames.

**Returns:**
int - die Anzahl der Frames.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Ruft einen Wert ab, der angibt, ob diese Instanz little endian ist.

Wert: `true`, wenn diese Instanz little endian ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Instanz little endian ist.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Ruft das Farbarray des Roten ab.

Wert: Die Rotwerte.

**Returns:**
byte[] - das Array der Farben des Roten
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Ruft das Farbarray des Grüns ab.

Wert: Die rote Farbe.

**Returns:**
byte[] - das Array der Farben des Grüns
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Ruft das Farbarray des Blaus ab.

Wert: Das Blau.

**Returns:**
byte[] - das Array der Farben des Blaus
### getOffset() {#getOffset--}
```
public int getOffset()
```


Ruft den Offset ab.

Wert: Der Wert des Offsets.

**Returns:**
int - das Offset.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Fügt ein neues DICOM-Tag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagDescription | java.lang.String | Die Tag-Beschreibung. Darf nicht null oder leer sein. |
| Wert | java.lang.Object | Der Tag-Wert. Darf nicht null sein. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Fügt ein neues DICOM-Tag hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tagDescription | java.lang.String | Die Tag-Beschreibung. Darf nicht null oder leer sein. |
| Wert | java.lang.Object | Der Tag-Wert. Darf nicht null sein. |

**Returns:**
boolean - Das Ergebnis der Operation.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Entfernt ein vorhandenes Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index des zu aktualisierenden Tags. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Entfernt ein vorhandenes Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index des zu aktualisierenden Tags. |

**Returns:**
boolean - Das Ergebnis der Operation.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Aktualisiert ein vorhandenes Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index des zu aktualisierenden Tags. |
| newValue | java.lang.Object | Der Tag-Wert. Darf nicht null sein. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Aktualisiert ein vorhandenes Tag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index des zu aktualisierenden Tags. |
| newValue | java.lang.Object | Der Tag-Wert. Darf nicht null sein. |

**Returns:**
boolean - Das Ergebnis der Operation.
