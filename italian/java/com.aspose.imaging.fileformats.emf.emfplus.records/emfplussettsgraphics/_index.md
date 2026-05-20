---
title: "EmfPlusSetTsGraphics"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetTSGraphics specifica lo stato di un contesto del dispositivo grafico per un server terminale."
type: docs
weight: 67
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

Il record EmfPlusSetTSGraphics specifica lo stato di un contesto del dispositivo grafico per un server terminale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetTsGraphics`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Ottiene un valore che indica se [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Ottiene un valore che indica se [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering delle linee, incluso il tipo di anti-aliasing delle linee. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering delle linee, incluso il tipo di anti-aliasing delle linee. |
| [getTextRenderHint()](#getTextRenderHint--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering del testo, incluso il tipo di anti-aliasing del testo. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering del testo, incluso il tipo di anti-aliasing del testo. |
| [getCompositingMode()](#getCompositingMode--) | Ottiene o imposta un intero senza segno a 8 bit che specifica come i colori di origine vengono combinati con i colori di sfondo. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica come i colori di origine vengono combinati con i colori di sfondo. |
| [getCompositingQuality()](#getCompositingQuality--) | Ottiene o imposta un intero senza segno a 8 bit che specifica il grado di smussatura da applicare a linee, curve e ai bordi delle aree riempite per farle apparire più continue o nettamente definite. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica il grado di smussatura da applicare a linee, curve e ai bordi delle aree riempite per farle apparire più continue o nettamente definite. |
| [getRenderOriginX()](#getRenderOriginX--) | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata orizzontale dell'origine per il rendering di reticoli di mezzitoni e dithering. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata orizzontale dell'origine per il rendering di reticoli di mezzitoni e dithering. |
| [getRenderOriginY()](#getRenderOriginY--) | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata verticale dell'origine per il rendering di reticoli di mezzitoni e dithering. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Ottiene o imposta un intero con segno a 16 bit, che è la coordinata verticale dell'origine per il rendering di reticoli di mezzitoni e dithering. |
| [getTextContrast()](#getTextContrast--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma usato per il rendering di testo anti-aliasing e ClearType. |
| [setTextContrast(short value)](#setTextContrast-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma usato per il rendering di testo anti-aliasing e ClearType. |
| [getFilterType()](#getFilterType--) | Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguita la scalatura, inclusi allungamento e riduzione. |
| [setFilterType(byte value)](#setFilterType-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguita la scalatura, inclusi allungamento e riduzione. |
| [getPixelOffset()](#getPixelOffset--) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine e del processo di rendering del testo. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine e del processo di rendering del testo. |
| [getWorldToDevice()](#getWorldToDevice--) | Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che specifica le trasformazioni dallo spazio mondo allo spazio dispositivo. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che specifica le trasformazioni dallo spazio mondo allo spazio dispositivo. |
| [getPalette()](#getPalette--) | Ottiene o imposta un oggetto EmfPlusPalette opzionale. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Ottiene o imposta un oggetto EmfPlusPalette opzionale. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetTsGraphics`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Ottiene un valore che indica se [basic vga colors]. Se impostato, la tavolozza contiene solo i colori VGA di base.

Valore: `true` se [basic vga colors]; altrimenti, `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Ottiene un valore che indica se [have palette]. Se impostato, questo record contiene un oggetto EmfPlusPalette (sezione 2.2.2.28) nel campo Palette dopo i dati dello stato grafico.

Valore: `true` se [have palette]; altrimenti, `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering delle linee, inclusa il tipo di anti-aliasing delle linee. Deve essere definito nell'enumerazione SmoothingMode (sezione 2.1.1.28).

Valore: La modalità anti-alias.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering delle linee, inclusa il tipo di anti-aliasing delle linee. Deve essere definito nell'enumerazione SmoothingMode (sezione 2.1.1.28).

Valore: La modalità anti-alias.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering del testo, inclusa il tipo di anti-aliasing del testo. Deve essere definito nell'enumerazione TextRenderingHint (sezione 2.1.1.32).

Valore: L'indicazione di rendering del testo.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità del rendering del testo, inclusa il tipo di anti-aliasing del testo. Deve essere definito nell'enumerazione TextRenderingHint (sezione 2.1.1.32).

Valore: L'indicazione di rendering del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica come i colori di origine vengono combinati con i colori di sfondo. Deve essere un valore nell'enumerazione CompositingMode (sezione 2.1.1.5).

Valore: La modalità di composizione.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica come i colori di origine vengono combinati con i colori di sfondo. Deve essere un valore nell'enumerazione CompositingMode (sezione 2.1.1.5).

Valore: La modalità di composizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica il grado di smussatura da applicare a linee, curve e ai bordi delle aree riempite per farle apparire più continue o nettamente definite. Deve essere un valore nell'enumerazione CompositingQuality (sezione 2.1.1.6).

Valore: La qualità di composizione.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica il grado di smussatura da applicare a linee, curve e ai bordi delle aree riempite per farle apparire più continue o nettamente definite. Deve essere un valore nell'enumerazione CompositingQuality (sezione 2.1.1.6).

Valore: La qualità di composizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Ottiene o imposta un intero con segno a 16 bit, che è la coordinata orizzontale dell'origine per il rendering di reticoli di mezzitoni e dithering.

Valore: L'origine di rendering x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Ottiene o imposta un intero con segno a 16 bit, che è la coordinata orizzontale dell'origine per il rendering di reticoli di mezzitoni e dithering.

Valore: L'origine di rendering x.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Ottiene o imposta un intero con segno a 16 bit, che è la coordinata verticale dell'origine per il rendering di reticoli di mezzitoni e dithering.

Valore: L'origine di rendering y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Ottiene o imposta un intero con segno a 16 bit, che è la coordinata verticale dell'origine per il rendering di reticoli di mezzitoni e dithering.

Valore: L'origine di rendering y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma utilizzato per il rendering del testo anti-alias e ClearType. Questo valore DEVE essere compreso nell'intervallo da 0 a 12, inclusi.

Valore: Il contrasto del testo.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma utilizzato per il rendering del testo anti-alias e ClearType. Questo valore DEVE essere compreso nell'intervallo da 0 a 12, inclusi.

Valore: Il contrasto del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguita la scalatura, inclusi allungamento e riduzione. Deve essere un valore nell'enumerazione FilterType (sezione 2.1.1.11).

Valore: Il tipo di filtro.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica come viene eseguita la scalatura, inclusi allungamento e riduzione. Deve essere un valore nell'enumerazione FilterType (sezione 2.1.1.11).

Valore: Il tipo di filtro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine e del processo di rendering del testo. Deve essere un valore nell'enumerazione PixelOffsetMode (sezione 2.1.1.26).

Valore: L'offset dei pixel.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità complessiva dell'immagine e del processo di rendering del testo. Deve essere un valore nell'enumerazione PixelOffsetMode (sezione 2.1.1.26).

Valore: L'offset dei pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che specifica le trasformazioni dallo spazio mondo allo spazio dispositivo.

Valore: Il mondo al dispositivo.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix a 192 bit (sezione 2.2.2.47) che specifica le trasformazioni dallo spazio mondo allo spazio dispositivo.

Valore: Il mondo al dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Ottiene o imposta un oggetto EmfPlusPalette opzionale.

Valore: La tavolozza.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Ottiene o imposta un oggetto EmfPlusPalette opzionale.

Valore: La tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

