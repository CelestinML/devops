FROM python:3.9

COPY ./pyflux.py /code/

COPY ./requirements.txt /code/

WORKDIR /code

EXPOSE 5000

RUN pip install -r requirements.txt

ENTRYPOINT [ "python3" ]

CMD [ "pyflux.py" ]
