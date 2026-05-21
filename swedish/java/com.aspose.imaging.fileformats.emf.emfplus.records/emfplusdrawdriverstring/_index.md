---
title: "EmfPlusDrawDriverString"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusDrawDriverString-posten specificerar textutmatning med teckenpositioner."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

EmfPlusDrawDriverString-posten specificerar textutmatning med teckenpositioner.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusDrawDriverString`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectId()](#getObjectId--) | Hämtar objektidentifieraren. |
| [setObjectId(byte value)](#setObjectId-byte-) | Anger objektidentifieraren. |
| [getBrushId()](#getBrushId--) | Hämtar penselidentifieraren. Ett 32‑bitars osignerat heltal som specificerar antingen förgrundsfärgen för texten eller en grafikpensel, beroende på värdet av S‑flaggan i Flags |
| [setBrushId(int value)](#setBrushId-int-) | Ställer in penselidentifieraren Ett 32-bitars osignerat heltal som specificerar antingen förgrundsfärgen för texten eller en grafikpensel, beroende på värdet av S‑flaggan i Flags |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Hämtar drivrutinssträngalternativflaggorna Ett 32-bitars osignerat heltal som specificerar avstånd, orientering och renderingskvalitet för strängen. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Ställer in drivrutinssträngalternativflaggorna Ett 32-bitars osignerat heltal som specificerar avstånd, orientering och renderingskvalitet för strängen. |
| [getGlyphCount()](#getGlyphCount--) | Hämtar glyfantalet Ett 32-bitars osignerat heltal som specificerar antalet glyfer i strängen |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Ställer in glyfantalet Ett 32-bitars osignerat heltal som specificerar antalet glyfer i strängen |
| [getGlyphPos()](#getGlyphPos--) | Hämtar glyfpositionsarrayen En array av EmfPlusPointF‑objekt (avsnitt 2.2.2.36) som specificerar utskriftspositionen för varje teckenglyf. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Ställer in glyfpositionsarrayen En array av EmfPlusPointF‑objekt (avsnitt 2.2.2.36) som specificerar utskriftspositionen för varje teckenglyf. |
| [getGlyphs()](#getGlyphs--) | Hämtar glyfarrayen En array av 16‑bitars värden som definierar textsträngen att rita. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Ställer in glyfarrayen En array av 16‑bitars värden som definierar textsträngen att rita. |
| [isColor()](#isColor--) | Hämtar eller anger ett värde som indikerar om denna instans är färg. |
| [setColor(boolean value)](#setColor-boolean-) | Ställer in ett värde som indikerar om detta objekt är färg. |
| [getMatrixPresent()](#getMatrixPresent--) | Hämtar om matris‑present‑flaggan Ett 32-bitars osignerat heltal som specificerar om en transformmatris finns i TransformMatrix‑fältet 0 – ingen matris närvarande. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Ställer in om matris‑present‑flaggan Ett 32-bitars osignerat heltal som specificerar om en transformmatris finns i TransformMatrix‑fältet 0 – ingen matris närvarande. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar transformmatrisen Ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar transformationen som ska tillämpas på varje värde i textarrayen. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Ställer in transformmatrisen Ett valfritt EmfPlusTransformMatrix‑objekt (avsnitt 2.2.2.47) som specificerar transformationen som ska tillämpas på varje värde i textarrayen. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusDrawDriverString`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Hämtar objektidentifieraren. EMF+ Object Table‑indexet för ett ``‑objekt (avsnitt 2.2.1.3) för att rendera texten. Värdet MÅSTE vara 0 till 63, inklusive.

