FROM python:3.11

WORKDIR /usr/src/app

COPY requirements.txt ./

EXPOSE 5000

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python3", "app.py" ]