FROM python:3.8-alpine3.12
RUN pip install redis==3.5.3 \
    && pip install requests==2.25.1
COPY worker.py /
CMD ["python", "worker.py"]
