FROM python
MAINTAINER DEEPU
RUN apt install python3 -y
RUN mkdir /dockerTest
COPY test.py /dockerTest/test.py
WORKDIR /dockerTest
CMD python3 /dockerTest/test.py
