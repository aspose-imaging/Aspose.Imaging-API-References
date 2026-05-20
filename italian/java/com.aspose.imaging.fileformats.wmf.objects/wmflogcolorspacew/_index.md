---
title: "WmfLogColorSpaceW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogColorSpaceW specifica uno spazio colore logico che può essere definito da un file di profilo colore con un nome composto da caratteri Unicode a 16 bit."
type: docs
weight: 45
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

L'oggetto LogColorSpaceW specifica uno spazio colore logico, che può essere definito da un file di profilo colore con un nome costituito da caratteri Unicode a 16 bit.

Vedi l'oggetto `WmfLogColorSpace` (sezione 2.2.2.11) per ulteriori dettagli riguardo l'interpretazione dei valori dei campi di questo oggetto.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
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
| [getFilename()](#getFilename--) | Ottiene o imposta una stringa di caratteri Unicode UTF16-LE opzionale, terminata da null, che specifica il nome di un file che contiene un profilo colore. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Ottiene o imposta una stringa di caratteri Unicode UTF16-LE opzionale, terminata da null, che specifica il nome di un file che contiene un profilo colore. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
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


Ottiene o imposta una stringa di caratteri Unicode UTF16-LE opzionale, terminata da null, che specifica il nome di un file che contiene un profilo colore. Se viene specificato un nome file e il campo `ColorSpaceType` è impostato a LCS\_CALIBRATED\_RGB, gli altri campi di questa struttura DOVREBBERO essere ignorati.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Ottiene o imposta una stringa di caratteri Unicode UTF16-LE opzionale, terminata da null, che specifica il nome di un file che contiene un profilo colore. Se viene specificato un nome file e il campo `ColorSpaceType` è impostato a LCS\_CALIBRATED\_RGB, gli altri campi di questa struttura DOVREBBERO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

