---
title: "EmfGraphicsMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione GraphicsMode è usata per specificare come interpretare i dati di forma, come le coordinate dei rettangoli."
type: docs
weight: 24
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

L'enumerazione GraphicsMode è usata per specificare come interpretare i dati di forma, come le coordinate dei rettangoli.
## Campi

| Campo | Descrizione |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | Il testo TrueType MUST essere scritto da sinistra a destra e con il lato destro in alto, anche se il resto della grafica è ruotato attorno all'asse x o y a causa della corrente world-to-device transformation nel contesto del dispositivo di riproduzione. |
| [GM_ADVANCED](#GM-ADVANCED) | L'output del testo TrueType MUST conformare pienamente alla corrente world-to-device transformation nel contesto del dispositivo di riproduzione. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


Il testo TrueType MUST essere scritto da sinistra a destra e con il lato destro in alto, anche se il resto della grafica è ruotato attorno all'asse x o y a causa della corrente world-to-device transformation nel contesto del dispositivo di riproduzione. Solo l'altezza del testo SHOULD essere scalata. Gli archi MUST essere disegnati usando la direzione corrente dell'arco nel contesto del dispositivo di riproduzione, ma non MUST RISPETTARE la corrente world-to-device transformation, che potrebbe richiedere una rotazione lungo l'asse x o y. La world-to-device transformation SHOULD essere modificata solo cambiando le estensioni e le origini della finestra e del viewport, usando i record EMR\_SETWINDOWEXTEX (sezione 2.3.11.30) e EMR\_SETVIEWPORTEXTEX (sezione 2.3.11.28), e i record EMR\_SETWINDOWORGEX (sezione 2.3.11.31) e EMR\_SETVIEWPORTORGEX (sezione 2.3.11.30), rispettivamente. Cambiare direttamente la trasformazione usando i record EMR\_MODIFYWORLDTRANSFORM (sezione 2.3.12.1) o EMR\_SETWORLDTRANSFORM (sezione 2.3.12.2) MAY NOT essere supportato. In modalità grafica GM\_COMPATIBLE, i bordi inferiori e più a destra MUST essere esclusi quando i rettangoli sono disegnati.

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


L'output del testo TrueType MUST conformare pienamente alla corrente world-to-device transformation nel contesto del dispositivo di riproduzione. Gli archi MUST essere disegnati in direzione antioraria nello spazio world; tuttavia, sia i punti di controllo dell'arco sia gli archi stessi MUST rispettare pienamente la corrente world-to-device transformation nel contesto del dispositivo di riproduzione. La world-to-device transform MAY essere modificata direttamente usando i record EMR\_MODIFYWORLDTRANSFORM o EMR\_SETWORLDTRANSFORM, o indirettamente cambiando le estensioni e le origini della finestra e del viewport, usando i record EMR\_SETWINDOWEXTEX (sezione 2.3.11.30) e EMR\_SETVIEWPORTEXTEX (sezione 2.3.11.28), e i record EMR\_SETWINDOWORGEX (sezione 2.3.11.31) e EMR\_SETVIEWPORTORGEX (sezione 2.3.11.30), rispettivamente. In modalità grafica GM\_ADVANCED, i bordi inferiori e più a destra MUST essere inclusi quando i rettangoli sono disegnati.

