---
title: "EmfPlusStringFormat"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusStringFormat specifica le manipolazioni di visualizzazione del layout del testo e l'identificazione della lingua"
type: docs
weight: 74
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusStringFormat specifica il layout del testo, le manipolazioni di visualizzazione e l'identificazione della lingua
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la lingua da utilizzare per le cifre numeriche nella stringa. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la lingua da utilizzare per le cifre numeriche nella stringa. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire le cifre numeriche nella stringa in base a una locale o lingua. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire le cifre numeriche nella stringa in base a una locale o lingua. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di elaborazione eseguita su una stringa quando viene incontrato un prefisso di scorciatoia da tastiera (cioè, un e commerciale). |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di elaborazione eseguita su una stringa quando viene incontrato un prefisso di scorciatoia da tastiera (cioè, un e commerciale). |
| [getLanguage()](#getLanguage--) | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23) che specifica la lingua da utilizzare per la stringa |
| [setLanguage(short value)](#setLanguage-short-) | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23) che specifica la lingua da utilizzare per la stringa |
| [getLeadingMargin()](#getLeadingMargin--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da aggiungere alla posizione iniziale di una stringa. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da aggiungere alla posizione iniziale di una stringa. |
| [getLineAlign()](#getLineAlign--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare verticalmente la stringa nel rettangolo di layout. |
| [setLineAlign(int value)](#setLineAlign-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare verticalmente la stringa nel rettangolo di layout. |
| [getRangeCount()](#getRangeCount--) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange (sezione 2.2.2.8) definiti nel campo StringFormatData. |
| [setRangeCount(int value)](#setRangeCount-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange (sezione 2.2.2.8) definiti nel campo StringFormatData. |
| [getStringAlignment()](#getStringAlignment--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare orizzontalmente la stringa nel rettangolo di layout. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare orizzontalmente la stringa nel rettangolo di layout. |
| [getStringFormatData()](#getStringFormatData--) | Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44) che specifica dati opzionali di layout del testo. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44) che specifica dati opzionali di layout del testo. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo per la formattazione, il ritaglio e la gestione dei caratteri. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo per la formattazione, il ritaglio e la gestione dei caratteri. |
| [getTabstopCount()](#getTabstopCount--) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni definite nel campo StringFormatData. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni definite nel campo StringFormatData. |
| [getTracking()](#getTracking--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto tra lo spazio orizzontale assegnato a ciascun carattere in una stringa specificata e la larghezza del carattere definita dal carattere. |
| [setTracking(float value)](#setTracking-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto tra lo spazio orizzontale assegnato a ciascun carattere in una stringa specificata e la larghezza del carattere definita dal carattere. |
| [getTrailingMargin()](#getTrailingMargin--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da lasciare dopo una stringa. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da lasciare dopo una stringa. |
| [getTrimming()](#getTrimming--) | Ottiene o imposta che specifica come tagliare i caratteri da una stringa troppo grande per adattarsi a un rettangolo di layout. |
| [setTrimming(int value)](#setTrimming-int-) | Ottiene o imposta che specifica come tagliare i caratteri da una stringa troppo grande per adattarsi a un rettangolo di layout. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la lingua da utilizzare per le cifre numeriche nella stringa. Ad esempio, se questa stringa contiene cifre arabe, questo campo DEVE contenere un identificatore di lingua che specifichi una lingua araba.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la lingua da utilizzare per le cifre numeriche nella stringa. Ad esempio, se questa stringa contiene cifre arabe, questo campo DEVE contenere un identificatore di lingua che specifichi una lingua araba.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire le cifre numeriche nella stringa in base a una locale o lingua. Questo valore DEVE essere definito nell'enumerazione StringDigitSubstitution (sezione 2.1.1.30).

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire le cifre numeriche nella stringa in base a una locale o lingua. Questo valore DEVE essere definito nell'enumerazione StringDigitSubstitution (sezione 2.1.1.30).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di elaborazione eseguita su una stringa quando viene incontrato un prefisso di scorciatoia da tastiera (cioè, un e commerciale). In pratica, questo campo specifica se visualizzare i prefissi di scorciatoia da tastiera relativi al testo. Il valore DEVE essere definito nell'enumerazione HotkeyPrefix (sezione 2.1.1.14).

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di elaborazione eseguita su una stringa quando viene incontrato un prefisso di scorciatoia da tastiera (cioè, un e commerciale). In pratica, questo campo specifica se visualizzare i prefissi di scorciatoia da tastiera relativi al testo. Il valore DEVE essere definito nell'enumerazione HotkeyPrefix (sezione 2.1.1.14).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23) che specifica la lingua da utilizzare per la stringa

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23) che specifica la lingua da utilizzare per la stringa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da aggiungere alla posizione iniziale di una stringa. Il valore predefinito è 1/6 di pollice; per i caratteri tipografici, il valore predefinito è 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da aggiungere alla posizione iniziale di una stringa. Il valore predefinito è 1/6 di pollice; per i caratteri tipografici, il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare verticalmente la stringa nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare verticalmente la stringa nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange (sezione 2.2.2.8) definiti nel campo StringFormatData.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange (sezione 2.2.2.8) definiti nel campo StringFormatData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare orizzontalmente la stringa nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment (sezione 2.1.1.29).

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare orizzontalmente la stringa nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment (sezione 2.1.1.29).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44) che specifica dati opzionali di layout del testo.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44) che specifica dati opzionali di layout del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo per formattazione, ritaglio e gestione dei caratteri. Questo valore DEVE essere composto da flag StringFormat (sezione 2.1.2.8).

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo per formattazione, ritaglio e gestione dei caratteri. Questo valore DEVE essere composto da flag StringFormat (sezione 2.1.2.8).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni definite nel campo StringFormatData.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni definite nel campo StringFormatData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto tra lo spazio orizzontale assegnato a ciascun carattere in una stringa specificata e la larghezza del carattere definita dal font. Valori elevati per questa proprietà indicano ampio spazio tra i caratteri; valori inferiori a 1 possono provocare sovrapposizione dei caratteri. Il valore predefinito è 1,03; per i font tipografici, il valore predefinito è 1,00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto tra lo spazio orizzontale assegnato a ciascun carattere in una stringa specificata e la larghezza del carattere definita dal font. Valori elevati per questa proprietà indicano ampio spazio tra i caratteri; valori inferiori a 1 possono provocare sovrapposizione dei caratteri. Il valore predefinito è 1,03; per i font tipografici, il valore predefinito è 1,00.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da lasciare dopo una stringa. Il valore predefinito è 1/6 di pollice; per i font tipografici, il valore predefinito è 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da lasciare dopo una stringa. Il valore predefinito è 1/6 di pollice; per i font tipografici, il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ottiene o imposta specifica come tagliare i caratteri da una stringa troppo grande per entrare in un rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringTrimming (sezione 2.1.1.31).

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ottiene o imposta specifica come tagliare i caratteri da una stringa troppo grande per entrare in un rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringTrimming (sezione 2.1.1.31).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

