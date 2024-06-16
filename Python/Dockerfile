FROM python 3.9.18-slim

WORKDIR /app

COPY . /app

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

CMD ["streamlit", "run", "app.py"]