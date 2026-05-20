---
title: "WmfBitmapInfoHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto BitmapInfoHeader contiene informazioni sulle dimensioni e sul formato colore di un bitmap indipendente dal dispositivo DIB."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

L'oggetto BitmapInfoHeader contiene informazioni sulle dimensioni e sul formato colore di un bitmap indipendente dal dispositivo (DIB).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | La dimensione della struttura |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. |
| [getHeight()](#getHeight--) | Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. |
| [getCompression()](#getCompression--) | Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. |
| [setCompression(int value)](#setCompression-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. |
| [getImageSize()](#getImageSize--) | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine. |
| [setImageSize(int value)](#setImageSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo di destinazione per il DIB |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo di destinazione per il DIB |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo di destinazione per il DIB |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo di destinazione per il DIB |
| [getColorUsed()](#getColorUsed--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tavola dei colori usata dal DIB, come segue: se questo valore è zero, il DIB utilizza il numero massimo di colori corrispondente al valore BitCount. |
| [setColorUsed(int value)](#setColorUsed-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tavola dei colori usata dal DIB, come segue: se questo valore è zero, il DIB utilizza il numero massimo di colori corrispondente al valore BitCount. |
| [getColorImportant()](#getColorImportant--) | Ottiene o imposta un intero senza segno a 32 bit che definisce il numero di indici di colore richiesti per visualizzare il DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce il numero di indici di colore richiesti per visualizzare il DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


La dimensione della struttura

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. Questo valore DEVE essere positivo. Questo campo DOVREBBE specificare la larghezza del file immagine decompressa, se il valore Compression specifica il formato JPEG o PNG.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. Questo valore DEVE essere positivo. Questo campo DOVREBBE specificare la larghezza del file immagine decompressa, se il valore Compression specifica il formato JPEG o PNG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. Questo valore NON DEVE essere zero. Se questo valore è positivo, il DIB è un bitmap bottom‑up e la sua origine è l'angolo inferiore sinistro. Se questo valore è negativo, il DIB è un bitmap top‑down e la sua origine è l'angolo superiore sinistro. I bitmap top‑down non supportano la compressione. Questo campo DOVREBBE specificare l'altezza del file immagine decompressa, se il valore Compression specifica il formato JPEG o PNG.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. Questo valore NON DEVE essere zero. Se questo valore è positivo, il DIB è un bitmap bottom‑up e la sua origine è l'angolo inferiore sinistro. Se questo valore è negativo, il DIB è un bitmap top‑down e la sua origine è l'angolo superiore sinistro. I bitmap top‑down non supportano la compressione. Questo campo DOVREBBE specificare l'altezza del file immagine decompressa, se il valore Compression specifica il formato JPEG o PNG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. Questo valore DEVE appartenere all'Enumerazione Compression (sezione 2.1.1.7). Questo valore NON DEVE specificare un formato compresso se il DIB è un bitmap top‑down, come indicato dal valore Height.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. Questo valore DEVE appartenere all'Enumerazione Compression (sezione 2.1.1.7). Questo valore NON DEVE specificare un formato compresso se il DIB è un bitmap top‑down, come indicato dal valore Height.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine. Se il valore Compression è BI\_RGB, questo valore DOVREBBE essere zero e DEVE essere ignorato. Se il valore Compression è BI\_JPEG o BI\_PNG, questo valore DEVE specificare la dimensione del buffer immagine JPEG o PNG, rispettivamente.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine. Se il valore Compression è BI\_RGB, questo valore DOVREBBE essere zero e DEVE essere ignorato. Se il valore Compression è BI\_JPEG o BI\_PNG, questo valore DEVE specificare la dimensione del buffer immagine JPEG o PNG, rispettivamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo di destinazione per il DIB

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo di destinazione per il DIB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo di destinazione per il DIB

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo di destinazione per il DIB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tavola dei colori usata dal DIB, come segue: se questo valore è zero, il DIB utilizza il numero massimo di colori corrispondente al valore BitCount. Se questo valore è diverso da zero e il valore BitCount è inferiore a 16, questo valore specifica il numero di colori usati dal DIB. Se questo valore è diverso da zero e il valore BitCount è 16 o superiore, questo valore specifica la dimensione della tavola dei colori usata per ottimizzare le prestazioni della palette di sistema. Nota: se questo valore è diverso da zero e maggiore della dimensione massima possibile della tavola dei colori basata sul valore BitCount, si DEVE assumere la dimensione massima della tavola dei colori.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tavola dei colori usata dal DIB, come segue: se questo valore è zero, il DIB utilizza il numero massimo di colori corrispondente al valore BitCount. Se questo valore è diverso da zero e il valore BitCount è inferiore a 16, questo valore specifica il numero di colori usati dal DIB. Se questo valore è diverso da zero e il valore BitCount è 16 o superiore, questo valore specifica la dimensione della tavola dei colori usata per ottimizzare le prestazioni della palette di sistema. Nota: se questo valore è diverso da zero e maggiore della dimensione massima possibile della tavola dei colori basata sul valore BitCount, si DEVE assumere la dimensione massima della tavola dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce il numero di indici di colore richiesti per visualizzare il DIB. Se questo valore è zero, tutti gli indici di colore sono richiesti.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce il numero di indici di colore richiesti per visualizzare il DIB. Se questo valore è zero, tutti gli indici di colore sono richiesti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

