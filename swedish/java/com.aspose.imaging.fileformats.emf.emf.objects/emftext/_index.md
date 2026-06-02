---
title: "EmfText"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmrText-objektet innehåller värden för textutmatning."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

EmrText-objektet innehåller värden för textutmatning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getReference()](#getReference--) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar koordinaterna för referenspunkten som används för att placera strängen. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar koordinaterna för referenspunkten som används för att placera strängen. |
| [getChars()](#getChars--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen |
| [setChars(int value)](#setChars-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen |
| [getOptions()](#getOptions--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur rektangeln angiven i Rectangle-fältet ska användas. |
| [setOptions(int value)](#setOptions-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur rektangeln angiven i Rectangle-fältet ska användas. |
| [getRectangle()](#getRectangle--) | Hämtar eller anger ett valfritt WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en beskärnings- och/eller opakningsrektangel i logiska enheter. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett valfritt WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en beskärnings- och/eller opakningsrektangel i logiska enheter. |
| [getStringBuffer()](#getStringBuffer--) | Hämtar eller anger teckensträngsbufferten UndefinedSpace1 (variabel): Ett valfritt antal oanvända byte. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Hämtar eller anger teckensträngsbufferten UndefinedSpace1 (variabel): Ett valfritt antal oanvända byte. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Hämtar den valfria glyfindexbufferten. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Ställer in den valfria glyfindexbufferten. |
| [getDxBuffer()](#getDxBuffer--) | Hämtar eller anger den valfria teckenavståndsbufferten UndefinedSpace2 (variabel): Ett valfritt antal oanvända byte. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Hämtar eller anger den valfria teckenavståndsbufferten UndefinedSpace2 (variabel): Ett valfritt antal oanvända byte. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar koordinaterna för referenspunkten som används för att placera strängen. Referenspunkten definieras av den sista EMR\_SETTEXTALIGN-posten (avsnitt 2.3.11.25). Om ingen sådan post har angetts är standardjusteringen TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar koordinaterna för referenspunkten som används för att placera strängen. Referenspunkten definieras av den sista EMR\_SETTEXTALIGN-posten (avsnitt 2.3.11.25). Om ingen sådan post har angetts är standardjusteringen TA\_LEFT,TA\_TOP.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet tecken i strängen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur rektangeln angiven i Rectangle-fältet ska användas. Detta fält kan vara en kombination av mer än ett värde från ExtTextOutOptions‑enumerationen (avsnitt 2.1.11).

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur rektangeln angiven i Rectangle-fältet ska användas. Detta fält kan vara en kombination av mer än ett värde från ExtTextOutOptions‑enumerationen (avsnitt 2.1.11).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Hämtar eller anger ett valfritt WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en beskärnings- och/eller opakningsrektangel i logiska enheter. Denna rektangel tillämpas på textutdata som utförs av den innehållande posten.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Hämtar eller anger ett valfritt WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en beskärnings- och/eller opakningsrektangel i logiska enheter. Denna rektangel tillämpas på textutdata som utförs av den innehållande posten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Hämtar eller anger teckensträngsbufferten UndefinedSpace1 (variabel): Ett valfritt antal oanvända byte. OutputString-fältet behöver inte följa omedelbart den föregående delen av denna struktur. OutputString (variabel): En matris av tecken som specificerar strängen att skriva ut. Platsen för detta fält anges av värdet av offString i byte från början av posten. Antalet tecken anges av värdet av Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Hämtar eller anger teckensträngsbufferten UndefinedSpace1 (variabel): Ett valfritt antal oanvända byte. OutputString-fältet behöver inte följa omedelbart den föregående delen av denna struktur. OutputString (variabel): En matris av tecken som specificerar strängen att skriva ut. Platsen för detta fält anges av värdet av offString i byte från början av posten. Antalet tecken anges av värdet av Chars.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Hämtar den valfria glyfindexbufferten. Om alternativ har flaggan ETO\_GLYPH\_INDEX så är koderna för tecken i en utmatad textsträng faktiskt index för teckenglyfer i ett TrueType-typsnitt (2.1.11 ExtTextOutOptions‑enumeration). Glyfindex är typsnittsspecifika, så för att visa rätt tecken vid uppspelning måste det använda typsnittet vara identiskt med det typsnitt som användes för att generera indexen.

**Returns:**
int[] – den valfria glyfindexbufferten.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Ställer in den valfria glyfindexbufferten. Om alternativ har flaggan ETO\_GLYPH\_INDEX så är koderna för tecken i en utmatad textsträng faktiskt index för teckenglyfer i ett TrueType-typsnitt (2.1.11 ExtTextOutOptions‑enumeration). Glyfindex är typsnittsspecifika, så för att visa rätt tecken vid uppspelning måste det använda typsnittet vara identiskt med det typsnitt som användes för att generera indexen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | den valfria glyfindexbufferten. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Hämtar eller anger den valfria teckenavståndsbufferten UndefinedSpace2 (variabel): Ett valfritt antal oanvända byte. OutputDx-fältet behöver inte följa omedelbart den föregående delen av denna struktur. OutputDx (variabel): En matris av 32-bitars osignerade heltal som specificerar avståndet mellan ursprungen för intilliggande teckenceller i logiska enheter. Platsen för detta fält anges av värdet av offDx i byte från början av posten. Om avstånd definieras innehåller detta fält samma antal värden som tecken i utmatningssträngen. Om Options-fältet i EmrText-objektet innehåller flaggan ETO\_PDY, innehåller denna buffer dubbelt så många värden som det finns tecken i utmatningssträngen, ett horisontellt och ett vertikalt offset för varje, i den ordningen. Om ETO\_RTLREADING anges läggs tecken från höger till vänster istället för från vänster till höger. Inga andra alternativ påverkar tolkningen av detta fält.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Hämtar eller anger den valfria teckenavståndsbufferten UndefinedSpace2 (variabel): Ett valfritt antal oanvända byte. OutputDx-fältet behöver inte följa omedelbart den föregående delen av denna struktur. OutputDx (variabel): En matris av 32-bitars osignerade heltal som specificerar avståndet mellan ursprungen för intilliggande teckenceller i logiska enheter. Platsen för detta fält anges av värdet av offDx i byte från början av posten. Om avstånd definieras innehåller detta fält samma antal värden som tecken i utmatningssträngen. Om Options-fältet i EmrText-objektet innehåller flaggan ETO\_PDY, innehåller denna buffer dubbelt så många värden som det finns tecken i utmatningssträngen, ett horisontellt och ett vertikalt offset för varje, i den ordningen. Om ETO\_RTLREADING anges läggs tecken från höger till vänster istället för från vänster till höger. Inga andra alternativ påverkar tolkningen av detta fält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

