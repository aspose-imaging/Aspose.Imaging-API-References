---
title: "Font"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un formato specifico per il testo includendo la dimensione del carattere e gli attributi di stile."
type: docs
weight: 48
url: /it/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Inizializza un nuovo `com.aspose.imaging.Font` che utilizza il `com.aspose.imaging.Font` esistente specificato e l'enumerazione `com.aspose.imaging.FontStyle`. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione specificata. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione e uno stile specificati. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione, uno stile, un'unità e un set di caratteri specificati. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione, uno stile e un'unità specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione e un'unità specificati. |
| [getBold()](#getBold--) | Restituisce un valore che indica se questo `Font` è in grassetto. |
| [getCharacterSet()](#getCharacterSet--) | Restituisce un valore byte che specifica il set di caratteri utilizzato da questo `Font`. |
| [getItalic()](#getItalic--) | Restituisce un valore che indica se questo `Font` è in corsivo. |
| [getName()](#getName--) | Restituisce il nome del tipo di carattere di questo `Font`. |
| [getStrikeout()](#getStrikeout--) | Restituisce un valore che indica se questo `Font` specifica una linea orizzontale attraverso il carattere. |
| [getUnderline()](#getUnderline--) | Restituisce un valore che indica se questo `Font` è sottolineato. |
| [getStyle()](#getStyle--) | Restituisce le informazioni di stile per questo `Font`. |
| [getSize()](#getSize--) | Restituisce la dimensione em di questo `Font` misurata nelle unità specificate dalla proprietà `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | Ottiene l'unità di misura per questo `Font`. |
| [deepClone()](#deepClone--) | Crea una copia profonda esatta di questo `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indica se l'oggetto specificato è un `com.aspose.imaging.Font` e ha gli stessi valori delle proprietà di questo `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Ottiene il codice hash per questo `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile da un umano di questo `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Questo esempio dimostra l'uso delle classi Font e SolidBrush per disegnare stringhe sulla superficie dell'Image. L'esempio crea una nuova Image e disegna forme usando Figures e GraphicsPath.
``` java
//Crea un'istanza di BmpOptions e imposta le sue varie proprietà.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
//Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crea un'istanza di Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inizializza un'istanza della classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Cancella la superficie di Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea un'istanza di Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crea un'istanza di SolidBrush con colore rosso
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Disegna una stringa
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // salva tutte le modifiche
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Inizializza un nuovo `com.aspose.imaging.Font` che utilizza il `com.aspose.imaging.Font` esistente specificato e l'enumerazione `com.aspose.imaging.FontStyle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Il `com.aspose.imaging.Font` esistente da cui creare il nuovo `com.aspose.imaging.Font`. |
| newStyle | int | Il `com.aspose.imaging.FontStyle` da applicare al nuovo `com.aspose.imaging.Font`. Più valori dell'enumerazione `com.aspose.imaging.FontStyle` possono essere combinati con l'operatore OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Inizializza un nuovo `com.aspose.imaging.Font` utilizzando una dimensione specificata. Il set di caratteri è impostato su `F:Aspose.Imaging.CharacterSet.Default`, l'unità grafica su `F:Aspose.Imaging.GraphicsUnit.Point`, lo stile del font su `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del `com.aspose.imaging.Font`. |
| emSize | float | L'em-size, in punti, del nuovo font. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Inizializza un nuovo `com.aspose.imaging.Font` utilizzando una dimensione e uno stile specificati. Il set di caratteri è impostato su `F:Aspose.Imaging.CharacterSet.Default`, l'unità grafica su `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del `com.aspose.imaging.Font`. |
| emSize | float | L'em-size, in punti, del nuovo font. |
| style | int | Il `com.aspose.imaging.FontStyle` del nuovo font. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione, uno stile, un'unità e un set di caratteri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del `com.aspose.imaging.Font`. |
| emSize | float | L'em-size del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il `com.aspose.imaging.FontStyle` del nuovo font. |
| unit | int | L'`com.aspose.imaging.GraphicsUnit` del nuovo font. |
| characterSet | int | Un set di caratteri da utilizzare per questo font. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione, uno stile e un'unità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del `com.aspose.imaging.Font`. |
| emSize | float | L'em-size del nuovo font nelle unità specificate dal parametro `unit`. |
| style | int | Il `com.aspose.imaging.FontStyle` del nuovo font. |
| unit | int | L'`com.aspose.imaging.GraphicsUnit` del nuovo font. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Inizializza un nuovo `com.aspose.imaging.Font` usando una dimensione e un'unità specificate. Il set di caratteri è impostato su `F:Aspose.Imaging.CharacterSet.Default`, lo stile è impostato su `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Una rappresentazione stringa del nome del `com.aspose.imaging.Font`. |
| emSize | float | L'em-size del nuovo font nelle unità specificate dal parametro `unit`. |
| unit | int | L'`com.aspose.imaging.GraphicsUnit` del nuovo font. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Restituisce un valore che indica se questo `Font` è in grassetto.

**Returns:**
boolean - True se questo `Font` è in grassetto; altrimenti, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Restituisce un valore byte che specifica il set di caratteri utilizzato da questo `Font`.

**Returns:**
int - Un set di caratteri che questo `Font` utilizza.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Restituisce un valore che indica se questo `Font` è in corsivo.

**Returns:**
boolean - True se questo `Font` è in corsivo; altrimenti, false.
### getName() {#getName--}
```
public String getName()
```


Restituisce il nome del tipo di carattere di questo `Font`.

**Returns:**
java.lang.String - Una rappresentazione stringa del nome del tipo di carattere di questo `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Restituisce un valore che indica se questo `Font` specifica una linea orizzontale attraverso il carattere.

**Returns:**
boolean - True se questo `Font` ha una linea orizzontale attraverso di esso; altrimenti, false.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Restituisce un valore che indica se questo `Font` è sottolineato.

**Returns:**
boolean - True se questo `Font` è sottolineato; altrimenti, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Restituisce le informazioni di stile per questo `Font`.

**Returns:**
int - Un'enumerazione `FontStyle` che contiene informazioni di stile per questo `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Restituisce la dimensione em di questo `Font` misurata nelle unità specificate dalla proprietà `P:Aspose.Imaging.Font.Unit`.

**Returns:**
float - La dimensione em di questo `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Ottiene l'unità di misura per questo `Font`.

**Returns:**
int - Un `GraphicsUnit` che rappresenta l'unità di misura per questo `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Crea una copia profonda esatta di questo `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indica se l'oggetto specificato è un `com.aspose.imaging.Font` e ha gli stessi valori delle proprietà di questo `com.aspose.imaging.Font`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - True se il parametro `obj` è un `com.aspose.imaging.Font` e ha gli stessi valori delle proprietà di questo `com.aspose.imaging.Font`; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash per questo `com.aspose.imaging.Font`.

**Returns:**
int - Il codice hash per questo `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile da un umano di questo `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - Una stringa che rappresenta questo `com.aspose.imaging.Font`.
