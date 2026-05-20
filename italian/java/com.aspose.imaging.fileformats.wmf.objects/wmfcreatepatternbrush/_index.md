---
title: "WmfCreatePatternBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_CREATEPATTERNBRUSH crea un oggetto pennello con un motivo specificato da una bitmap."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

Il record META\_CREATEPATTERNBRUSH crea un oggetto pennello con un motivo specificato da un bitmap.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs il record. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitmap()](#getBitmap--) | Ottiene o imposta la bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Ottiene o imposta la bitmap. |
| [getReserved()](#getReserved--) | Ottiene o imposta il riservato. |
| [setReserved(byte[] value)](#setReserved-byte---) | Ottiene o imposta il riservato. |
| [getPattern()](#getPattern--) | Ottiene o imposta il motivo. |
| [setPattern(byte[] value)](#setPattern-byte---) | Ottiene o imposta il motivo. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs il record.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Ottiene o imposta la bitmap.

Valore: la bitmap che specifica il motivo per il pennello.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Ottiene o imposta la bitmap.

Valore: la bitmap che specifica il motivo per il pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Ottiene o imposta il riservato.

Valore: riservato. Questo campo DEVE essere ignorato.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Ottiene o imposta il riservato.

Valore: riservato. Questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Ottiene o imposta il motivo.

Valore: un array di byte a lunghezza variabile che definisce i dati dei pixel della bitmap che compongono il motivo del pennello. La lunghezza di questo campo, in byte, può essere calcolata dai parametri della bitmap come segue.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Ottiene o imposta il motivo.

Valore: un array di byte a lunghezza variabile che definisce i dati dei pixel della bitmap che compongono il motivo del pennello. La lunghezza di questo campo, in byte, può essere calcolata dai parametri della bitmap come segue.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