**Returns:**
byte – Objektidentifieraren.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ställer in objektidentifieraren. EMF+ Object Table‑indexet för ett ``‑objekt (avsnitt 2.2.1.3) för att rendera texten. Värdet MÅSTE vara 0 till 63, inklusive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Objektidentifieraren. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Hämtar penselidentifieraren. Ett 32‑bitars osignerat heltal som specificerar antingen förgrundsfärgen för texten eller en grafikpensel, beroende på värdet av S‑flaggan i Flags

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ställer in penselidentifieraren Ett 32-bitars osignerat heltal som specificerar antingen förgrundsfärgen för texten eller en grafikpensel, beroende på värdet av S‑flaggan i Flags

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Hämtar drivrutinssträngalternativflaggorna Ett 32-bitars osignerat heltal som specificerar avstånd, orientering och renderingskvalitet för strängen.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Ställer in drivrutinssträngalternativflaggorna Ett 32-bitars osignerat heltal som specificerar avstånd, orientering och renderingskvalitet för strängen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Hämtar glyfantalet Ett 32-bitars osignerat heltal som specificerar antalet glyfer i strängen

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Ställer in glyfantalet Ett 32-bitars osignerat heltal som specificerar antalet glyfer i strängen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Hämtar glyfpositionsarrayen En array av EmfPlusPointF‑objekt (avsnitt 2.2.2.36) som specificerar utskriftspositionen för varje teckenglyf. Det MÅSTE finnas GlyphCount‑element, som har en en‑till‑en‑korrespondens med elementen i Glyphs‑arrayen. Glyfpositioner beräknas från positionen för den första glyfen om flaggan DriverStringOptionsRealizedAdvance i DriverStringOptions‑flaggorna är satt. I detta fall specificerar GlyphPos endast positionen för den första glyfen.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Ställer in glyfpositionsarrayen En array av EmfPlusPointF‑objekt (avsnitt 2.2.2.36) som specificerar utskriftspositionen för varje teckenglyf. Det MÅSTE finnas GlyphCount‑element, som har en en‑till‑en‑korrespondens med elementen i Glyphs‑arrayen. Glyfpositioner beräknas från positionen för den första glyfen om flaggan DriverStringOptionsRealizedAdvance i DriverStringOptions‑flaggorna är satt. I detta fall specificerar GlyphPos endast positionen för den första glyfen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Hämtar glyfarrayen En array av 16‑bitars värden som definierar textsträngen att rita. Om flaggan DriverStringOptionsCmapLookup i fältet DriverStringOptionsFlags är satt, specificerar varje värde i denna array ett Unicode‑tecken. Annars specificerar varje värde ett index till ett teckenglyf i EmfPlusFont‑objektet som anges av ObjectId‑värdet i Flags‑fältet.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Ställer in glyfarrayen En array av 16‑bitars värden som definierar textsträngen att rita. Om flaggan DriverStringOptionsCmapLookup i fältet DriverStringOptionsFlags är satt, specificerar varje värde i denna array ett Unicode‑tecken. Annars specificerar varje värde ett index till ett teckenglyf i EmfPlusFont‑objektet som anges av ObjectId‑värdet i Flags‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Hämtar eller ställer in ett värde som indikerar om detta objekt är färg. Denna bit anger vilken typ av data som finns i BrushId‑fältet. Om satt, specificerar BrushId färgvärdet i ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad, innehåller BrushId EMF+ Object Table‑indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1).

**Returns:**
boolean – `true` om detta objekt är färg; annars `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ställer in ett värde som indikerar om detta objekt är färg. Denna bit anger vilken typ av data som finns i BrushId‑fältet. Om satt, specificerar BrushId färgvärdet i ett EmfPlusARGB‑objekt (avsnitt 2.2.2.1). Om rensad, innehåller BrushId EMF+ Object Table‑indexet för ett EmfPlusBrush‑objekt (avsnitt 2.2.1.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om detta objekt är färg; annars `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Hämtar om flaggan för matrisens närvaro A 32-bitars osignerad heltal som specificerar huruvida en transformmatris finns i fältet TransformMatrix 0 - ingen matris närvarande. 1 - transformmatris finns i fältet TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Ställer in om flaggan för matrisens närvaro En 32-bitars osignerad heltal som specificerar huruvida en transformmatris finns i fältet TransformMatrix 0 - ingen matris närvarande. 1 - transformmatris finns i fältet TransformMatrix.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Hämtar transformmatrisen Ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationen som ska tillämpas på varje värde i textarrayen. Närvaron av dessa data bestäms från fältet MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Ställer in transformmatrisen Ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar transformationen som ska tillämpas på varje värde i textarrayen. Närvaron av dessa data bestäms från fältet MatrixPresent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

