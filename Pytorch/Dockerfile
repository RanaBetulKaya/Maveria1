# tensorflow.Dockerfile
FROM pytorch/pytorch

# Container içindeki çalışma dizinini ayarla
WORKDIR /usr/src/app

# Yerel dosyaları container içindeki çalışma dizinine kopyala
COPY . /usr/src/app

# Gerekli Python kütüphanelerini yükleyin
RUN pip install --upgrade pip
RUN pip install pandas numpy jupyterlab


CMD ["python", "app.py"]
