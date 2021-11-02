FROM python:3.7.3
LABEL maintainer="Test Test <test@gmail.com>"
LABEL version="0.1"
LABEL description="Test"

WORKDIR /data

RUN pip install numpy pandas==0.24.2  seaborn==0.9.0 jupyter

EXPOSE 8888

CMD ["jupyter","notebook","--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]
