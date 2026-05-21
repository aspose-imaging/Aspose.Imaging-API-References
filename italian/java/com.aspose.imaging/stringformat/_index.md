---
title: "StringFormat"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Incapsula le informazioni di layout del testo, come l'allineamento, l'orientamento e le tabulazioni, e le manipolazioni di visualizzazione come l'inserimento di ellissi, la sostituzione di cifre nazionali e le funzionalità OpenType."
type: docs
weight: 112
url: /it/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Incapsula le informazioni di layout del testo (come allineamento, orientamento e tabulazioni), le manipolazioni di visualizzazione (come l'inserimento di ellissi e la sostituzione di cifre nazionali) e le funzionalità OpenType. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StringFormat()](#StringFormat--) | Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat`. |
| [StringFormat(int options)](#StringFormat-int-) | Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat` con l'enumerazione `com.aspose.imaging.StringFormatFlags` specificata e la lingua. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat` a partire dall'oggetto `com.aspose.imaging.StringFormat` esistente specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Restituisce un oggetto `com.aspose.imaging.StringFormat` generico predefinito. |
| [getGenericTypographic()](#getGenericTypographic--) | Ottiene un oggetto tipografico generico `com.aspose.imaging.StringFormat`. |
| [getFormatFlags()](#getFormatFlags--) | Ottiene un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Imposta un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione. |
| [getAlignment()](#getAlignment--) | Ottiene informazioni sull'allineamento del testo sul piano verticale. |
| [setAlignment(int value)](#setAlignment-int-) | Imposta informazioni sull'allineamento del testo sul piano verticale. |
| [getLineAlignment()](#getLineAlignment--) | Ottiene l'allineamento della linea sul piano orizzontale. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Imposta l'allineamento della linea sul piano orizzontale. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ottiene l'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Imposta l'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`. |
| [getTrimming()](#getTrimming--) | Ottiene l'enumerazione `com.aspose.imaging.StringTrimming` per questo oggetto `com.aspose.imaging.StringFormat`. |
| [setTrimming(int value)](#setTrimming-int-) | Imposta l'enumerazione `com.aspose.imaging.StringTrimming` per questo oggetto `com.aspose.imaging.StringFormat`. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ottiene il metodo da utilizzare per la sostituzione delle cifre. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Imposta il metodo da utilizzare per la sostituzione delle cifre. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ottiene la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Ottiene il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore. |
| [getTabStops()](#getTabStops--) | Ottiene un array di distanze tra i tabulatori nelle unità specificate dalla proprietà `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Ottiene l'identificatore del carattere personalizzato. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Imposta l'identificatore del carattere personalizzato. |
| [deepClone()](#deepClone--) | Crea una copia profonda di questo oggetto `com.aspose.imaging.StringFormat`. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Imposta i tabulatori per questo oggetto `com.aspose.imaging.StringFormat`. |
| [toString()](#toString--) | Converte questo oggetto `com.aspose.imaging.StringFormat` in una stringa leggibile dall'uomo. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat`.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat` con l'enumerazione `com.aspose.imaging.StringFormatFlags` specificata e la lingua.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| opzioni | int | L'enumerazione `com.aspose.imaging.StringFormatFlags` per il nuovo oggetto `com.aspose.imaging.StringFormat`. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Inizializza un nuovo oggetto `com.aspose.imaging.StringFormat` a partire dall'oggetto `com.aspose.imaging.StringFormat` esistente specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | L'oggetto `com.aspose.imaging.StringFormat` da cui inizializzare il nuovo oggetto `com.aspose.imaging.StringFormat`. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Restituisce un oggetto `com.aspose.imaging.StringFormat` generico predefinito.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ottiene un oggetto tipografico generico `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ottiene un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione.

**Returns:**
int - Un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Imposta un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione `com.aspose.imaging.StringFormatFlags` che contiene informazioni di formattazione. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ottiene informazioni sull'allineamento del testo sul piano verticale.

**Returns:**
int - Un'enumerazione `com.aspose.imaging.StringAlignment` che specifica le informazioni di allineamento del testo.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Imposta informazioni sull'allineamento del testo sul piano verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione `com.aspose.imaging.StringAlignment` che specifica le informazioni di allineamento del testo. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ottiene l'allineamento della linea sul piano orizzontale.

**Returns:**
int - Un'enumerazione `com.aspose.imaging.StringAlignment` che rappresenta l'allineamento della linea.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Imposta l'allineamento della linea sul piano orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione `com.aspose.imaging.StringAlignment` che rappresenta l'allineamento della linea. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ottiene l'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`.

**Returns:**
int - L'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`, il valore predefinito è `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Imposta l'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'oggetto `com.aspose.imaging.HotkeyPrefix` per questo oggetto `com.aspose.imaging.StringFormat`, il valore predefinito è `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ottiene l'enumerazione `com.aspose.imaging.StringTrimming` per questo oggetto `com.aspose.imaging.StringFormat`.

**Returns:**
int - Un'enumerazione `com.aspose.imaging.StringTrimming` che indica come il testo disegnato con questo oggetto `com.aspose.imaging.StringFormat` viene troncato quando supera i bordi del rettangolo di layout.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Imposta l'enumerazione `com.aspose.imaging.StringTrimming` per questo oggetto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un'enumerazione `com.aspose.imaging.StringTrimming` che indica come il testo disegnato con questo oggetto `com.aspose.imaging.StringFormat` viene troncato quando supera i bordi del rettangolo di layout. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ottiene il metodo da utilizzare per la sostituzione delle cifre.

**Returns:**
int - Un valore di enumerazione `com.aspose.imaging.StringDigitSubstitute` che specifica come sostituire i caratteri in una stringa che non può essere visualizzata perché non supportata dal font corrente.

Il setter è introdotto per il metodo obsoleto SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Imposta il metodo da utilizzare per la sostituzione delle cifre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Un valore di enumerazione `com.aspose.imaging.StringDigitSubstitute` che specifica come sostituire i caratteri in una stringa che non può essere visualizzata perché non supportata dal font corrente. |

Il setter è introdotto per il metodo obsoleto SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Ottiene la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali.

**Returns:**
int - Un identificatore di lingua National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà `P:System.Globalization.CultureInfo.LCID` di un oggetto `System.Globalization.CultureInfo` come identificatore di lingua NLS. Per esempio, supponiamo di creare e impostare una locale "ar-EG". Se si passa `com.aspose.imaging.StringDigitSubstitute.Traditional` al metodo `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Imposta la lingua utilizzata quando le cifre locali vengono sostituite con cifre occidentali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un identificatore di lingua National Language Support (NLS) che identifica la lingua da utilizzare quando le cifre locali vengono sostituite con cifre occidentali. È possibile passare la proprietà `P:System.Globalization.CultureInfo.LCID` di un oggetto `System.Globalization.CultureInfo` come identificatore di lingua NLS. Per esempio, supponiamo di creare e impostare una locale "ar-EG". Se si passa `com.aspose.imaging.StringDigitSubstitute.Traditional` al metodo `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`, le cifre arabo-indiane saranno sostituite alle cifre occidentali al momento della visualizzazione. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Ottiene il numero di spazi tra l'inizio di una riga di testo e il primo tabulatore.

**Returns:**
float - Il primo offset di tabulazione.

La proprietà è introdotta per il metodo rimosso GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ottiene un array di distanze tra i tabulatori nelle unità specificate dalla proprietà `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Le tabulazioni.

La proprietà è introdotta per il metodo rimosso GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Ottiene l'identificatore del carattere personalizzato.

Valore: L'identificatore del carattere personalizzato.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Imposta l'identificatore del carattere personalizzato.

Valore: L'identificatore del carattere personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | l'identificatore del carattere personalizzato. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Crea una copia profonda di questo oggetto `com.aspose.imaging.StringFormat`.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Imposta i tabulatori per questo oggetto `com.aspose.imaging.StringFormat`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstTabOffset | float | Il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| tabStops | float[] | Un array di distanze tra le tabulazioni nelle unità specificate dalla proprietà `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


Converte questo oggetto `com.aspose.imaging.StringFormat` in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una rappresentazione testuale di questo oggetto `com.aspose.imaging.StringFormat`.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
