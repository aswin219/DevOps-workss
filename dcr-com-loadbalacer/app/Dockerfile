FROM python:alpine
EXPOSE 5007
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD python app.py
