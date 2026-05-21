---
title: "CustomLineCap"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inkapslar en anpassad användardefinierad linjeändpunkt."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Inkapslar en anpassad användardefinierad linjeändpunkt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Initierar en ny instans av `CustomLineCap`-klassen med den angivna konturen och fyllningen. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Initierar en ny instans av `CustomLineCap`-klassen från den angivna befintliga `LineCap`-enumerationen med den angivna konturen och fyllningen. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Initierar en ny instans av `CustomLineCap`-klassen från den angivna befintliga `LineCap`-enumerationen med den angivna konturen, fyllningen och insättningen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillPath()](#getFillPath--) | Hämtar objektet som definierar fyllningen för den anpassade toppen. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Ställer in objektet som definierar fyllningen för den anpassade spetsen. |
| [getStrokePath()](#getStrokePath--) | Hämtar objektet som definierar konturen för den anpassade spetsen. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Ställer in objektet som definierar konturen för den anpassade spetsen. |
| [getStrokeJoin()](#getStrokeJoin--) | Hämtar `LineJoin`-enumerationen som bestämmer hur linjer som utgör detta `CustomLineCap`-objekt sammanfogas. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Ställer in `LineJoin`-enumerationen som bestämmer hur linjer som utgör detta `CustomLineCap`-objekt sammanfogas. |
| [getBaseCap()](#getBaseCap--) | Hämtar `LineCap`-enumerationen som detta `CustomLineCap` är baserat på. |
| [setBaseCap(int value)](#setBaseCap-int-) | Ställer in `LineCap`-enumerationen som detta `CustomLineCap` är baserat på. |
| [getBaseInset()](#getBaseInset--) | Hämtar avståndet mellan spetsen och linjen. |
| [setBaseInset(float value)](#setBaseInset-float-) | Ställer in avståndet mellan spetsen och linjen. |
| [getWidthScale()](#getWidthScale--) | Hämtar mängden med vilken detta `CustomLineCap`-klassobjekt ska skalas i förhållande till bredden på `System.Drawing.Pen`-objektet. |
| [setWidthScale(float value)](#setWidthScale-float-) | Ställer in mängden med vilken detta `CustomLineCap`-klassobjekt ska skalas i förhållande till bredden på `System.Drawing.Pen`-objektet. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Ställer in spetsarna som används för att starta och avsluta linjer som utgör denna anpassade spets. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Hämtar spetsarna som används för att starta och avsluta linjer som utgör denna anpassade spets. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initierar en ny instans av `CustomLineCap`-klassen med den angivna konturen och fyllningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar konturen för den anpassade spetsen. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initierar en ny instans av `CustomLineCap`-klassen från den angivna befintliga `LineCap`-enumerationen med den angivna konturen och fyllningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar konturen för den anpassade spetsen. |
| baseCap | int | Linjespetsen som den anpassade spetsen ska skapas från. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initierar en ny instans av `CustomLineCap`-klassen från den angivna befintliga `LineCap`-enumerationen med den angivna konturen, fyllningen och insättningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar fyllningen för den anpassade spetsen. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Ett `GraphicsPath`-objekt som definierar konturen för den anpassade spetsen. |
| baseCap | int | Linjespetsen som den anpassade spetsen ska skapas från. |
| baseInset | float | Avståndet mellan spetsen och linjen. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Hämtar objektet som definierar fyllningen för den anpassade toppen.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Ställer in objektet som definierar fyllningen för den anpassade spetsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Objektet som definierar fyllningen för den anpassade spetsen. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Hämtar objektet som definierar konturen för den anpassade spetsen.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Ställer in objektet som definierar konturen för den anpassade spetsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Objektet som definierar konturen för den anpassade spetsen. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Hämtar `LineJoin`-enumerationen som bestämmer hur linjer som utgör detta `CustomLineCap`-objekt sammanfogas.

**Returns:**
int - `LineJoin`-enumerationen som detta `CustomLineCap`-objekt använder för att sammanfoga linjer.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Ställer in `LineJoin`-enumerationen som bestämmer hur linjer som utgör detta `CustomLineCap`-objekt sammanfogas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | `LineJoin`-enumerationen som detta `CustomLineCap`-objekt använder för att sammanfoga linjer. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Hämtar `LineCap`-enumerationen som detta `CustomLineCap` är baserat på.

**Returns:**
int - `LineCap`-enumerationen som detta `CustomLineCap` är baserat på.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Ställer in `LineCap`-enumerationen som detta `CustomLineCap` är baserat på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | `LineCap`-enumerationen som detta `CustomLineCap` är baserat på. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Hämtar avståndet mellan spetsen och linjen.

**Returns:**
float - Avståndet mellan början av spetsen och slutet av linjen.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Ställer in avståndet mellan spetsen och linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Avståndet mellan början av spetsen och slutet av linjen. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Hämtar mängden med vilken detta `CustomLineCap`-klassobjekt ska skalas i förhållande till bredden på `System.Drawing.Pen`-objektet.

**Returns:**
float - Mängden som spetsen ska skalas med.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Ställer in mängden med vilken detta `CustomLineCap`-klassobjekt ska skalas i förhållande till bredden på `System.Drawing.Pen`-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Mängden som spetsen ska skalas med. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Ställer in spetsarna som används för att starta och avsluta linjer som utgör denna anpassade spets.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int | Den `LineCap`-enumerationen som används i början av en linje inom denna spets. |
| endCap | int | Den `LineCap`-enumerationen som används i slutet av en linje inom denna spets. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Hämtar spetsarna som används för att starta och avsluta linjer som utgör denna anpassade spets.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int[] | Den `LineCap`-enumerationen som används i början av en linje inom denna spets. |
| endCap | int[] | Den `LineCap`-enumerationen som används i slutet av en linje inom denna spets. |

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
