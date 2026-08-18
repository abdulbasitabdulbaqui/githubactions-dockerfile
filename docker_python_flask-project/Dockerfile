FROM python:3.6
COPY . /app
WORKDIR /app
RUN apt-get update && apt-get install -y python3 python3-pip && pip3 install --no-cache-dir --break-system-packages -r requirements.txt
EXPOSE 5000
#ENTRYPOINT ["python"]
#CMD ["app.py"]
CMD ["python", "app.py"]
