---
title: "EmfPlusPathPointFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ein 32‑Bit‑vorzeichenloser Ganzzahlwert, der angibt, wie die Punkte und zugehörigen Punktetypen, die von diesem Objekt definiert werden, zu interpretieren sind."
type: docs
weight: 38
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

Ein 32‑Bit‑vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind. C (1 Bit): Wenn gesetzt, gibt das PathPoints‑Array absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Wenn nicht gesetzt, gibt das PathPoints‑Array absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. Hinweis: Wenn das P‑Flag (unten) gesetzt ist, kann dieses Flag nicht gesetzt sein und muss ignoriert werden. R (1 Bit): Wenn gesetzt, werden die Punkttypen im PathPointTypes‑Array durch EmfPlusPathPointTypeRle‑Objekte (Abschnitt 2.2.2.32) angegeben, die Laufzeitkodierung (RLE)‑Kompression verwenden, und/oder durch EmfPlusPathPointType‑Objekte (Abschnitt 2.2.2.31). Siehe [MS-WMF] Abschnitt 3.1.6 für weitere Informationen zur RLE‑Kompression. Wenn nicht gesetzt, werden die Punkttypen im PathPointTypes‑Array durch EmfPlusPathPointType‑Objekte angegeben. P (1 Bit): Wenn gesetzt, gibt jedes Element im PathPoints‑Array einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Im Fall des ersten Elements in PathPoints wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, gibt jedes Element im PathPoints‑Array einen absoluten Ort an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [C](#C) | Das c‑Flag |
| [R](#R) | Das r‑Flag |
| [P](#P) | Das p‑Flag |
### C {#C}
```
public static final short C
```


Das c‑Flag

### R {#R}
```
public static final short R
```


Das r‑Flag

### P {#P}
```
public static final short P
```


Das p‑Flag

