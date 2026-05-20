---
title: "Os22XBitmapHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Un OS/2 2.x OS22XBITMAPHEADER, noto anche come BITMAPCOREHEADER2."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

Un OS/2 2.x OS22XBITMAPHEADER, noto anche come BITMAPCOREHEADER2.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUnits()](#getUnits--) | Restituisce le unità. |
| [getReserved()](#getReserved--) | Restituisce il riservato. |
| [getRecording()](#getRecording--) | Restituisce la registrazione. |
| [getRendering()](#getRendering--) | Restituisce il rendering. |
| [getSize1()](#getSize1--) | Restituisce la dimensione1. |
| [getSize2()](#getSize2--) | Restituisce la dimensione2. |
| [getColorEncoding()](#getColorEncoding--) | Restituisce la codifica colore. |
| [getIdentifier()](#getIdentifier--) | Restituisce l'identificatore. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Restituisce le unità.

**Returns:**
int - Tipo di unità utilizzate per misurare la risoluzione
### getReserved() {#getReserved--}
```
public int getReserved()
```


Restituisce il riservato.

**Returns:**
int - Struttura di padding a un allineamento di 4 byte
### getRecording() {#getRecording--}
```
public int getRecording()
```


Restituisce la registrazione.

**Returns:**
int - Algoritmo di registrazione
### getRendering() {#getRendering--}
```
public int getRendering()
```


Restituisce il rendering.

**Returns:**
int - Algoritmo di mezzitoni utilizzato
### getSize1() {#getSize1--}
```
public int getSize1()
```


Restituisce la dimensione1.

**Returns:**
int - Riservato per l'uso dell'algoritmo di mezzitoni
### getSize2() {#getSize2--}
```
public int getSize2()
```


Restituisce la dimensione2.

**Returns:**
int - Riservato per l'uso dell'algoritmo di mezzitoni
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Restituisce la codifica colore.

**Returns:**
int - Modello di colore utilizzato nel bitmap
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Restituisce l'identificatore.

**Returns:**
int - Riservato per l'uso dell'applicazione
