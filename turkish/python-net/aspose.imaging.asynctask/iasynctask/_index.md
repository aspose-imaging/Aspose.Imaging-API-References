---
title: "IAsyncTask Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| is_busy | bool | r | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değer döndürür. |
| is_canceled | bool | r | Bu görevin iptal edilip edilmediğini gösteren bir değer döndürür. |
| is_faulted | bool | r | Bu görevin hatalı olup olmadığını gösteren bir değer döndürür. |
| result | System.Object | r | Bu görevin sonucunu alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| abort() | Bu görevi iptal eder.<br/>            Görev hemen tamamlanır, dahili yönetilmeyen kaynakların serbest bırakılmama riski vardır. |
| cancel() | Bu görevi iptal eder.<br/>            Görev, algoritmanın kontrollü durdurulmasıyla güvenli bir şekilde tamamlanır. |
| run_async() | Bu görevi çalıştırır. |
| wait_on_done() | Görev tamamlanana kadar bekler. |


