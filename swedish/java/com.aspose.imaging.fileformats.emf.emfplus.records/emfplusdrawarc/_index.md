---
title: "EmfPlusDrawArc"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawArc-posten specificerar ritning av en ellipsbåge."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

EmfPlusDrawArc-posten specificerar ritning av en ellipsbåge.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawArc`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataSize()](#getDataSize--) | Hämtar storleken på data. |
| [setDataSize(int value)](#setDataSize-int-) | Anger storleken på data. |
| [getRectFloat()](#getRectFloat--) | Hämtar ett värde som indikerar om data innehåller EmfPlusRectF- eller EmfPlusRect-poster. Denna bit indikerar om data i fältet RectData är komprimerad. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Anger ett värde som indikerar om data innehåller EmfPlusRectF- eller EmfPlusRect-poster. Denna bit indikerar om data i fältet RectData är komprimerad. |
| [getObjectId()](#getObjectId--) | Hämtar objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Anger objektidentifieraren. |
| [getSize()](#getSize--) | Hämtar storleken. |
| [setSize(int value)](#setSize-int-) | Anger storleken. |
| [getStartAngle()](#getStartAngle--) | Hämtar startvinkeln. Ett 32-bitars icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för bågen. |
| [setStartAngle(float value)](#setStartAngle-float-) | Anger startvinkeln. Ett 32-bitars icke‑negativt flyttal som specificerar vinkeln mellan x‑axeln och startpunkten för bågen. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar svepvinkeln. Ett 32-bitars flyttal som specificerar omfattningen av bågen som ska ritas, som en vinkel i grader mätt från startpunkten definierad av StartAngle‑värdet. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Anger svepvinkeln. Ett 32-bitars flyttal som specificerar omfattningen av bågen som ska ritas, som en vinkel i grader mätt från startpunkten definierad av StartAngle‑värdet. |
| [getRectangleData()](#getRectangleData--) | Hämtar rektangeldata. Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande lådan för ellipsen som är kollinear med bågen. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Anger rektangeldata. Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande lådan för ellipsen som är kollinear med bågen. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawArc`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar storleken på data. Ett 32-bitars osignerat heltal som specificerar det 32-bitars justerade antalet byte av post‑specifik data som följer. För denna posttyp måste värdet vara ett av följande: 0x00000010 om C‑biten är satt i fältet Flags. 0x00000018 om C‑biten är rensad i fältet Flags.

**Returns:**
int - Datastorleken.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Anger storleken på data. Ett 32-bitars osignerat heltal som specificerar det 32-bitars justerade antalet byte av post‑specifik data som följer. För denna posttyp måste värdet vara ett av följande: 0x00000010 om C‑biten är satt i fältet Flags. 0x00000018 om C‑biten är rensad i fältet Flags.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Datastorleken. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Hämtar ett värde som indikerar om data innehåller EmfPlusRectF- eller EmfPlusRect-poster. Denna bit indikerar om data i fältet RectData är komprimerad. Om satt innehåller RectData ett EmfPlusRect‑objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF‑objekt (avsnitt 2.2.2.39).

**Returns:**
boolean – `true` om flytande; annars `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Ställer in ett värde som anger om data innehåller EmfPlusRectF- eller EmfPlusRect-poster. Denna bit anger om data i RectData-fältet är komprimerad. Om satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). Om rensad innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om flyttal; annars `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita bågen. Värdet MÅSTE vara 0 till 63, inklusive.

**Returns:**
byte – Objektidentifieraren.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ställer in objektidentifieraren. Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Object Table för att rita bågen. Värdet MÅSTE vara 0 till 63, inklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Objektidentifieraren. |

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar storleken. En 32-bitars osignerad heltal som specificerar det 32-bitars justerade antalet byte i hela posten, inklusive 12-byte posthuvud och postspecifik data. För denna posttyp måste värdet vara ett av följande: 0x0000001C om C-bit är satt i Flags-fältet. 0x00000024 om C-bit är rensad i Flags-fältet.

**Returns:**
int - Storleken.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Ställer in storleken. En 32-bitars osignerad heltal som specificerar det 32-bitars justerade antalet byte i hela posten, inklusive 12-byte posthuvud och postspecifik data. För denna posttyp måste värdet vara ett av följande: 0x0000001C om C-bit är satt i Flags-fältet. 0x00000024 om C-bit är rensad i Flags-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Storleken. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar startvinkeln. Ett 32-bitars icke-negativt flyttal som specificerar vinkeln mellan x-axeln och startpunkten för bågen. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, med resultatet i intervallet 0,0 inklusive till 360,0 exklusive.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Ställer in startvinkeln. Ett 32-bitars icke-negativt flyttal som specificerar vinkeln mellan x-axeln och startpunkten för bågen. Alla värden är tillåtna, men det MÅSTE tolkas modulo 360, med resultatet i intervallet 0,0 inklusive till 360,0 exklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar svepvinkeln. Ett 32-bitars flyttal som specificerar omfattningen av bågen att rita, som en vinkel i grader mätt från startpunkten som definieras av StartAngle-värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Ställer in svepvinkeln. Ett 32-bitars flyttal som specificerar omfattningen av bågen att rita, som en vinkel i grader mätt från startpunkten som definieras av StartAngle-värdet. Alla värden är tillåtna, men det MÅSTE begränsas till -360,0 till 360,0 inklusive. Ett positivt värde indikerar att svepet definieras i medurs riktning, och ett negativt värde indikerar att svepet definieras i moturs riktning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Hämtar rektangeldata. Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande lådan för ellipsen som är kollinear med bågen. Denna rektangel definierar position, storlek och form på bågen. Typen av objekt i detta fält specificeras av värdet i Flags-fältet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Ställer in rektangeldata. Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande lådan för ellipsen som är kollinear med bågen. Denna rektangel definierar position, storlek och form på bågen. Typen av objekt i detta fält specificeras av värdet i Flags-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

