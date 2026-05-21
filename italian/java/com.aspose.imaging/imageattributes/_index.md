---
title: "ImageAttributes"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Un oggetto com.aspose.imaging.ImageAttributes contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering."
type: docs
weight: 57
url: /it/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Un oggetto `com.aspose.imaging.ImageAttributes` contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering. Un oggetto `com.aspose.imaging.ImageAttributes` mantiene diverse impostazioni di regolazione del colore, incluse matrici di regolazione del colore, matrici di regolazione in scala di grigi, valori di correzione gamma, tabelle di mappatura dei colori e valori di soglia del colore. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializza un oggetto `com.aspose.imaging.ImageAttributes` e passa il percorso di quell'oggetto `com.aspose.imaging.ImageAttributes` (insieme al percorso di un [Image](../../com.aspose.imaging/image)) al metodo drawImage.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Inizializza una nuova istanza della classe `com.aspose.imaging.ImageAttributes`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Imposta la matrice di regolazione del colore per una categoria specificata. |
| [clearColorMatrix()](#clearColorMatrix--) | Cancella la matrice di regolazione del colore per la categoria predefinita. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Cancella la matrice di regolazione del colore per una categoria specificata. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per la categoria predefinita. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per la categoria predefinita. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per una categoria specificata. |
| [setThreshold(float threshold)](#setThreshold-float-) | Imposta la soglia (intervallo di trasparenza) per la categoria predefinita. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Imposta la soglia (intervallo di trasparenza) per una categoria specificata. |
| [clearThreshold()](#clearThreshold--) | Cancella il valore di soglia per la categoria predefinita. |
| [clearThreshold(int type)](#clearThreshold-int-) | Cancella il valore di soglia per una categoria specificata. |
| [setGamma(float gamma)](#setGamma-float-) | Imposta il valore gamma per la categoria predefinita. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Imposta il valore gamma per una categoria specificata. |
| [clearGamma()](#clearGamma--) | Disabilita la correzione gamma per la categoria predefinita. |
| [clearGamma(int type)](#clearGamma-int-) | Disabilita la correzione gamma per una categoria specificata. |
| [setNoOp()](#setNoOp--) | Disattiva la regolazione del colore per la categoria predefinita. |
| [setNoOp(int type)](#setNoOp-int-) | Disattiva la regolazione del colore per una categoria specificata. |
| [clearNoOp()](#clearNoOp--) | Cancella l'impostazione NoOp per la categoria predefinita. |
| [clearNoOp(int type)](#clearNoOp-int-) | Cancella l'impostazione NoOp per una categoria specificata. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Imposta la chiave di colore per la categoria predefinita. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Imposta la chiave di colore (intervallo di trasparenza) per una categoria specificata. |
| [clearColorKey()](#clearColorKey--) | Cancella la chiave di colore (intervallo di trasparenza) per la categoria predefinita. |
| [clearColorKey(int type)](#clearColorKey-int-) | Cancella la chiave di colore (intervallo di trasparenza) per una categoria specificata. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata. |
| [clearOutputChannel()](#clearOutputChannel--) | Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Cancella l'impostazione del canale di output (ciano-magenta-giallo-nero) per una categoria specificata. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Imposta il file del profilo colore del canale di output per la categoria predefinita. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Imposta il file del profilo colore del canale di output per una categoria specificata. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Cancella l'impostazione del profilo colore del canale di output per una categoria specificata. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Imposta la tabella di rimappatura colore per la categoria predefinita. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Imposta la tabella di rimappatura colore per una categoria specificata. |
| [clearRemapTable()](#clearRemapTable--) | Cancella la tabella di rimappatura colore per la categoria predefinita. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Cancella la tabella di rimappatura colore per una categoria specificata. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Imposta la tabella di rimappatura colore per la categoria pennello. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Cancella la tabella di rimappatura colore del pennello di questo oggetto `com.aspose.imaging.ImageAttributes`. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Imposta la modalità di avvolgimento usata per decidere come ripetere una texture su una forma, o ai bordi della forma. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Imposta la modalità di avvolgimento e il colore usati per decidere come ripetere una texture su una forma, o ai bordi della forma. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Imposta la modalità di avvolgimento e il colore usati per decidere come ripetere una texture su una forma, o ai bordi della forma. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Inizializza una nuova istanza della classe `com.aspose.imaging.ImageAttributes`.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Imposta la matrice di regolazione del colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Imposta la matrice di regolazione del colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |
| flag | int | Un elemento di `Aspose.Imaging.ColorMatrixFlag` che specifica il tipo di immagine e colore che sarà influenzato dalla matrice di correzione colore. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Imposta la matrice di regolazione del colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |
| modalità | int | Un elemento di `Aspose.Imaging.ColorMatrixFlag` che specifica il tipo di immagine e colore che sarà influenzato dalla matrice di correzione colore. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la matrice di correzione colore è impostata. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Cancella la matrice di regolazione del colore per la categoria predefinita.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Cancella la matrice di regolazione del colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la matrice di correzione colore è cancellata. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione in scala di grigi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione in scala di grigi. |
| flag | int | Un elemento di `Aspose.Imaging.ColorMatrixFlag` che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di correzione colore e correzione in scala di grigi. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Imposta la matrice di regolazione del colore e la matrice di regolazione in scala di grigi per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione colore. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matrice di correzione in scala di grigi. |
| modalità | int | Un elemento di `Aspose.Imaging.ColorMatrixFlag` che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di correzione colore e correzione in scala di grigi. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale le matrici di correzione colore e correzione in scala di grigi sono impostate. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Imposta la soglia (intervallo di trasparenza) per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Un numero reale che specifica il valore soglia. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Imposta la soglia (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Un valore soglia da 0.0 a 1.0 che viene usato come punto di interruzione per ordinare i colori che saranno mappati a un valore massimo o minimo. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostata la soglia di colore. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Cancella il valore di soglia per la categoria predefinita.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Cancella il valore di soglia per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la soglia viene cancellata. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Imposta il valore gamma per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Il valore di correzione gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Imposta il valore gamma per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Il valore di correzione gamma. |
| tipo | int | Un elemento dell'enumerazione `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostato il valore gamma. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Disabilita la correzione gamma per la categoria predefinita.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Disabilita la correzione gamma per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la correzione gamma è disabilitata. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Disattiva la regolazione del colore per la categoria predefinita.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Disattiva la regolazione del colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la correzione colore è disattivata. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Cancella l'impostazione NoOp per la categoria predefinita.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Cancella l'impostazione NoOp per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale l'impostazione NoOp viene cancellata. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Imposta la chiave di colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Il valore della chiave colore basso. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Il valore della chiave colore alto. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Imposta la chiave di colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | Il valore della chiave colore basso. |
| colorHigh | [Color](../../com.aspose.imaging/color) | Il valore della chiave colore alto. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostata la chiave colore. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Cancella la chiave di colore (intervallo di trasparenza) per la categoria predefinita.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Cancella la chiave di colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la chiave colore viene cancellata. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag | int | Un elemento di `Aspose.Imaging.ColorChannelFlag` che specifica il canale di output. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag | int | Un elemento di `Aspose.Imaging.ColorChannelFlag` che specifica il canale di output. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostato il canale di output. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Cancella l'impostazione del canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Cancella l'impostazione del canale di output (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale l'impostazione del canale di output viene cancellata. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Imposta il file del profilo colore del canale di output per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\\System32\\Spool\\Drivers\\Color, questo parametro può essere il nome del file. Altrimenti, questo parametro deve essere il percorso completo. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Imposta il file del profilo colore del canale di output per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\\System32\\Spool\\Drivers\\Color, questo parametro può essere il nome del file. Altrimenti, questo parametro deve essere il percorso completo. |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostato il file di profilo colore del canale di output. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Cancella l'impostazione del profilo colore del canale di output per la categoria predefinita.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Cancella l'impostazione del profilo colore del canale di output per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale l'impostazione del profilo del canale di output viene cancellata. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Imposta la tabella di rimappatura colore per la categoria predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Un array di coppie di colore di tipo `com.aspose.imaging.ColorMap`. Ogni coppia di colore contiene un colore esistente (il primo valore) e il colore a cui sarà mappato (il secondo valore). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Imposta la tabella di rimappatura colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Un array di coppie di colore di tipo `com.aspose.imaging.ColorMap`. Ogni coppia di colore contiene un colore esistente (il primo valore) e il colore a cui sarà mappato (il secondo valore). |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale è impostata la tabella di rimappatura colore. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Cancella la tabella di rimappatura colore per la categoria predefinita.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Cancella la tabella di rimappatura colore per una categoria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Un elemento di `Aspose.Imaging.ColorAdjustType` che specifica la categoria per la quale la tabella di rimappatura viene cancellata. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Imposta la tabella di rimappatura colore per la categoria pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Un array di oggetti `com.aspose.imaging.ColorMap`. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Cancella la tabella di rimappatura colore del pennello di questo oggetto `com.aspose.imaging.ImageAttributes`.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Imposta la modalità di avvolgimento usata per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modalità | int | Un elemento di `Aspose.Imaging.WrapMode` che specifica come le copie ripetute di un'immagine vengono usate per riempire un'area a tasselli. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Imposta la modalità di avvolgimento e il colore usati per decidere come riempire a tasselli una texture su una forma, o ai bordi della forma. Una texture viene riempita a tasselli su una forma per riempirla quando la texture è più piccola della forma che sta riempiendo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modalità | int | Un elemento di `Aspose.Imaging.WrapMode` che specifica come le copie ripetute di un'immagine vengono usate per riempire un'area a tasselli. |
| color | [Color](../../com.aspose.imaging/color) | Un oggetto `com.aspose.imaging.ImageAttributes` che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su `WrapMode.Clamp` e il rettangolo di origine passato a DrawImage è più grande dell'immagine stessa. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Imposta la modalità di avvolgimento e il colore usati per decidere come riempire a tasselli una texture su una forma, o ai bordi della forma. Una texture viene riempita a tasselli su una forma per riempirla quando la texture è più piccola della forma che sta riempiendo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modalità | int | Un elemento di `Aspose.Imaging.WrapMode` che specifica come le copie ripetute di un'immagine vengono usate per riempire un'area a tasselli. |
| color | [Color](../../com.aspose.imaging/color) | Un oggetto colore che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su `WrapMode.Clamp` e il rettangolo di origine passato a DrawImage è più grande dell'immagine stessa. |
| clamp | boolean | Questo parametro non ha effetto. Impostalo su false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
