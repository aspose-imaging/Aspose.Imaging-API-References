---
title: "EmfColorSpace"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die ColorSpace-Aufzählung wird verwendet, um anzugeben, wann die Farbproofing ein- und ausgeschaltet wird und wann Transformationen gelöscht werden."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

Die Aufzählung ColorSpace wird verwendet, um anzugeben, wann die Farbprüfung ein- und ausgeschaltet wird und wann Transformationen gelöscht werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Ordnet Farben dem Farbraum des Zielgeräts zu. |
| [CS_DISABLE](#CS-DISABLE) | Deaktiviert das Farbproofing. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Wenn die Farbverwaltung für das Zielprofil aktiviert ist, wird sie deaktiviert und die verkettete Transformation gelöscht. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Ordnet Farben dem Farbraum des Zielgeräts zu. Dies aktiviert das Farbproofing. Alle nachfolgenden Zeichenbefehle im Wiedergabegeräte‑Kontext rendern die Farben so, wie sie auf dem Zielgerät erscheinen würden.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Deaktiviert das Farbproofing.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Wenn die Farbverwaltung für das Zielprofil aktiviert ist, wird sie deaktiviert und die verkettete Transformation gelöscht.

