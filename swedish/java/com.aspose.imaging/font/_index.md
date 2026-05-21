---
title: "Teckensnitt"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar ett specifikt format för text inklusive teckensnitt, storlek och stilattribut."
type: docs
weight: 48
url: /sv/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | Initierar ett nytt `com.aspose.imaging.Font` som använder den angivna befintliga `com.aspose.imaging.Font` och `com.aspose.imaging.FontStyle`-enumerationen. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek och stil. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek, stil, enhet och teckenuppsättning. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek, stil och enhet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek och enhet. |
| [getBold()](#getBold--) | Hämtar ett värde som indikerar om detta `Font` är fetstil. |
| [getCharacterSet()](#getCharacterSet--) | Hämtar ett bytevärde som specificerar teckenuppsättningen som detta `Font` använder. |
| [getItalic()](#getItalic--) | Hämtar ett värde som indikerar om detta `Font` är kursiv. |
| [getName()](#getName--) | Hämtar teckensnittsnamnet för detta `Font`. |
| [getStrikeout()](#getStrikeout--) | Hämtar ett värde som indikerar om detta `Font` specificerar en horisontell linje genom teckensnittet. |
| [getUnderline()](#getUnderline--) | Hämtar ett värde som indikerar om detta `Font` är understruket. |
| [getStyle()](#getStyle--) | Hämtar stilinformation för detta `Font`. |
| [getSize()](#getSize--) | Hämtar em-storleken för detta `Font` mätt i de enheter som anges av egenskapen `P:Aspose.Imaging.Font.Unit`. |
| [getUnit()](#getUnit--) | Hämtar måttenheten för detta `Font`. |
| [deepClone()](#deepClone--) | Skapar en exakt djup kopia av detta `Font`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om det angivna objektet är en `com.aspose.imaging.Font` och har samma egenskapsvärden som denna `com.aspose.imaging.Font`. |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för denna `com.aspose.imaging.Font`. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av denna `com.aspose.imaging.Font`. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Detta exempel demonstrerar användningen av Font‑ och SolidBrush‑klassen för att rita strängar på en Image‑yta. Exemplet skapar en ny Image och ritar former med Figures och GraphicsPath.
``` java
//Skapar en instans av BmpOptions och sätter dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
//Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Skapar en instans av Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Skapar och initierar en instans av Graphics‑klassen
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Rensar Graphics‑ytan
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Skapar en instans av Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Rita en sträng
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // spara alla ändringar
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Initierar ett nytt `com.aspose.imaging.Font` som använder den angivna befintliga `com.aspose.imaging.Font` och `com.aspose.imaging.FontStyle`-enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | Den befintliga `com.aspose.imaging.Font` som den nya `com.aspose.imaging.Font` ska skapas från. |
| newStyle | int | Den `com.aspose.imaging.FontStyle` som ska tillämpas på den nya `com.aspose.imaging.Font`. Flera värden i `com.aspose.imaging.FontStyle`‑enumerationen kan kombineras med OR‑operatorn. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Initierar en ny `com.aspose.imaging.Font` med en angiven storlek. Teckenuppsättningen sätts till `F:Aspose.Imaging.CharacterSet.Default`, grafik‑enheten till `F:Aspose.Imaging.GraphicsUnit.Point` och teckensnittsstilen till `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av namnet på `com.aspose.imaging.Font`. |
| emSize | float | Em‑storleken, i punkter, för det nya teckensnittet. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Initierar en ny `com.aspose.imaging.Font` med en angiven storlek och stil. Teckenuppsättningen sätts till `F:Aspose.Imaging.CharacterSet.Default` och grafik‑enheten till `F:Aspose.Imaging.GraphicsUnit.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av namnet på `com.aspose.imaging.Font`. |
| emSize | float | Em‑storleken, i punkter, för det nya teckensnittet. |
| style | int | `com.aspose.imaging.FontStyle` för det nya teckensnittet. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek, stil, enhet och teckenuppsättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av namnet på `com.aspose.imaging.Font`. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av `unit`‑parametern. |
| style | int | `com.aspose.imaging.FontStyle` för det nya teckensnittet. |
| unit | int | Den `com.aspose.imaging.GraphicsUnit` för det nya teckensnittet. |
| characterSet | int | En teckenuppsättning att använda för detta teckensnitt. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek, stil och enhet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av namnet på `com.aspose.imaging.Font`. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av `unit`‑parametern. |
| style | int | `com.aspose.imaging.FontStyle` för det nya teckensnittet. |
| unit | int | Den `com.aspose.imaging.GraphicsUnit` för det nya teckensnittet. |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Initierar ett nytt `com.aspose.imaging.Font` med en angiven storlek och enhet. Teckenuppsättningen sätts till `F:Aspose.Imaging.CharacterSet.Default`, stilen sätts till `F:Aspose.Imaging.FontStyle.Regular`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | En strängrepresentation av namnet på `com.aspose.imaging.Font`. |
| emSize | float | Em‑storleken för det nya teckensnittet i de enheter som anges av `unit`‑parametern. |
| unit | int | Den `com.aspose.imaging.GraphicsUnit` för det nya teckensnittet. |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


Hämtar ett värde som indikerar om detta `Font` är fetstil.

**Returns:**
boolean - Sant om detta `Font` är fetstil; annars falskt.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Hämtar ett bytevärde som specificerar teckenuppsättningen som detta `Font` använder.

**Returns:**
int - En teckenuppsättning som detta `Font` använder.
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Hämtar ett värde som indikerar om detta `Font` är kursiv.

**Returns:**
boolean - Sant om detta `Font` är kursiv; annars falskt.
### getName() {#getName--}
```
public String getName()
```


Hämtar teckensnittsnamnet för detta `Font`.

**Returns:**
java.lang.String - En strängrepresentation av teckensnittets namn för detta `Font`.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Hämtar ett värde som indikerar om detta `Font` specificerar en horisontell linje genom teckensnittet.

**Returns:**
boolean - Sant om detta `Font` har ett horisontellt streck igenom; annars falskt.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Hämtar ett värde som indikerar om detta `Font` är understruket.

**Returns:**
boolean - Sant om detta `Font` är understruket; annars falskt.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Hämtar stilinformation för detta `Font`.

**Returns:**
int - En `FontStyle`-enumeration som innehåller stilinformation för detta `Font`.
### getSize() {#getSize--}
```
public float getSize()
```


Hämtar em-storleken för detta `Font` mätt i de enheter som anges av egenskapen `P:Aspose.Imaging.Font.Unit`.

**Returns:**
float - Em-storleken för detta `Font`.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Hämtar måttenheten för detta `Font`.

**Returns:**
int - En `GraphicsUnit` som representerar måttenheten för detta `Font`.
### deepClone() {#deepClone--}
```
public Font deepClone()
```


Skapar en exakt djup kopia av detta `Font`.

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om det angivna objektet är en `com.aspose.imaging.Font` och har samma egenskapsvärden som denna `com.aspose.imaging.Font`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Sant om parametern `obj` är en `com.aspose.imaging.Font` och har samma egenskapsvärden som detta `com.aspose.imaging.Font`; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för denna `com.aspose.imaging.Font`.

**Returns:**
int - Hashkoden för detta `com.aspose.imaging.Font`.
### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av denna `com.aspose.imaging.Font`.

**Returns:**
java.lang.String - En sträng som representerar detta `com.aspose.imaging.Font`.
