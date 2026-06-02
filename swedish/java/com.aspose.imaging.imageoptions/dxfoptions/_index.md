---
title: "DxfOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API för Drawing Interchange Format DXF vektorbildsskapande erbjuder skräddarsydda lösningar för att generera AutoCAD-ritningsfiler med precision och flexibilitet."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

API för Drawing Interchange Format (DXF) vektorbildsskapande erbjuder skräddarsydda lösningar för att generera AutoCAD-ritningsfiler med precision och flexibilitet. Speciellt utformat för arbete med textlinjer och Bézierkurvor kan utvecklare effektivt manipulera dessa element, räkna Bézier-punkter och konvertera kurvor till polylinjer för sömlös export, vilket säkerställer kompatibilitet och noggrannhet i DXF-vektorbilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Kopieringskonstruktor |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Hur många punkter som ska genereras när Bezier‑kurvor konverteras till polylinjer, minst 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Hur många punkter som ska genereras när Bezier‑kurvor konverteras till polylinjer, minst 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Fungerar när \#textAsLines är satt till `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Fungerar när \#textAsLines är satt till `true`. |
| [getTextAsLines()](#getTextAsLines--) | Om text ska exporteras som konturer bestående av polylinjer (standard) eller som redigerbara Autocad TEXT‑entiteter. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Om text ska exporteras som konturer bestående av polylinjer (standard) eller som redigerbara Autocad TEXT‑entiteter. |

## Example: This example demonstrates export to Dxf format

``` java

//Skapa en Image-instans och initiera den med en befintlig bildfil från en diskplats.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Kopieringskonstruktor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Källalternativen för kopiering |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Hur många punkter som ska genereras när Bezier‑kurvor konverteras till polylinjer, minst 4. Används när (/) och (/) båda /// är satta till `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Hur många punkter som ska genereras när Bezier‑kurvor konverteras till polylinjer, minst 4. Används när (/) och (/) båda /// är satta till `true`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Fungerar när \#textAsLines är satt till `true`. Om Bezier‑kurvor i textkonturer ska konverteras till multipunkt‑polylinjer.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Fungerar när \#textAsLines är satt till `true`. Om Bezier‑kurvor i textkonturer ska konverteras till multipunkt‑polylinjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Om text ska exporteras som konturer bestående av polylinjer (standard) eller som redigerbara Autocad TEXT‑entiteter. Om detta alternativ är satt

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Om text ska exporteras som konturer bestående av polylinjer (standard) eller som redigerbara Autocad TEXT‑entiteter. Om detta alternativ är satt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

