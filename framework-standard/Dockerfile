from thecodingmachine/php:8.3-v4-apache-node20

RUN wget https://packages.microsoft.com/config/debian/10/packages-microsoft-prod.deb
RUN sudo dpkg -i packages-microsoft-prod.deb
RUN sudo apt-get update
RUN sudo apt-get install powershell  -y
RUN sudo apt-get install curl -y
RUN sudo apt-get install unzip  -y
RUN sudo apt-get install xvfb  -y
RUN sudo apt-get install libxi6  -y
RUN sudo apt-get install libgconf-2-4 -y
RUN sudo apt-get install default-jdk  -y
RUN sudo apt-get install firefox-geckodriver -y
RUN sudo apt-get install screen -y
RUN sudo apt-get install zip -y
RUN sudo apt-get install mysql-client -y
RUN sudo apt-get install firefox -y
RUN sudo apt-get install inetutils-ping -y
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN sudo ./aws/install
RUN sudo git config --global --add safe.directory '*'
RUN git config --global --add safe.directory '*'