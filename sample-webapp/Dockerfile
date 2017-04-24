# This file is used to execute e2e tests for the project.
FROM python:2.7-alpine
RUN pip install webapp2 && \
pip install webob
COPY app.py /root/
COPY app.yaml /root/
COPY server.py /root/
# Replace this line with a realistic test script.
ENTRYPOINT ["python", "/root/server.py"]
