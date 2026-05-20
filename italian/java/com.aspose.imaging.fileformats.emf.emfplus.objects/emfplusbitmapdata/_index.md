---
title: "EmfPlusBitmapData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusBitmapData specifica un'immagine bitmap con dati pixel."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusBitmapData extends EmfPlusBaseBitmapData
```

L'oggetto EmfPlusBitmapData specifica un'immagine bitmap con dati pixel.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColors()](#getColors--) | Ottiene o imposta i colori della tavolozza Colors (variabile): un oggetto opzionale `EmfPlusPalette` (sezione 2.2.2.28), che specifica la tavolozza di colori utilizzata nei dati dei pixel. |
| [setColors(EmfPlusPalette value)](#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Ottiene o imposta i colori della tavolozza Colors (variabile): un oggetto opzionale `EmfPlusPalette` (sezione 2.2.2.28), che specifica la tavolozza di colori utilizzata nei dati dei pixel. |
| [getPixelData()](#getPixelData--) | Ottiene o imposta i dati dei pixel PixelData (variabile): un array di byte che specificano i dati dei pixel. |
| [setPixelData(byte[] value)](#setPixelData-byte---) | Ottiene o imposta i dati dei pixel PixelData (variabile): un array di byte che specificano i dati dei pixel. |
### EmfPlusBitmapData() {#EmfPlusBitmapData--}
```
public EmfPlusBitmapData()
```


### getColors() {#getColors--}
```
public EmfPlusPalette getColors()
```


Ottiene o imposta i colori della tavolozza Colors (variabile): un oggetto opzionale `EmfPlusPalette` (sezione 2.2.28), che specifica la tavolozza di colori utilizzata nei dati dei pixel. Questo campo DEVE essere presente se il flag I è impostato nel campo PixelFormat dell'oggetto `EmfPlusBitmap`.

Valore: I colori.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setColors(EmfPlusPalette value) {#setColors-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setColors(EmfPlusPalette value)
```


Ottiene o imposta i colori della tavolozza Colors (variabile): un oggetto opzionale `EmfPlusPalette` (sezione 2.2.28), che specifica la tavolozza di colori utilizzata nei dati dei pixel. Questo campo DEVE essere presente se il flag I è impostato nel campo PixelFormat dell'oggetto `EmfPlusBitmap`.

Valore: I colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

### getPixelData() {#getPixelData--}
```
public byte[] getPixelData()
```


Ottiene o imposta i dati dei pixel PixelData (variabile): un array di byte che specificano i dati dei pixel. La dimensione e il formato di questi dati possono essere calcolati dai campi dell'oggetto EmfPlusBitmap, inclusa la modalità pixel dall'enumerazione `Consts.EmfPlusPixelFormat` (sezione 2.1.1.25).

Valore: I dati dei pixel.

**Returns:**
byte[]
### setPixelData(byte[] value) {#setPixelData-byte---}
```
public void setPixelData(byte[] value)
```


Ottiene o imposta i dati dei pixel PixelData (variabile): un array di byte che specificano i dati dei pixel. La dimensione e il formato di questi dati possono essere calcolati dai campi dell'oggetto EmfPlusBitmap, inclusa la modalità pixel dall'enumerazione `Consts.EmfPlusPixelFormat` (sezione 2.1.1.25).

Valore: I dati dei pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

