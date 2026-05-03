FROM ubuntu:bionic

RUN yum update -y && \
    yum install -y python3 python3-pip && \
    python3 -m pip install pyfiglet termcolor

ADD missile.py /

CMD ["/usr/games/fortune", "missile.py"]
