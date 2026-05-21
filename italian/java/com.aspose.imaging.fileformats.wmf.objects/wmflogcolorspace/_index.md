---
title: "WmfLogColorSpace"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogColorSpace specifica uno spazio colore logico per il contesto del dispositivo di riproduzione, che può essere il nome di un profilo colore in caratteri ASCII."
type: docs
weight: 44
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpace extends MetaObject
```

L'oggetto LogColorSpace specifica uno spazio colore logico per il contesto del dispositivo di riproduzione, che può essere il nome di un profilo colore in caratteri ASCII.

I campi Endpoints, GammaRed, GammaGreen e GammaBlue sono usati per specificare uno spazio colore logico. Il campo Endpoints è un oggetto CIEXYZTriple che contiene i valori x, y e z del punto finale RGB dello spazio colore. La relazione tra i valori tri‑stimolo X,Y,Z e i valori di cromaticità x,y,z è espressa come segue. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) I campi GammaRed, GammaGreen e GammaBlue contengono valori nel formato "8.8 fixed point", che è una tecnica per rappresentare numeri non interi. Cada valore è composto da una magnitudine a 8 bit estesa a zero seguita da una frazione a 8 bit, con i 16 bit combinati spostati a sinistra di 8 bit. Pertanto, in 32 bit, il valore reale N.F è 00000000nnnnnnnnffffffff00000000, dove "nnnnnnnn" e "ffffffff" sono le rappresentazioni binarie di N e F, rispettivamente. Per esempio, per il numero reale 10.5, nnnnnnnn sarebbe 00001010 (binario 10) e ffffffff sarebbe 00000101 (binario 5), e il valore binario a 32 bit completo sarebbe 00000000000010100000010100000000, che è il valore esadecimale 0x0A50.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfLogColorSpace()](#WmfLogColorSpace--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSignature()](#getSignature--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la `signature` degli oggetti spazio colore; DEVE essere impostato al valore 0x50534F43, che è la codifica ASCII della stringa "PSOC". |
| [setSignature(int value)](#setSignature-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la `signature` degli oggetti spazio colore; DEVE essere impostato al valore 0x50534F43, che è la codifica ASCII della stringa "PSOC". |
| [getVersion()](#getVersion--) | Ottiene o imposta un intero senza segno a 32 bit che definisce un numero di `version`; DEVE essere 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce un numero di `version`; DEVE essere 0x00000400. |
| [getSize()](#getSize--) | Ottiene o imposta un intero senza segno a 32 bit che definisce la `size` di questo oggetto, in byte. |
| [setSize(int value)](#setSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che definisce la `size` di questo oggetto, in byte. |
| [getColorSpaceType()](#getColorSpaceType--) | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di spazio colore. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di spazio colore. |
| [getIntent()](#getIntent--) | Ottiene o imposta un intero con segno a 32 bit che definisce l'intento di mappatura del gamut. |
| [setIntent(int value)](#setIntent-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce l'intento di mappatura del gamut. |
| [getEndpoints()](#getEndpoints--) | Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce le coordinate di cromaticità CIE x, y e z dei tre colori che corrispondono agli `endpoints` RGB per lo spazio colore logico associato al bitmap. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce le coordinate di cromaticità CIE x, y e z dei tre colori che corrispondono agli `endpoints` RGB per lo spazio colore logico associato al bitmap. |
| [getGammaRed()](#getGammaRed--) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il rosso. |
| [setGammaRed(int value)](#setGammaRed-int-) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il rosso. |
| [getGammaGreen()](#getGammaGreen--) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il verde. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il verde. |
| [getGammaBlue()](#getGammaBlue--) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il blu. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il blu. |
| [getFilename()](#getFilename--) | Ottiene o imposta una stringa ASCII opzionale che specifica il nome di un file che contiene un profilo colore. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Ottiene o imposta una stringa ASCII opzionale che specifica il nome di un file che contiene un profilo colore. |
### WmfLogColorSpace() {#WmfLogColorSpace--}
```
public WmfLogColorSpace()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la `signature` degli oggetti spazio colore; DEVE essere impostato al valore 0x50534F43, che è la codifica ASCII della stringa "PSOC".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la `signature` degli oggetti spazio colore; DEVE essere impostato al valore 0x50534F43, che è la codifica ASCII della stringa "PSOC".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce un numero di `version`; DEVE essere 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce un numero di `version`; DEVE essere 0x00000400.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la `size` di questo oggetto, in byte.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che definisce la `size` di questo oggetto, in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di spazio colore. DEVE essere definito nell'enumerazione LogicalColorSpace (sezione 2.1.1.14). Se questo valore è LCS\_sRGB o LCS\_WINDOWS\_COLOR\_SPACE, lo spazio colore sRGB DEVE essere usato.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di spazio colore. DEVE essere definito nell'enumerazione LogicalColorSpace (sezione 2.1.1.14). Se questo valore è LCS\_sRGB o LCS\_WINDOWS\_COLOR\_SPACE, lo spazio colore sRGB DEVE essere usato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Ottiene o imposta un intero con segno a 32 bit che definisce l'intento di mappatura del gamut. DEVE essere definito nell'enumerazione GamutMappingIntent (sezione 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce l'intento di mappatura del gamut. DEVE essere definito nell'enumerazione GamutMappingIntent (sezione 2.1.1.11).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce le coordinate di cromaticità CIE x, y e z dei tre colori che corrispondono agli `endpoints` RGB per lo spazio colore logico associato al bitmap. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce le coordinate di cromaticità CIE x, y e z dei tre colori che corrispondono agli `endpoints` RGB per lo spazio colore logico associato al bitmap. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il rosso. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il rosso. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il verde. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il verde. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il blu. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Ottiene o imposta un valore a punto fisso a 32 bit che definisce la curva di risposta tonificata per il blu. Se il campo `ColorSpaceType` non specifica LCS\_CALIBRATED\_RGB, questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Ottiene o imposta una stringa ASCII opzionale che specifica il nome di un file che contiene un profilo colore. Se viene specificato un nome file e il campo `ColorSpaceType` è impostato a LCS\_CALIBRATED\_RGB, gli altri campi di questa struttura DOVREBBERO essere ignorati.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Ottiene o imposta una stringa ASCII opzionale che specifica il nome di un file che contiene un profilo colore. Se viene specificato un nome file e il campo `ColorSpaceType` è impostato a LCS\_CALIBRATED\_RGB, gli altri campi di questa struttura DOVREBBERO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

