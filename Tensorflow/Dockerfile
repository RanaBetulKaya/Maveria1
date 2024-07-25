# tensorflow.Dockerfile
FROM tensorflow/tensorflow:latest

# Container içindeki çalışma dizinini ayarla
WORKDIR /usr/src/app

# Yerel dosyaları container içindeki çalışma dizinine kopyala
COPY . /usr/src/app

# Gerekli Python kütüphanelerini yükleyin
RUN pip install --upgrade pip
RUN pip install pandas numpy


CMD ["python", "app.py"]