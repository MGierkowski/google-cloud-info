## Ceny usługi Cloud Storage
**Warunki darmowego korzystania z usługi**
Warunki darmowego korzystania z usługi na koncie typu *free*
|Zasoby|Darmowe limity  |
|--|--|
|Standard Storage|5GB miesięcznie|
|Operacje klasy A*|5000|
|Operacje klasy B*|50000|

**Standardowe opłaty za korzystanie z usługi**
*Podane ceny stanowią koszty za każdy 1GB w rozliczeniu miesięcznym i różnią się w zależności od regionu*
Region|Standard Storage|Nearline Storage  |Coldline Storage|Archive Storage|
|--|--|--|--|--|
|US (multi-region)|$0.026  |$0.010|$0.007|$0.004|
|EU (multi-region)|$0.026  |$0.010|$0.007|$0.004|
|Asia (multi-region)|$0.026  |$0.010|$0.007|$0.004|
|europe-west1|$0.020|$0.010|$0.004|$0.0012|
|europe-west2|$0.023|$0.013|$0.007|$0.0025|
|europe-west3|$0.023|$0.013|$0.006|$0.0025|
Link do cennika gdzie można znaleźć opłaty dla innych regionów
[Cennik](https://cloud.google.com/storage/pricing)

**Ceny przenoszenia danych do innego segmentu lub udostępnienia ich dla innej usługi**
|W tej samej lokalizacji|Pomiędzy innymi częściami tego samego kontynentu  |
|--|--|
| za darmo | $0.01 za każdy GB |
*Ceny przenoszenia między kontynentami wahają się od $0.08 do $0.25 za 1GB
**Cennik operacji**
|Storage class|Class A Operation|Class B Operation|Free|
|--|--|--|--|
|Standard Storage|$0.05|$0.004|free|
|Nearline Storage|$0.10|$0.01|free|
|Coldline Storage|$0.10|$0.05|free|
|Archive Storage|$0.50|$0.50|free|

**Opis klas operacji**
|Rodzaj operacji|Class A Operation|Class B Operation|Free|
|--|--|--|--|
|JSON API|storage.*.insert1 <br>storage.*.patch<br>  storage.*.update  <br>storage.*.setIamPolicy  <br>storage.buckets.list  <br>storage.buckets.lockRetentionPolicy  <br>storage.notifications.delete  <br>storage.objects.compose  <br>storage.objects.copy  <br>storage.objects.list  <brstorage.objects.rewrite  <br>storage.objects.watchAll  <br>storage.projects.hmacKeys.create  <br>storage.projects.hmacKeys.list  <br>storage.*AccessControls.delete<br>|storage.*.get  <br>storage.*.getIamPolicy  <br>storage.*.testIamPermissions <br> storage.*AccessControls.list  <br>storage.notifications.list  <br>Each object notification<br>|storage.channels.stop  <br>storage.buckets.delete  <br>storage.objects.delete  <br>storage.projects.hmacKeys.delete <br>
|XML API|GET Service <br>GET Bucket (when listing objects in a bucket) <br> PUT <br> POST<br>|GET Bucket (when retrieving bucket configuration)  <br>GET Object  <br>HEAD|DELETE|
|Object Lifecycle Management|SetStorageClass||Delete|
<br>Link do kalkulatora dla każdej usługi 

[Kalkulator](https://cloud.google.com/products/calculator/)

