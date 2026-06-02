---
title: "ImageAttributes"
second_title: "Aspose.Imaging för Java API-referens"
description: "Ett com.aspose.imaging.ImageAttributes-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering."
type: docs
weight: 57
url: /sv/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Ett `com.aspose.imaging.ImageAttributes`-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering. Ett `com.aspose.imaging.ImageAttributes`-objekt upprätthåller flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gamma‑korrektionsvärden, färgkartutabeller och färgtröskelvärden. Under rendering kan färger korrigeras, mörkna, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett `com.aspose.imaging.ImageAttributes`-objekt och skicka sökvägen till det `com.aspose.imaging.ImageAttributes`-objektet (tillsammans med sökvägen till en [Image](../../com.aspose.imaging/image)) till drawImage‑metoden.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initierar en ny instans av klassen `com.aspose.imaging.ImageAttributes`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen för en angiven kategori. |
| [clearColorMatrix()](#clearColorMatrix--) | Rensar färgjusteringsmatrisen för standardkategorin. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Rensar färgjusteringsmatrisen för en angiven kategori. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för en angiven kategori. |
| [setThreshold(float threshold)](#setThreshold-float-) | Ställer in tröskelvärdet (transparentintervall) för standardkategorin. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Ställer in tröskelvärdet (transparentintervall) för en angiven kategori. |
| [clearThreshold()](#clearThreshold--) | Rensar tröskelvärdet för standardkategorin. |
| [clearThreshold(int type)](#clearThreshold-int-) | Rensar tröskelvärdet för en angiven kategori. |
| [setGamma(float gamma)](#setGamma-float-) | Ställer in gamma‑värdet för standardkategorin. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Ställer in gamma‑värdet för en angiven kategori. |
| [clearGamma()](#clearGamma--) | Inaktiverar gamma‑korrektion för standardkategorin. |
| [clearGamma(int type)](#clearGamma-int-) | Inaktiverar gamma‑korrektion för en angiven kategori. |
| [setNoOp()](#setNoOp--) | Stänger av färgjustering för standardkategorin. |
| [setNoOp(int type)](#setNoOp-int-) | Stänger av färgjustering för en angiven kategori. |
| [clearNoOp()](#clearNoOp--) | Rensar NoOp‑inställningen för standardkategorin. |
| [clearNoOp(int type)](#clearNoOp-int-) | Rensar NoOp‑inställningen för en angiven kategori. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Ställer in färgnyckeln för standardkategorin. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Ställer in färgnyckeln (transparentintervall) för en angiven kategori. |
| [clearColorKey()](#clearColorKey--) | Rensar färgnyckeln (transparentintervall) för standardkategorin. |
| [clearColorKey(int type)](#clearColorKey-int-) | Rensar färgnyckeln (transparentintervall) för en angiven kategori. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Ställer in CMYK‑utgångskanalen (cyan‑magenta‑gul‑svart) för standardkategorin. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för en specificerad kategori. |
| [clearOutputChannel()](#clearOutputChannel--) | Rensar CMYK (cyan-magenta-gul-svart) utgångskanalinställning för standardkategorin. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Rensar (cyan-magenta-gul-svart) utgångskanalinställning för en specificerad kategori. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Ställer in färgprofilfil för utgångskanalen för standardkategorin. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Ställer in färgprofilfil för utgångskanalen för en specificerad kategori. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Rensar färgprofilinställning för utgångskanalen för standardkategorin. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Rensar färgprofilinställning för utgångskanalen för en specificerad kategori. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Ställer in färg‑omkartläggningstabell för standardkategorin. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Ställer in färg‑omkartläggningstabell för en specificerad kategori. |
| [clearRemapTable()](#clearRemapTable--) | Rensar färg‑omkartläggningstabell för standardkategorin. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Rensar färg‑omkartläggningstabell för en specificerad kategori. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Ställer in färg‑omkartläggningstabell för penselkategorin. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Rensar penselns färg‑omkartläggningstabell för detta `com.aspose.imaging.ImageAttributes`-objekt. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Ställer in omslagsläget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formgränser. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initierar en ny instans av klassen `com.aspose.imaging.ImageAttributes`.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Ställer in färgjusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |
| flaggor | int | Ett element av `Aspose.Imaging.ColorMatrixFlag` som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |
| läge | int | Ett element av `Aspose.Imaging.ColorMatrixFlag` som specificerar typen av bild och färg som kommer att påverkas av färgjusteringsmatrisen. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar den kategori för vilken färgjusteringsmatrisen är inställd. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Rensar färgjusteringsmatrisen för standardkategorin.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Rensar färgjusteringsmatrisen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar den kategori för vilken färgjusteringsmatrisen rensas. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gråskalajusteringsmatrisen. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gråskalajusteringsmatrisen. |
| flaggor | int | Ett element av `Aspose.Imaging.ColorMatrixFlag` som specificerar typen av bild och färg som kommer att påverkas av färg‑ och gråskalajusteringsmatriserna. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Färgjusteringsmatrisen. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Gråskalajusteringsmatrisen. |
| läge | int | Ett element av `Aspose.Imaging.ColorMatrixFlag` som specificerar typen av bild och färg som kommer att påverkas av färg‑ och gråskalajusteringsmatriserna. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar den kategori för vilken färg‑ och gråskalajusteringsmatriserna är inställda. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Ställer in tröskelvärdet (transparentintervall) för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Ett reellt tal som specificerar tröskelvärdet. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Ställer in tröskelvärdet (transparentintervall) för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Ett tröskelvärde från 0,0 till 1,0 som används som en brytpunkt för att sortera färger som kommer att mappas till antingen ett maximalt eller ett minimalt värde. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färgtröskeln är inställd. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Rensar tröskelvärdet för standardkategorin.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Rensar tröskelvärdet för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken tröskeln rensas. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Ställer in gamma‑värdet för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma-korrigeringsvärdet. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Ställer in gamma‑värdet för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma-korrigeringsvärdet. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType`‑enumerationen som specificerar kategorin för vilken gamma‑värdet är inställt. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Inaktiverar gamma‑korrektion för standardkategorin.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Inaktiverar gamma‑korrektion för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken gamma‑korrektion är inaktiverad. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Stänger av färgjustering för standardkategorin.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Stänger av färgjustering för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färgkorrektion är avstängd. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Rensar NoOp‑inställningen för standardkategorin.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Rensar NoOp‑inställningen för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken NoOp‑inställningen rensas. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Ställer in färgnyckeln för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Det höga färgnyckelvärdet. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Ställer in färgnyckeln (transparentintervall) för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Det låga färgnyckelvärdet. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Det höga färgnyckelvärdet. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färgnyckeln är inställd. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Rensar färgnyckeln (transparentintervall) för standardkategorin.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Rensar färgnyckeln (transparentintervall) för en angiven kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färgnyckeln rensas. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Ställer in CMYK‑utgångskanalen (cyan‑magenta‑gul‑svart) för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | int | Ett element av `Aspose.Imaging.ColorChannelFlag` som specificerar utgångskanalen. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Ställer in CMYK (cyan-magenta-gul-svart) utgångskanal för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flaggor | int | Ett element av `Aspose.Imaging.ColorChannelFlag` som specificerar utgångskanalen. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken utgångskanalen är inställd. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Rensar CMYK (cyan-magenta-gul-svart) utgångskanalinställning för standardkategorin.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Rensar (cyan-magenta-gul-svart) utgångskanalinställning för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken inställningen för utgångskanalen rensas. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Ställer in färgprofilfil för utgångskanalen för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan den här parametern vara filnamnet. Annars måste den här parametern vara det fullständigt kvalificerade sökvägsnamnet. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Ställer in färgprofilfil för utgångskanalen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan den här parametern vara filnamnet. Annars måste den här parametern vara det fullständigt kvalificerade sökvägsnamnet. |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färgprofilfil för utgångskanalen är inställd. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Rensar färgprofilinställning för utgångskanalen för standardkategorin.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Rensar färgprofilinställning för utgångskanalen för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken profilen för utgångskanalen rensas. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Ställer in färg‑omkartläggningstabell för standardkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | En array av färgpar av typen `com.aspose.imaging.ColorMap`. Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Ställer in färg‑omkartläggningstabell för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | En array av färgpar av typen `com.aspose.imaging.ColorMap`. Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken färg‑omkartningstabell är inställd. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Rensar färg‑omkartläggningstabell för standardkategorin.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Rensar färg‑omkartläggningstabell för en specificerad kategori.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Ett element av `Aspose.Imaging.ColorAdjustType` som specificerar kategorin för vilken omkartningstabellen rensas. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Ställer in färg‑omkartläggningstabell för penselkategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | En array av `com.aspose.imaging.ColorMap`‑objekt. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Rensar penselns färg‑omkartläggningstabell för detta `com.aspose.imaging.ImageAttributes`-objekt.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Ställer in omslagsläget som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla i den när texturen är mindre än den form den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | int | Ett element av `Aspose.Imaging.WrapMode` som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Ställer in wrap-läget och färgen som används för att bestämma hur en textur mosaikeras över en form, eller vid formens gränser. En textur mosaikeras över en form för att fylla den när texturen är mindre än den form den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | int | Ett element av `Aspose.Imaging.WrapMode` som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| color | [Color](../../com.aspose.imaging/color) | Ett `com.aspose.imaging.ImageAttributes`-objekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är satt till `WrapMode.Clamp` och källrektangeln som skickas till DrawImage är större än själva bilden. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Ställer in wrap-läget och färgen som används för att bestämma hur en textur mosaikeras över en form, eller vid formens gränser. En textur mosaikeras över en form för att fylla den när texturen är mindre än den form den fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | int | Ett element av `Aspose.Imaging.WrapMode` som specificerar hur upprepade kopior av en bild används för att mosaikera ett område. |
| color | [Color](../../com.aspose.imaging/color) | Ett färgobjekt som specificerar färgen på pixlar utanför en renderad bild. Denna färg är synlig om lägesparametern är satt till `WrapMode.Clamp` och källrektangeln som skickas till DrawImage är större än själva bilden. |
| kläm | boolean | Den här parametern har ingen effekt. Sätt den till false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
