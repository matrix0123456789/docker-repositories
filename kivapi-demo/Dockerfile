FROM thecodingmachine/php:8.4-v5-apache-node22

RUN sudo composer global require kivapi/kivapi-cli
RUN cd /
RUN sudo git clone https://github.com/GreenCodeStudio/kivapi-clean.git app
RUN cd /app
RUN sudo kivapi build
