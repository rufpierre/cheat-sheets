concatener des fichiers directement sur le bucket
---
```
gsutil compose gs://<PATH>/part-000{0,1,2}* gs://<PATH>/<DST_FILE>
```
