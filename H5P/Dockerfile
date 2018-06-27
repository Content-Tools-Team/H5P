FROM python:2.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
<<<<<<< 5bb366e95c6ae83b92c2baa9a2e37804e75c9ae1
RUN pip install -r requirements.txt
RUN apt-get install default-libmysqlclient-dev
ADD . /code/
RUN pip install H5PP-0.1.9.tar.gz
RUN cp .env.docker .env
=======
ADD . /code/
RUN pip install -r requirements.txt
RUN pip install H5PP-0.1.9.tar.gz
RUN apt-get install default-libmysqlclient-dev

>>>>>>> Added docker file
