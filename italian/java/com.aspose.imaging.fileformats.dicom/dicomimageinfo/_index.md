---
title: "DicomImageInfo"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene tutte le meta‑informazioni dall'intestazione del file Dicom."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Contiene tutte le meta‑informazioni dall'intestazione del file Dicom.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Ottiene le informazioni dell'intestazione DICOM in byte. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Ottiene la configurazione planare. |
| [getSignedImage()](#getSignedImage--) | Ottiene un valore che indica se "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Ottiene le informazioni dell'intestazione del file DICOM. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Ottiene un valore di "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Ottiene un valore di "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Ottiene il numero di bit memorizzati. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Ottiene un valore di "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Restituisce la larghezza. |
| [getHeight()](#getHeight--) | Ottiene l'altezza. |
| [getWindowCentre()](#getWindowCentre--) | Ottiene il centro della finestra. |
| [getWindowWidth()](#getWindowWidth--) | Ottiene la larghezza della finestra. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Ottiene un valore del pixel "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Ottiene un valore di "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Ottiene un valore di "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Ottiene il numero di fotogrammi. |
| [isLittleEndian()](#isLittleEndian--) | Ottiene un valore che indica se questa istanza è little endian. |
| [getReds()](#getReds--) | Ottiene l'array dei colori del rosso |
| [getGreens()](#getGreens--) | Ottiene l'array dei colori del verde |
| [getBlues()](#getBlues--) | Ottiene l'array dei colori del blu |
| [getOffset()](#getOffset--) | Ottiene l'offset. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Aggiungi un nuovo tag Dicom. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Aggiungi un nuovo tag Dicom. |
| [removeTagAt(int index)](#removeTagAt-int-) | Rimuovi un tag esistente. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Rimuovi un tag esistente. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Aggiorna un tag esistente. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Aggiorna un tag esistente. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Ottiene le informazioni dell'intestazione DICOM in byte.

Valore: le informazioni dell'intestazione DICOM in byte.

**Returns:**
byte[] - le informazioni dell'intestazione DICOM in byte.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Ottiene la configurazione planare.

Valore: La configurazione planare.

**Returns:**
int - la configurazione planare.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Ottiene un valore che indica se "signedImage".

**Returns:**
boolean - un valore che indica se "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Ottiene le informazioni dell'intestazione del file DICOM.

**Returns:**
java.util.List<java.lang.String> - le informazioni di intestazione del file DICOM.

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
//UID della classe SOP di archiviazione media: 1.2.840.10008.5.1.4.1.1.3.1
//UID dell'istanza SOP di archiviazione media: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//UID della sintassi di trasferimento: 1.2.840.10008.1.2.4.70
//UID della classe di implementazione: 1.2.840.114236
//Set di caratteri specifico: ISO_IR 100
//Tipo di immagine: \SECONDARY\INTRAOPERATIVE
//UID della classe SOP: 1.2.840.10008.5.1.4.1.1.3.1
//UID dell'istanza SOP: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Data dello studio: 20110824
//Data della serie: 20110824
//Data del contenuto: 20110824
//Ora dello studio: 094836.214743984
//Ora della serie: 094836.214743984
//Ora del contenuto: 100451.214743816
//Modalità: US
//Produttore: Medistim
//Nome dell'istituzione: Hospital Name
//Indirizzo dell'istituzione: Hospital Address or Department
//Nome della stazione: VERIQ
//Nome del medico esecutore: CA Prof. Debus
//Nome modello del produttore: VeriQ C
//Frequenza fotogrammi consigliata per la visualizzazione: 1
//Nome del paziente: Femoral trombenarterectomy^Case Report:
//ID Paziente: Rapporto del Caso 1
//Sesso del Paziente: M
//Dimensione del Paziente: 0
//Peso del Paziente: 0
//Commenti del Paziente: Vedi il caso di studio su www.medistim.com
//Frequenza Cine: 1
//Durata Effettiva: 1
//Numero di Serie del Dispositivo: 0
//Versione/i del Software: 3.3.0 RC0 compilata il 02 / 23 / 12  09:50:45
//Tempo del Fotogramma: 1000
//UID Istanza Studio: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//UID Istanza Serie: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Numero Serie: 1
//Numero Istanza: 1
//Campioni per Pixel: 3
//Interpretazione Fotometrica: RGB
//Configurazione Planare: 0
//Numero di Fotogrammi: 1
//Puntatore Incremento Fotogramma:
//Righe: 768
//Colonne: 1024
//Bit Allocati: 8
//Bit Memorizzati: 8
//Bit più alto: 7
//Rappresentazione Pixel: 0
//Compressione immagine con perdita: 00
//Dati pixel: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Ottiene un valore di "samplesPerPixel".

Valore: Il valore di "samplesPerPixel".

**Returns:**
int - un valore di "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Ottiene un valore di "bitsAllocated".

Valore: Il valore di "bitsAllocated".

**Returns:**
int - un valore di "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Ottiene il numero di bit memorizzati.

**Returns:**
int - il numero di bit memorizzati.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Ottiene un valore di "PhotoInterpretation".

**Returns:**
java.lang.String - un valore di "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza.

Valore: Il valore della larghezza.

**Returns:**
int - la larghezza.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene l'altezza.

Valore: Il valore dell'altezza.

**Returns:**
int - l'altezza.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Ottiene il centro della finestra.

Valore: Il valore del centro della finestra.

**Returns:**
double - il centro della finestra.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Ottiene la larghezza della finestra.

Valore: La larghezza della finestra.

**Returns:**
double - la larghezza della finestra.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Ottiene un valore del pixel "pixelRepresentation".

Valore: Il valore di "pixelRepresentation".

**Returns:**
int - un valore del pixel "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Ottiene un valore di "rescaleIntercept".

Valore: Il valore di "rescaleIntercept".

**Returns:**
double - un valore di "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Ottiene un valore di "rescaleSlope".

Valore: Il valore di "rescaleSlope".

**Returns:**
double - un valore di "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Ottiene il numero di fotogrammi.

Valore: Il numero di fotogrammi.

**Returns:**
int - il numero di fotogrammi.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Ottiene un valore che indica se questa istanza è little endian.

Valore: `true` se questa istanza è little endian; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa istanza è little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Ottiene l'array dei colori del rosso

Valore: I rossi.

**Returns:**
byte[] - l'array dei colori del rosso
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Ottiene l'array dei colori del verde

Valore: Il colore del rosso.

**Returns:**
byte[] - l'array dei colori del verde
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Ottiene l'array dei colori del blu

Valore: I blu.

**Returns:**
byte[] - l'array dei colori del blu
### getOffset() {#getOffset--}
```
public int getOffset()
```


Ottiene l'offset.

Valore: Il valore dell'offset.

**Returns:**
int - l'offset.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Aggiungi un nuovo tag Dicom.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagDescription | java.lang.String | La descrizione del tag. Non può essere nulla o vuota. |
| valore | java.lang.Object | Il valore del tag. Non può essere nullo. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Aggiungi un nuovo tag Dicom.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagDescription | java.lang.String | La descrizione del tag. Non può essere nulla o vuota. |
| valore | java.lang.Object | Il valore del tag. Non può essere nullo. |

**Returns:**
boolean - Il risultato dell'operazione.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Rimuovi un tag esistente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del tag da aggiornare. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Rimuovi un tag esistente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del tag da aggiornare. |

**Returns:**
boolean - Il risultato dell'operazione.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Aggiorna un tag esistente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del tag da aggiornare. |
| newValue | java.lang.Object | Il valore del tag. Non può essere nullo. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Aggiorna un tag esistente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice del tag da aggiornare. |
| newValue | java.lang.Object | Il valore del tag. Non può essere nullo. |

**Returns:**
boolean - Il risultato dell'operazione.
