---
title: "ImageAttributes"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ein com.aspose.imaging.ImageAttributes-Objekt enthält Informationen darüber, wie Bitmap- und Metafile-Farben beim Rendern manipuliert werden."
type: docs
weight: 57
url: /de/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Ein `com.aspose.imaging.ImageAttributes`‑Objekt enthält Informationen darüber, wie Bitmap‑ und Metadatei‑Farben während des Renderns manipuliert werden. Ein `com.aspose.imaging.ImageAttributes`‑Objekt verwaltet mehrere Farb‑Anpassungseinstellungen, einschließlich Farb‑Anpassungsmatrizen, Graustufen‑Anpassungsmatrizen, Gamma‑Korrekturwerte, Farb‑Zuordnungstabellen und Farb‑Schwellenwerte. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein `com.aspose.imaging.ImageAttributes`‑Objekt und übergeben den Pfad dieses `com.aspose.imaging.ImageAttributes`‑Objekts (zusammen mit dem Pfad eines [Image](../../com.aspose.imaging/image)) an die drawImage‑Methode.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Initialisiert eine neue Instanz der `com.aspose.imaging.ImageAttributes`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Setzt die Farb‑Anpassungsmatrix für die Standardkategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Setzt die Farb‑Anpassungsmatrix für die Standardkategorie. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Setzt die Farb‑Anpassungsmatrix für eine angegebene Kategorie. |
| [clearColorMatrix()](#clearColorMatrix--) | Löscht die Farb‑Anpassungsmatrix für die Standardkategorie. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Löscht die Farb‑Anpassungsmatrix für eine angegebene Kategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für die Standardkategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für die Standardkategorie. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für eine angegebene Kategorie. |
| [setThreshold(float threshold)](#setThreshold-float-) | Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie. |
| [clearThreshold()](#clearThreshold--) | Löscht den Schwellenwert für die Standardkategorie. |
| [clearThreshold(int type)](#clearThreshold-int-) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [setGamma(float gamma)](#setGamma-float-) | Setzt den Gamma‑Wert für die Standardkategorie. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Setzt den Gamma‑Wert für eine angegebene Kategorie. |
| [clearGamma()](#clearGamma--) | Deaktiviert die Gamma‑Korrektur für die Standardkategorie. |
| [clearGamma(int type)](#clearGamma-int-) | Deaktiviert die Gamma‑Korrektur für eine angegebene Kategorie. |
| [setNoOp()](#setNoOp--) | Schaltet die Farb‑Anpassung für die Standardkategorie aus. |
| [setNoOp(int type)](#setNoOp-int-) | Schaltet die Farb‑Anpassung für eine angegebene Kategorie aus. |
| [clearNoOp()](#clearNoOp--) | Löscht die NoOp‑Einstellung für die Standardkategorie. |
| [clearNoOp(int type)](#clearNoOp-int-) | Löscht die NoOp‑Einstellung für eine angegebene Kategorie. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Setzt den Farb‑Schlüssel für die Standardkategorie. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Setzt den Farb‑Schlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [clearColorKey()](#clearColorKey--) | Löscht den Farb‑Schlüssel (Transparenzbereich) für die Standardkategorie. |
| [clearColorKey(int type)](#clearColorKey-int-) | Löscht den Farb‑Schlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für die Standardkategorie. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Legt den CMYK (cyan-magenta-yellow-black) Ausgabekanal für eine bestimmte Kategorie fest. |
| [clearOutputChannel()](#clearOutputChannel--) | Löscht die CMYK (cyan-magenta-yellow-black) Ausgabekanal-Einstellung für die Standardkategorie. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Löscht die (cyan-magenta-yellow-black) Ausgabekanal-Einstellung für eine bestimmte Kategorie. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Legt die Farbprofil-Datei des Ausgabekanals für die Standardkategorie fest. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Legt die Farbprofil-Datei des Ausgabekanals für eine bestimmte Kategorie fest. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Löscht die Farbprofil-Einstellung des Ausgabekanals für die Standardkategorie. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Löscht die Farbprofil-Einstellung des Ausgabekanals für eine bestimmte Kategorie. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Legt die Farb-Remap-Tabelle für die Standardkategorie fest. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Legt die Farb-Remap-Tabelle für eine bestimmte Kategorie fest. |
| [clearRemapTable()](#clearRemapTable--) | Löscht die Farb-Remap-Tabelle für die Standardkategorie. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Löscht die Farb-Remap-Tabelle für eine bestimmte Kategorie. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Legt die Farb-Remap-Tabelle für die Pinselkategorie fest. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Löscht die Pinsel-Farb-Remap-Tabelle dieses `com.aspose.imaging.ImageAttributes`-Objekts. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Legt den Wrap-Modus fest, der verwendet wird, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Initialisiert eine neue Instanz der `com.aspose.imaging.ImageAttributes`‑Klasse.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Setzt die Farb‑Anpassungsmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Setzt die Farb‑Anpassungsmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |
| Kennzeichen | int | Ein Element von `Aspose.Imaging.ColorMatrixFlag`, das den Bild- und Farbtyp angibt, der von der Farbkorrekturmatrix betroffen ist. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Setzt die Farb‑Anpassungsmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |
| Modus | int | Ein Element von `Aspose.Imaging.ColorMatrixFlag`, das den Bild- und Farbtyp angibt, der von der Farbkorrekturmatrix betroffen ist. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farbkorrekturmatrix festgelegt wird. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Löscht die Farb‑Anpassungsmatrix für die Standardkategorie.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Löscht die Farb‑Anpassungsmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farbkorrekturmatrix gelöscht wird. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Graustufen-Korrekturmatrix. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Graustufen-Korrekturmatrix. |
| Kennzeichen | int | Ein Element von `Aspose.Imaging.ColorMatrixFlag`, das den Bild- und Farbtyp angibt, der von den Farbkorrektur- und Graustufen-Korrekturmatrizen betroffen ist. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Setzt die Farb‑Anpassungsmatrix und die Graustufen‑Anpassungsmatrix für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Farbkorrekturmatrix. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | Die Graustufen-Korrekturmatrix. |
| Modus | int | Ein Element von `Aspose.Imaging.ColorMatrixFlag`, das den Bild- und Farbtyp angibt, der von den Farbkorrektur- und Graustufen-Korrekturmatrizen betroffen ist. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farbkorrektur- und Graustufen-Korrekturmatrizen festgelegt werden. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Eine reelle Zahl, die den Schwellenwert angibt. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Ein Schwellenwert von 0.0 bis 1.0, der als Trennpunkt verwendet wird, um Farben zu sortieren, die entweder einem Maximal- oder einem Minimalwert zugeordnet werden. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Farbschwellenwert festgelegt ist. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Löscht den Schwellenwert für die Standardkategorie.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Löscht den Schwellenwert für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Schwellenwert gelöscht wird. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Setzt den Gamma‑Wert für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gamma-Korrekturwert. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Setzt den Gamma‑Wert für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Der Gamma-Korrekturwert. |
| Typ | int | Ein Element der Aufzählung `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Gammawert festgelegt ist. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Deaktiviert die Gamma‑Korrektur für die Standardkategorie.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Deaktiviert die Gamma‑Korrektur für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Gamma-Korrektur deaktiviert ist. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Schaltet die Farb‑Anpassung für die Standardkategorie aus.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Schaltet die Farb‑Anpassung für eine angegebene Kategorie aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farbkorrigierung ausgeschaltet ist. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Löscht die NoOp‑Einstellung für die Standardkategorie.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Löscht die NoOp‑Einstellung für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die NoOp-Einstellung gelöscht wird. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Setzt den Farb‑Schlüssel für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Der hohe Farbschlüsselwert. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Setzt den Farb‑Schlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Der niedrige Farbschlüsselwert. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Der hohe Farbschlüsselwert. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Farbschlüssel festgelegt ist. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Löscht den Farb‑Schlüssel (Transparenzbereich) für die Standardkategorie.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Löscht den Farb‑Schlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Farbschlüssel gelöscht wird. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Setzt den CMYK‑Ausgabekanal (cyan‑magenta‑gelb‑schwarz) für die Standardkategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kennzeichen | int | Ein Element von `Aspose.Imaging.ColorChannelFlag`, das den Ausgabekanal angibt. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Legt den CMYK (cyan-magenta-yellow-black) Ausgabekanal für eine bestimmte Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kennzeichen | int | Ein Element von `Aspose.Imaging.ColorChannelFlag`, das den Ausgabekanal angibt. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die der Ausgabekanal festgelegt ist. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Löscht die CMYK (cyan-magenta-yellow-black) Ausgabekanal-Einstellung für die Standardkategorie.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Löscht die (cyan-magenta-yellow-black) Ausgabekanal-Einstellung für eine bestimmte Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Einstellung des Ausgabekanals gelöscht wird. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Legt die Farbprofil-Datei des Ausgabekanals für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im %SystemRoot%\\System32\\Spool\\Drivers\\Color-Verzeichnis liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollständig qualifizierten Pfadnamen enthalten. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Legt die Farbprofil-Datei des Ausgabekanals für eine bestimmte Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im %SystemRoot%\\System32\\Spool\\Drivers\\Color-Verzeichnis liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollständig qualifizierten Pfadnamen enthalten. |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farbprofildatei des Ausgabekanals festgelegt ist. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Löscht die Farbprofil-Einstellung des Ausgabekanals für die Standardkategorie.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Löscht die Farbprofil-Einstellung des Ausgabekanals für eine bestimmte Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Einstellung des Ausgabekanalprofils gelöscht wird. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Legt die Farb-Remap-Tabelle für die Standardkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Ein Array von Farbpaaren vom Typ `com.aspose.imaging.ColorMap`. Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Legt die Farb-Remap-Tabelle für eine bestimmte Kategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Ein Array von Farbpaaren vom Typ `com.aspose.imaging.ColorMap`. Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Farb-Remap-Tabelle festgelegt ist. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Löscht die Farb-Remap-Tabelle für die Standardkategorie.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Löscht die Farb-Remap-Tabelle für eine bestimmte Kategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Ein Element von `Aspose.Imaging.ColorAdjustType`, das die Kategorie angibt, für die die Remap-Tabelle gelöscht wird. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Legt die Farb-Remap-Tabelle für die Pinselkategorie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Ein Array von `com.aspose.imaging.ColorMap`-Objekten. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Löscht die Pinsel-Farb-Remap-Tabelle dieses `com.aspose.imaging.ImageAttributes`-Objekts.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von `Aspose.Imaging.WrapMode`, das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von `Aspose.Imaging.WrapMode`, das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.imaging/color) | Ein `com.aspose.imaging.ImageAttributes`‑Objekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modus‑Parameter auf `WrapMode.Clamp` gesetzt ist und das an `DrawImage` übergebene Quellrechteck größer ist als das Bild selbst. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus | int | Ein Element von `Aspose.Imaging.WrapMode`, das festlegt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](../../com.aspose.imaging/color) | Ein Farbobjekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modus‑Parameter auf `WrapMode.Clamp` gesetzt ist und das an `DrawImage` übergebene Quellrechteck größer ist als das Bild selbst. |
| clamp | boolean | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
