# tensorflow.Dockerfile
FROM bitnami/tensorflow:latest

# Container içindeki çalışma dizinini ayarla
WORKDIR /usr/src/app

# Yerel dosyaları container içindeki çalışma dizinine kopyala
COPY . .

# Gerekli Python kütüphanelerini yükleyin
RUN pip install --upgrade pip
RUN pip install pandas numpy

ENTRYPOINT [ "python", "app.py" ]
