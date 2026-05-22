---
title: "IAsyncTask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Asenkron görev."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Asenkron görev.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Asenkron görevin ilerleme olayı işleyicisini alır. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Asenkron görevin ilerleme olayı işleyicisini ayarlar. |
| [isBusy()](#isBusy--) | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değeri alır. |
| [isCanceled()](#isCanceled--) | Bu görevin iptal edilip edilmediğini gösteren bir değeri alır. |
| [isFaulted()](#isFaulted--) | Bu görevin hatalı olup olmadığını gösteren bir değeri alır. |
| [getError()](#getError--) | Görev tamamlandıktan sonra mevcut olan görev hatasını alır. |
| [getResult()](#getResult--) | Bu görevin sonucunu alır. |
| [runAsync()](#runAsync--) | Bu görevi çalıştırır. |
| [runAsync(int priority)](#runAsync-int-) | Bu görevi çalıştırır. |
| [cancel()](#cancel--) | Bu görevi iptal eder. |
| [abort()](#abort--) | Bu görevi durdurur. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Tamamlayıcı geri çağırma temsilcisini ayarlar. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Asenkron görevin ilerleme olayı işleyicisini alır.

Değer: Asenkron görevin ilerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Asenkron görevin ilerleme olayı işleyicisini ayarlar.

Değer: Asenkron görevin ilerleme olayı işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | asenkron görevin ilerleme olayı işleyicisi. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Bu görevin şu anda çalışıp çalışmadığını gösteren bir değeri alır.

Değer: Bu görev şu anda çalışıyorsa `true`; aksi takdirde `false`.

**Returns:**
boolean - bu görevin şu anda çalışıp çalışmadığını gösteren bir değer.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Bu görevin iptal edilip edilmediğini gösteren bir değeri alır.

Değer: Bu görev iptal edildiyse `true`; aksi takdirde `false`.

**Returns:**
boolean - bu görevin iptal edilip edilmediğini gösteren bir değer.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Bu görevin hatalı olup olmadığını gösteren bir değeri alır.

Değer: bu görev hatalıysa `true`; aksi takdirde `false`.

**Returns:**
boolean - bu görevin hatalı olup olmadığını gösteren bir değer.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Görev tamamlandıktan sonra mevcut olan görev hatasını alır.

Değer: Görev hatası.

**Returns:**
java.lang.Throwable - görev tamamlandıktan sonra mevcut olan görev hatası.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Bu görevin sonucunu alır.

Değer: Bu görevin sonucu.

**Returns:**
java.lang.Object - bu görevin sonucu.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Bu görevi çalıştırır.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Bu görevi çalıştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öncelik | int | İş parçacığı önceliği. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Bu görevi iptal eder. Görev, algoritmanın kontrollü durdurulmasıyla güvenli bir şekilde tamamlanır.

### abort() {#abort--}
```
public abstract void abort()
```


Bu görevi durdurur. Görev, dahili yönetilmeyen kaynakların serbest bırakılmama riskiyle hemen tamamlanır.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Tamamlayıcı geri çağırma temsilcisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Tamamlayıcı geri çağrı. |

