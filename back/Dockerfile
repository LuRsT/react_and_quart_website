FROM python


COPY . /opt/app

WORKDIR /opt/app

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "main.py"]
