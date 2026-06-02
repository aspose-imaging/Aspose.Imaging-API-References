---
title: "LoadOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta le opzioni di caricamento."
type: docs
weight: 70
url: /it/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Rappresenta le opzioni di caricamento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Ottiene la modalità di recupero dati. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Imposta la modalità di recupero dati. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Ottiene il `Color` di sfondo dell'`Image`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Imposta il `Color` di sfondo dell'`Image`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Ottiene un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Imposta un valore che indica se la conversione del profilo ICC deve essere applicata. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Aggiunge la fonte di font personalizzata per fornire font specifici dell'immagine. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Ottiene un valore che indica se [concurrent image processing]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Imposta un valore che indica se [concurrent image processing]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Ottiene la modalità di recupero dati.

**Returns:**
int - La modalità di recupero dati.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Imposta la modalità di recupero dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di recupero dati. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Ottiene il `Color` di sfondo dell'`Image`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Tipicamente il colore di sfondo viene impostato quando il valore del pixel non può essere recuperato a causa di corruzione dei dati.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Imposta il `Color` di sfondo dell'`Image`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | Il colore di sfondo. |

Tipicamente il colore di sfondo viene impostato quando il valore del pixel non può essere recuperato a causa di corruzione dei dati. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Ottiene un valore che indica se la conversione del profilo ICC deve essere applicata.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Imposta un valore che indica se la conversione del profilo ICC deve essere applicata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Aggiunge la fonte di font personalizzata per fornire font specifici dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | La funzione fornitore della fonte di font personalizzata. |
| args | java.lang.Object[] | Gli argomenti. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Restituisce il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Returns:**
int - l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Imposta il suggerimento della dimensione del buffer, che è definito come la dimensione massima consentita per tutti i buffer interni.

Valore: L'indicazione della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | l'indicazione della dimensione del buffer che definisce la dimensione massima consentita per tutti i buffer interni. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
Il seguente esempio mostra come impostare un limite di memoria durante il caricamento di un'immagine JPEG. Il limite di memoria è la dimensione massima consentita (in megabyte) per tutti i buffer interni.
``` java
String workDir = "c:\\temp\\";
// Impostazione di un limite di memoria di 50 megabyte per l'immagine caricata di destinazione
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


Ottiene un valore che indica se [concurrent image processing].

Valore: `true` se [concurrent image processing]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [concurrent image processing].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Imposta un valore che indica se [concurrent image processing].

Valore: `true` se [concurrent image processing]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | il gestore dell'evento di avanzamento. |

