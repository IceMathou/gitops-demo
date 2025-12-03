FROM python:3.10-slim
WORKDIR /app
COPY app.py ./
RUN pip install \
    flask==1.1.1 \
    jinja2==2.11.3 \
    markupsafe==2.0.1 \
    itsdangerous==1.1.0 \
    werkzeug==1.0.1
EXPOSE 5000
CMD ["python", "app.py"]
