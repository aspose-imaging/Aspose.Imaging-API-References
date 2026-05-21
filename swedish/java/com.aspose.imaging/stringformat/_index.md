---
title: "StringFormat"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inkapslar information om textlayout såsom justering, orientering och tabbstopp, samt displaymanipulationer såsom ellipsis-infogning, nationell siffrasubstitution och OpenType-funktioner."
type: docs
weight: 112
url: /sv/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Inkapslar information om textlayout (såsom justering, orientering och tabbstopp) displaymanipulationer (såsom ellipsis-infogning och nationell siffrasubstitution) och OpenType-funktioner. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt. |
| [StringFormat(int options)](#StringFormat-int-) | Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt med den angivna `com.aspose.imaging.StringFormatFlags`-enumerationen och språket. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt från det angivna befintliga `com.aspose.imaging.StringFormat`-objektet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Hämtar ett generiskt standard `com.aspose.imaging.StringFormat`-objekt. |
| [getGenericTypographic()](#getGenericTypographic--) | Hämtar ett generiskt typografiskt `com.aspose.imaging.StringFormat`-objekt. |
| [getFormatFlags()](#getFormatFlags--) | Hämtar en `com.aspose.imaging.StringFormatFlags`-enumeration som innehåller formateringsinformation. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Ställer in en `com.aspose.imaging.StringFormatFlags`-enumeration som innehåller formateringsinformation. |
| [getAlignment()](#getAlignment--) | Hämtar information om textjustering på den vertikala planet. |
| [setAlignment(int value)](#setAlignment-int-) | Ställer in information om textjustering på den vertikala planet. |
| [getLineAlignment()](#getLineAlignment--) | Hämtar radjusteringen på det horisontella planet. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Ställer in radjusteringen på det horisontella planet. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Hämtar `com.aspose.imaging.HotkeyPrefix`-objektet för detta `com.aspose.imaging.StringFormat`-objekt. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ställer in `com.aspose.imaging.HotkeyPrefix`-objektet för detta `com.aspose.imaging.StringFormat`-objekt. |
| [getTrimming()](#getTrimming--) | Hämtar `com.aspose.imaging.StringTrimming`-enumerationen för detta `com.aspose.imaging.StringFormat`-objekt. |
| [setTrimming(int value)](#setTrimming-int-) | Ställer in `com.aspose.imaging.StringTrimming`-enumerationen för detta `com.aspose.imaging.StringFormat`-objekt. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Hämtar metoden som ska användas för siffrors substitution. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Ställer in metoden som ska användas för siffrors substitution. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Hämtar språket som används när lokala siffror ersätts med västerländska siffror. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Ställer in språket som används när lokala siffror ersätts med västerländska siffror. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| [getTabStops()](#getTabStops--) | Hämtar en array av avstånd mellan tabbstopp i de enheter som anges av egenskapen `P:Aspose.Imaging.getGraphics().PageUnit`. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Hämtar den anpassade teckenidentifikatorn. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Ställer in den anpassade teckenidentifikatorn. |
| [deepClone()](#deepClone--) | Skapar en djup klon av detta `com.aspose.imaging.StringFormat`-objekt. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Ställer in tabbstopp för detta `com.aspose.imaging.StringFormat`-objekt. |
| [toString()](#toString--) | Konverterar detta `com.aspose.imaging.StringFormat`-objekt till en människoläsbar sträng. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt med den angivna `com.aspose.imaging.StringFormatFlags`-enumerationen och språket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativ | int | Den `com.aspose.imaging.StringFormatFlags`-enumerationen för det nya `com.aspose.imaging.StringFormat`-objektet. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initierar ett nytt `com.aspose.imaging.StringFormat`-objekt från det angivna befintliga `com.aspose.imaging.StringFormat`-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | Det `com.aspose.imaging.StringFormat`-objektet som ska användas för att initiera det nya `com.aspose.imaging.StringFormat`-objektet. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Hämtar ett generiskt standard `com.aspose.imaging.StringFormat`-objekt.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Hämtar ett generiskt typografiskt `com.aspose.imaging.StringFormat`-objekt.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Hämtar en `com.aspose.imaging.StringFormatFlags`-enumeration som innehåller formateringsinformation.

**Returns:**
int - En `com.aspose.imaging.StringFormatFlags` enumeration som innehåller formateringsinformation.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Ställer in en `com.aspose.imaging.StringFormatFlags`-enumeration som innehåller formateringsinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `com.aspose.imaging.StringFormatFlags` enumeration som innehåller formateringsinformation. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Hämtar information om textjustering på den vertikala planet.

**Returns:**
int - En `com.aspose.imaging.StringAlignment` enumeration som specificerar information om textjustering.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ställer in information om textjustering på den vertikala planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `com.aspose.imaging.StringAlignment` enumeration som specificerar information om textjustering. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Hämtar radjusteringen på det horisontella planet.

**Returns:**
int - En `com.aspose.imaging.StringAlignment` enumeration som representerar radjusteringen.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Ställer in radjusteringen på det horisontella planet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `com.aspose.imaging.StringAlignment` enumeration som representerar radjusteringen. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Hämtar `com.aspose.imaging.HotkeyPrefix`-objektet för detta `com.aspose.imaging.StringFormat`-objekt.

**Returns:**
int - Objektet `com.aspose.imaging.HotkeyPrefix` för detta `com.aspose.imaging.StringFormat`-objekt, standardvärdet är `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ställer in `com.aspose.imaging.HotkeyPrefix`-objektet för detta `com.aspose.imaging.StringFormat`-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Objektet `com.aspose.imaging.HotkeyPrefix` för detta `com.aspose.imaging.StringFormat`-objekt, standardvärdet är `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Hämtar `com.aspose.imaging.StringTrimming`-enumerationen för detta `com.aspose.imaging.StringFormat`-objekt.

**Returns:**
int - En `com.aspose.imaging.StringTrimming` enumeration som anger hur text som ritas med detta `com.aspose.imaging.StringFormat`-objekt beskärs när den överskrider layoutrektangelns kanter.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ställer in `com.aspose.imaging.StringTrimming`-enumerationen för detta `com.aspose.imaging.StringFormat`-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En `com.aspose.imaging.StringTrimming` enumeration som anger hur text som ritas med detta `com.aspose.imaging.StringFormat`-objekt beskärs när den överskrider layoutrektangelns kanter. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Hämtar metoden som ska användas för siffrors substitution.

**Returns:**
int - En `com.aspose.imaging.StringDigitSubstitute` enumeration‑värde som specificerar hur tecken i en sträng som inte kan visas eftersom de inte stöds av det aktuella teckensnittet ska ersättas.

Settern introduceras för den föråldrade metoden SetDigitSubstitution.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Ställer in metoden som ska användas för siffrors substitution.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | En `com.aspose.imaging.StringDigitSubstitute` enumeration‑värde som specificerar hur tecken i en sträng som inte kan visas eftersom de inte stöds av det aktuella teckensnittet ska ersättas. |

Settern introduceras för den föråldrade metoden SetDigitSubstitution. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Hämtar språket som används när lokala siffror ersätts med västerländska siffror.

**Returns:**
int - En National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka `P:System.Globalization.CultureInfo.LCID`-egenskapen för ett `System.Globalization.CultureInfo`-objekt som NLS-språkidentifierare. Till exempel, anta att du skapar och ställer in en lokal \"ar-EG\". Om du skickar `com.aspose.imaging.StringDigitSubstitute.Traditional` till `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`‑metoden, kommer arabiskt‑indiska siffror att ersättas med västerländska siffror vid visning.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Ställer in språket som används när lokala siffror ersätts med västerländska siffror.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En National Language Support (NLS) språkidentifierare som identifierar språket som kommer att användas när lokala siffror ersätts med västerländska siffror. Du kan skicka `P:System.Globalization.CultureInfo.LCID`-egenskapen för ett `System.Globalization.CultureInfo`-objekt som NLS-språkidentifierare. Till exempel, anta att du skapar och ställer in en lokal \"ar-EG\". Om du skickar `com.aspose.imaging.StringDigitSubstitute.Traditional` till `com.aspose.imaging.StringFormat.setDigitSubstitution(int)`‑metoden, kommer arabiskt‑indiska siffror att ersättas med västerländska siffror vid visning. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet.

**Returns:**
float - Det första tabulatoravståndet.

Egenskapen introduceras för den borttagna metoden GetTabStops.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Hämtar en array av avstånd mellan tabbstopp i de enheter som anges av egenskapen `P:Aspose.Imaging.getGraphics().PageUnit`.

**Returns:**
float[] - Tabulatorstopp.

Egenskapen introduceras för den borttagna metoden GetTabStops.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Hämtar den anpassade teckenidentifikatorn.

Värde: Den anpassade teckenidentifieraren.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Ställer in den anpassade teckenidentifikatorn.

Värde: Den anpassade teckenidentifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | den anpassade teckenidentifieraren. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Skapar en djup klon av detta `com.aspose.imaging.StringFormat`-objekt.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Ställer in tabbstopp för detta `com.aspose.imaging.StringFormat`-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstTabOffset | float | Antalet mellanslag mellan början av en textrad och den första tabulatorstoppen. |
| tabStops | float[] | En array av avstånd mellan tabulatorstopp i de enheter som anges av egenskapen `com.aspose.imaging.Graphics.PageUnit`. |

### toString() {#toString--}
```
public String toString()
```


Konverterar detta `com.aspose.imaging.StringFormat`-objekt till en människoläsbar sträng.

**Returns:**
java.lang.String - En strängrepresentation av detta `com.aspose.imaging.StringFormat`-objekt.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
