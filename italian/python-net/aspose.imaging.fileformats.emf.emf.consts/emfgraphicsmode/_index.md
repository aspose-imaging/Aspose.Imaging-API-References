---
title: "Enumerazione EmfGraphicsMode"
type: docs
weight: 150
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

L'enumerazione GraphicsMode è usata per specificare come interpretare i dati di forma come le coordinate dei rettangoli.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| GM_ADVANCED | Il rendering del testo TrueType DEVE conformarsi pienamente alla trasformazione mondo‑a‑dispositivo corrente nel contesto del dispositivo di riproduzione.<br/>            Gli archi DEVIANO essere disegnati in senso antiorario nello spazio mondo; tuttavia, sia i punti di controllo degli archi <br/>            sia gli archi stessi DEVONO rispettare pienamente la trasformazione mondo‑a‑dispositivo corrente nel contesto del dispositivo di riproduzione.<br/>            La trasformazione mondo‑a‑dispositivo PUÒ essere modificata direttamente utilizzando i record EMR_MODIFYWORLDTRANSFORM o <br/>            EMR_SETWORLDTRANSFORM, o indirettamente modificando le estensioni e le origini della finestra e del viewport, <br/>            utilizzando i record EMR_SETWINDOWEXTEX (sezione 2.3.11.30) e EMR_SETVIEWPORTEXTEX (sezione 2.3.11.28), <br/>            e i record EMR_SETWINDOWORGEX (sezione 2.3.11.31) e EMR_SETVIEWPORTORGEX (sezione 2.3.11.30), rispettivamente.<br/>            In modalità grafica GM_ADVANCED, i bordi inferiori e più a destra DEVONO essere inclusi quando i rettangoli sono disegnati. |
| GM_COMPATIBLE | Il testo TrueType DEVE essere scritto da sinistra a destra e con il lato destro verso l'alto, anche se il resto della grafica <br/>            è ruotato attorno all'asse x o y a causa della trasformazione mondo‑a‑dispositivo corrente nel contesto del dispositivo di riproduzione. Solo l'altezza del testo DOVREBBE essere scalata. Gli archi DEVIANO essere disegnati usando la direzione corrente dell'arco nel contesto del dispositivo di riproduzione, ma NON DEVONO rispettare la trasformazione mondo‑a‑dispositivo corrente, che potrebbe richiedere una rotazione lungo l'asse x o y.<br/>            La trasformazione mondo‑a‑dispositivo DOVREBBE essere modificata solo cambiando le estensioni e le origini della finestra e del viewport <br/>            utilizzando i record EMR_SETWINDOWEXTEX (sezione 2.3.11.30) e EMR_SETVIEWPORTEXTEX <br/>            (sezione 2.3.11.28), e i record EMR_SETWINDOWORGEX (sezione 2.3.11.31) e EMR_SETVIEWPORTORGEX <br/>            (sezione 2.3.11.30), rispettivamente. Cambiare la trasformazione direttamente usando i <br/>            record EMR_MODIFYWORLDTRANSFORM (sezione 2.3.12.1) o EMR_SETWORLDTRANSFORM (sezione 2.3.12.2) POTREBBE NON essere supportato.<br/>            In modalità grafica GM_COMPATIBLE, i bordi inferiori e più a destra DEVONO essere esclusi quando i rettangoli sono disegnati |
