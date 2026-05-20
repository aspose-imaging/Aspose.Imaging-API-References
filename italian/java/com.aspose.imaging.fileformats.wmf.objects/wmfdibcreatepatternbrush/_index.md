---
title: "WmfDibCreatePatternBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_DIBCREATEPATTERNBRUSH crea una sezione Brush Object 2.2.1.1 con un pattern specificato da una DeviceIndependentBitmap DIB Object sezione 2.2.2.9."
type: docs
weight: 29
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

Il record META\_DIBCREATEPATTERNBRUSH crea un oggetto Brush (sezione 2.2.1.1) con un motivo specificato da un oggetto DeviceIndependentBitmap (DIB) (sezione 2.2.2.9).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStyle()](#getStyle--) | Ottiene o imposta lo stile. |
| [setStyle(int value)](#setStyle-int-) | Ottiene o imposta lo stile. |
| [getColorUsage()](#getColorUsage--) | Ottiene o imposta l'uso del colore. |
| [setColorUsage(int value)](#setColorUsage-int-) | Ottiene o imposta l'uso del colore. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta il bitmap di origine. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta il bitmap di origine. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Ottiene o imposta lo stile.

Valore: I valori legali per questo campo sono definiti come segue: se il valore non è BS\_PATTERN, BS\_DIBPATTERNPT DEVE essere assunto. Questi valori sono specificati nell'enumerazione BrushStyle (sezione 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Ottiene o imposta lo stile.

Valore: I valori legali per questo campo sono definiti come segue: se il valore non è BS\_PATTERN, BS\_DIBPATTERNPT DEVE essere assunto. Questi valori sono specificati nell'enumerazione BrushStyle (sezione 2.1.1.4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Ottiene o imposta l'uso del colore.

Valore: Il campo Colors di un oggetto DIB contiene valori RGB espliciti, o indici in una tavolozza.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Ottiene o imposta l'uso del colore.

Valore: Il campo Colors di un oggetto DIB contiene valori RGB espliciti, o indici in una tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta il bitmap di origine.

Valore: Dati dell'oggetto DIB a bit variabile che definiscono il pattern da utilizzare nel brush.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta il bitmap di origine.

Valore: Dati dell'oggetto DIB a bit variabile che definiscono il pattern da utilizzare nel brush.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

