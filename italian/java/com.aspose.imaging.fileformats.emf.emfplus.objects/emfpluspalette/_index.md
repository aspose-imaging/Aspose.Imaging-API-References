---
title: "EmfPlusPalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPalette specifica i colori che compongono una tavolozza."
type: docs
weight: 57
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusPalette specifica i colori che compongono una tavolozza.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Ottiene o imposta i flag di stile della tavolozza. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Ottiene o imposta i flag di stile della tavolozza. |
| [getArgb32Entries()](#getArgb32Entries--) | Ottiene o imposta le voci della tavolozza. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Ottiene o imposta le voci della tavolozza. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Ottiene o imposta i flag di stile della tavolozza.

Valore: PaletteStyleFlags (4 byte): Un intero senza segno a 32 bit che specifica gli attributi dei dati nella tavolozza. Questo valore DEVE essere composto dai flag `EmfPlusPaletteStyleFlags`.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Ottiene o imposta i flag di stile della tavolozza.

Valore: PaletteStyleFlags (4 byte): Un intero senza segno a 32 bit che specifica gli attributi dei dati nella tavolozza. Questo valore DEVE essere composto dai flag `EmfPlusPaletteStyleFlags`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Ottiene o imposta le voci della tavolozza.

Valore: PaletteEntries (variabile): Un array di PaletteCount oggetti ARGB a 32 bit che specificano i dati nella tavolozza.

**Returns:**
int[] - La copia delle voci della tavolozza.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Ottiene o imposta le voci della tavolozza.

Valore: PaletteEntries (variabile): Un array di PaletteCount oggetti ARGB a 32 bit che specificano i dati nella tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

