---
title: "IAsyncTask-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Hämtar ett värde som indikerar om den här uppgiften för närvarande körs. |
| is_canceled | bool | r | Hämtar ett värde som indikerar om den här uppgiften avbröts. |
| is_faulted | bool | r | Hämtar ett värde som indikerar om den här uppgiften misslyckades. |
| result | System.Object | r | Hämtar resultatet av den här uppgiften. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Avbryter den här uppgiften.<br/>            Uppgiften avslutas omedelbart, med risken att interna ohanterade resurser inte frigörs. |
| cancel() | Avbryter den här uppgiften.<br/>            Uppgiften avslutas säkert genom kontrollerad stoppning av algoritmen. |
| run_async() | Kör den här uppgiften. |
| wait_on_done() | Väntar tills uppgiften är klar. |


