FROM python:3.10.12

LABEL authors="sinu"

WORKDIR /app

COPY ./requirement.txt .
RUN pip3 install -r ./requirement.txt

COPY . .

EXPOSE 8000

CMD ["python3","Main.py"]