---
title: "EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die ModifyWorldTransformMode‑Aufzählung definiert Modi zur Verwendung spezifizierter Transformationsdaten, um die Welt‑zu‑Seiten‑Transformation, die derzeit im Wiedergabegeräte‑Kontext definiert ist, zu ändern."
type: docs
weight: 33
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

Die ModifyWorldTransformMode‑Aufzählung definiert Modi zur Verwendung spezifizierter Transformationsdaten, um die Welt‑zu‑Seiten‑Transformation, die derzeit im Wiedergabegeräte‑Kontext definiert ist, zu ändern.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Setzen Sie die aktuelle Transformation zurück, indem Sie die Einheitsmatrix verwenden. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Multiplizieren Sie die aktuelle Transformation. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Multiplizieren Sie die aktuelle Transformation. |
| [MWT_SET](#MWT-SET) | Führen Sie die Funktion eines EMR_SETWORLDTRANSFORM‑Datensatzes aus (Abschnitt 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Setzen Sie die aktuelle Transformation zurück, indem Sie die Einheitsmatrix verwenden. In diesem Modus werden die angegebenen Transformationsdaten ignoriert.

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Multiplizieren Sie die aktuelle Transformation. In diesem Modus sind die angegebenen Transformationsdaten der linke Multiplikand, und die Transformation, die derzeit im Wiedergabegeräte‑Kontext definiert ist, ist der rechte Multiplikand.

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Multiplizieren Sie die aktuelle Transformation. In diesem Modus sind die angegebenen Transformationsdaten der rechte Multiplikand, und die Transformation, die derzeit im Wiedergabegeräte‑Kontext definiert ist, ist der linke Multiplikand.

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Führen Sie die Funktion eines EMR_SETWORLDTRANSFORM‑Datensatzes aus (Abschnitt 2.3.12.2).

