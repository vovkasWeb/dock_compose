FROM python:3
WORKDIR /src
COPY /equirements.txt ./
RUN pip install --no-cache-dir -r /src/requirements.txt
COPY /main/* /myapp/

CMD [ "python", "/myapp/main.py" ]