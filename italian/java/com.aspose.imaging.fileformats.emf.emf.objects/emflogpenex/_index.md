---
title: "EmfLogPenEx"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogPenEx specifica la larghezza dello stile e il colore di una penna logica estesa."
type: docs
weight: 28
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

L'oggetto LogPenEx specifica lo stile, la larghezza e il colore di una penna logica estesa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Ottiene lo stile della penna |
| [setPenStyle(int value)](#setPenStyle-int-) | Ottiene lo stile della penna |
| [getWidth()](#getWidth--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la larghezza della linea tracciata dalla penna. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la larghezza della linea tracciata dalla penna. |
| [getBrushStyle()](#getBrushStyle--) | Ottiene o imposta un intero senza segno a 32 bit che specifica uno stile di pennello per la penna dall'enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica uno stile di pennello per la penna dall'enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Ottiene o imposta il motivo di tratteggio del pennello. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Ottiene o imposta il motivo di tratteggio del pennello. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Ottiene il numero di elementi nell'array specificato nel campo StyleEntry. |
| [getStyleEntry()](#getStyleEntry--) | Ottiene o imposta un array opzionale di interi senza segno a 32 bit che definisce le lunghezze di trattini e spazi nella linea tracciata da questa penna, quando il valore di PenStyle è PS\_USERSTYLE stile di linea per la penna. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Ottiene o imposta un array opzionale di interi senza segno a 32 bit che definisce le lunghezze di trattini e spazi nella linea tracciata da questa penna, quando il valore di PenStyle è PS\_USERSTYLE stile di linea per la penna. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Ottiene o imposta il pattern dib del pennello. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta il pattern dib del pennello. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Ottiene lo stile della penna

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Ottiene lo stile della penna

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la larghezza della linea tracciata dalla penna. Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, questo valore è la larghezza in unità logiche; altrimenti, la larghezza è specificata in unità dispositivo. Se il tipo di penna nel campo PenStyle è PS\_COSMETIC, questo valore DEVE essere 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la larghezza della linea tracciata dalla penna. Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, questo valore è la larghezza in unità logiche; altrimenti, la larghezza è specificata in unità dispositivo. Se il tipo di penna nel campo PenStyle è PS\_COSMETIC, questo valore DEVE essere 0x00000001.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica uno stile di pennello per la penna dall'enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, questo valore DEVE essere BS\_SOLID o BS\_HATCHED. Il valore di questo campo può essere BS\_NULL, ma solo se lo stile di linea specificato in PenStyle è PS\_NULL. Lo stile BS\_NULL DOVREBBE essere usato per specificare un pennello che non ha effetto.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica uno stile di pennello per la penna dall'enumerazione WMF BrushStyle ([MS-WMF] sezione 2.1.1.4). Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, questo valore DEVE essere BS\_SOLID o BS\_HATCHED. Il valore di questo campo può essere BS\_NULL, ma solo se lo stile di linea specificato in PenStyle è PS\_NULL. Lo stile BS\_NULL DOVREBBE essere usato per specificare un pennello che non ha effetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8). L'interpretazione di questo campo dipende dal valore BrushStyle, come mostrato nella tabella più avanti in questa sezione.

Valore: Il colore ARGB a 32 bit

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8). L'interpretazione di questo campo dipende dal valore BrushStyle, come mostrato nella tabella più avanti in questa sezione.

Valore: Il colore ARGB a 32 bit

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Ottiene o imposta il motivo di tratteggio del pennello. La definizione di questo campo dipende dal valore BrushStyle, come mostrato nella tabella più avanti in questa sezione.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Ottiene o imposta il motivo di tratteggio del pennello. La definizione di questo campo dipende dal valore BrushStyle, come mostrato nella tabella più avanti in questa sezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Ottiene il numero di elementi nell'array specificato nel campo StyleEntry. Questo valore DOVREBBE essere zero se PenStyle non specifica PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Ottiene o imposta un array opzionale di interi senza segno a 32 bit che definisce le lunghezze di trattini e spazi nella linea tracciata da questa penna, quando il valore di PenStyle è PS\_USERSTYLE stile di linea per la penna. L'array contiene un numero di voci specificato da NumStyleEntries, ma viene usato come se si ripetesse indefinitamente. La prima voce dell'array specifica la lunghezza del primo trattino. La seconda voce specifica la lunghezza del primo spazio. Successivamente, le lunghezze di trattini e spazi si alternano. Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, le lunghezze sono specificate in unità logiche; altrimenti, le lunghezze sono specificate in unità dispositivo.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Ottiene o imposta un array opzionale di interi senza segno a 32 bit che definisce le lunghezze di trattini e spazi nella linea tracciata da questa penna, quando il valore di PenStyle è PS\_USERSTYLE stile di linea per la penna. L'array contiene un numero di voci specificato da NumStyleEntries, ma viene usato come se si ripetesse indefinitamente. La prima voce dell'array specifica la lunghezza del primo trattino. La seconda voce specifica la lunghezza del primo spazio. Successivamente, le lunghezze di trattini e spazi si alternano. Se il tipo di penna nel campo PenStyle è PS\_GEOMETRIC, le lunghezze sono specificate in unità logiche; altrimenti, le lunghezze sono specificate in unità dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Ottiene o imposta il pattern dib del pennello.

Valore: Il modello dib del pennello.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta il pattern dib del pennello.

Valore: Il modello dib del pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

