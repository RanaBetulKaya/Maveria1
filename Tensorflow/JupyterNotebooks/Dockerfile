# Dockerfile
FROM jupyter/tensorflow-notebook

WORKDIR /home/jovyan/work

COPY . /home/jovyan/work

RUN pip install --upgrade pip
RUN pip install pandas

USER root
RUN chown -R jovyan:users /home/jovyan/work
USER jovyan


EXPOSE 8888

CMD ["jupyter-lab", "--ip=0.0.0.0", "--no-browser", "--allow-root"]


