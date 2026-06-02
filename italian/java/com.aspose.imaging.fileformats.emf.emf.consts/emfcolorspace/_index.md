---
title: "EmfColorSpace"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione ColorSpace è usata per specificare quando attivare e disattivare la verifica del colore e quando eliminare le trasformazioni."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

L'enumerazione ColorSpace è usata per specificare quando attivare o disattivare la prova colore e quando eliminare le trasformazioni.
## Campi

| Campo | Descrizione |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Mappa i colori nella gamma di colore del dispositivo di destinazione. |
| [CS_DISABLE](#CS-DISABLE) | Disabilita la verifica del colore. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Se la gestione del colore è abilitata per il profilo di destinazione, la disabilita ed elimina la trasformazione concatenata. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Mappa i colori nella gamma di colore del dispositivo di destinazione. Questo abilita la verifica del colore. Tutti i successivi comandi di disegno al contesto del dispositivo di riproduzione renderanno i colori come apparirebbero sul dispositivo di destinazione.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Disabilita la verifica del colore.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Se la gestione del colore è abilitata per il profilo di destinazione, la disabilita ed elimina la trasformazione concatenata.

