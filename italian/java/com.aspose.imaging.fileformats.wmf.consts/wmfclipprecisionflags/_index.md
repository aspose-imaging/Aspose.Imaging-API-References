---
title: "WmfClipPrecisionFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I Flag ClipPrecision specificano la precisione di ritaglio che definisce come ritagliare i caratteri che sono parzialmente al di fuori di una regione di ritaglio."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

I Flag ClipPrecision specificano la precisione di ritaglio, che definisce come ritagliare i caratteri che sono parzialmente al di fuori di una regione di ritaglio. Questi flag possono essere combinati per specificare più opzioni.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Specifica che il ritaglio predefinito DEVE essere utilizzato. |
| [Character](#Character) | Questo valore NON DEVE essere utilizzato. |
| [Stroke](#Stroke) | Questo valore PUÒ essere restituito durante l'enumerazione di font rasterizzati, TrueType e vettoriali. |
| [LhAngles](#LhAngles) | Questo valore è usato per controllare la rotazione dei font, come segue: - Se impostato, la rotazione di tutti i font DEVE essere determinata dall'orientamento del sistema di coordinate; cioè, se l'orientamento è sinistro o destro. |
| [TtAlways](#TtAlways) | Questo valore NON DEVE [34] essere utilizzato. |
| [DfaDisable](#DfaDisable) | Questo valore specifica che l'associazione dei font DEVE [35] essere disattivata. |
| [Embedded](#Embedded) | Questo valore specifica che l'incorporamento dei font DEVE essere utilizzato per renderizzare il contenuto del documento; i font incorporati sono di sola lettura. |
### Default {#Default}
```
public static final byte Default
```


Specifica che il ritaglio predefinito DEVE essere utilizzato.

### Character {#Character}
```
public static final byte Character
```


Questo valore NON DEVE essere utilizzato.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Questo valore PUÒ essere restituito durante l'enumerazione di font rasterizzati, TrueType e vettoriali. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 e Windows XP: questo valore è sempre restituito durante l'enumerazione dei font.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Questo valore è usato per controllare la rotazione dei font, come segue: - Se impostato, la rotazione di tutti i font DEVE essere determinata dall'orientamento del sistema di coordinate; cioè, se l'orientamento è sinistro o destro. - Se non impostato, i font del dispositivo DEVIANO ruotare in senso antiorario, ma la rotazione degli altri font DEVE essere determinata dall'orientamento del sistema di coordinate.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Questo valore NON DEVE [34] essere utilizzato. [34] Questo valore è ignorato nelle seguenti versioni di Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Questo valore specifica che l'associazione dei font DEVE [35] essere disattivata. [35] Questo valore non è supportato in Windows 95, Windows 98 e Windows Millennium Edition. L'associazione dei font è disattivata in Windows 2000, Windows XP e Windows Server 2003. Questo valore è ignorato in queste versioni di Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Questo valore specifica che l'incorporamento dei font DEVE essere utilizzato per renderizzare il contenuto del documento; i font incorporati sono di sola lettura.

