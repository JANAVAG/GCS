# GCS

CREACION DEL BUCKET:

gsutil mb -p sit-devops-training -c nearline -l us-east4 -b on gs://sit-devops-training-bkt05

CREACION DEL ARCHIVO:

touch renato.txt
touch antonio.txt
touch armando.txt

COPIA DE ARCHIVO:

gsutil cp renato.txt gs://sit-devops-training-bkt05
gsutil cp antonio.txt gs://sit-devops-training-bkt05
gsutil cp armando.txt gs://sit-devops-training-bkt05
