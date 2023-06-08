FROM releases-docker.jfrog.io/jfrog/pipelines-u18java:17

CMD sudo apt remove docker docker-engine docker.io

CMD sudo apt update

CMD sudo apt install apt-transport-https ca-certificates curl software-properties-common

CMD curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

CMD sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

CMD sudo apt update

#apt-cache policy docker-ce

CMD sudo apt install docker-ce

#CMD sudo systemctl status docker

#CMD sudo usermod -aG docker ${USER}
