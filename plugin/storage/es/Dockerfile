FROM python:3-alpine
RUN pip install elasticsearch elasticsearch-curator
COPY esCleaner.py /es-index-cleaner/
CMD ["python3", "/es-index-cleaner/esCleaner.py"]
