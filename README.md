# ocp-storage
Argo repo for (csgo operator) storage data

Based on the yandex s3 k8s driver:  
https://github.com/yandex-cloud/k8s-csi-s3

## Backend
Data is hosted on a MinIO deployment at `10.0.1.60`.  
Each bucket receives its own `StorageClass`.