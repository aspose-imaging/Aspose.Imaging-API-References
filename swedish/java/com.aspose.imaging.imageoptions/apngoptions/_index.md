---
title: "ApngOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Animated PNG (Animated Portable Network Graphics) bildfilformatskapande är ett dynamiskt verktyg för utvecklare som vill generera fängslande animerade bilder."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

API:et för Animated PNG (Animated Portable Network Graphics) bildfilformatskapande är ett dynamiskt verktyg för utvecklare som vill generera fängslande animerade bilder. Med anpassningsbara alternativ såsom bildramslängd och antal gånger att loopa, möjliggör detta API finjustering av animerat innehåll enligt specifika behov. Oavsett om du skapar engagerande webbgrafik eller interaktiva visuella element, kan du utnyttja detta API för att sömlöst integrera APNG-bilder med exakt kontroll över animationsparametrar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Initierar en ny instans av klassen [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Initierar en ny instans av klassen `ApngOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Hämtar antalet gånger animationen ska loopas. |
| [setNumPlays(int value)](#setNumPlays-int-) | Ställer in antalet gånger animationen ska loopas. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Hämtar standardbildramens varaktighet. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Ställer in standardbildramens varaktighet. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportera till APNG-animation med obegränsade animationscykler som standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Ställa in standardramens varaktighet
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Initierar en ny instans av klassen [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Initierar en ny instans av klassen `ApngOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | PNG-alternativen. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Hämtar antalet gånger animationen ska loopas. 0 indikerar oändlig loopning.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportera till APNG-animation med obegränsade animationscykler som standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Ställer in antalet gånger animationen ska loopas. 0 indikerar oändlig loopning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportera till APNG-animation med obegränsade animationscykler som standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Hämtar standardbildramens varaktighet.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Ställer in standardbildramens varaktighet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

