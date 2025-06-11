# vsQUIC
клонируем репозиторий

git clone https://github.com/Taur1n/vsQUIC.git /opt/vsQUIC
обновляем пакетную базу дистрибутива и сразу обновсляем операционную систему

apt update && apt upgrade -y
устанавливаем Python и его пакетный менеджер

apt install python3 python-pip
переходим в целевую папку

cd /opt/vsQUIC
запуск
переходим в соответствующую папку: Server или Client

cd ./server
создаем виртуальное окружение Python

python -m venv venv
переходи в виртуальное окружение

source ./venv/bin/activate
устанавливаем зависимости

pip install -r ./requirements.txt
запускаем .....

python ./quic-srv-.....py
