# В качестве базового слоя взять с Docker Hub готовый образ nginx:1.22.1.
# Скопировать в создаваемый образ конфиг-файл nginx.conf.
# Сервер Nginx ожидает найти файл с настройками по адресу /etc/nginx/templates/default.conf.template, вот туда его и скопируем из директории gateway/.

FROM nginx:1.22.1
COPY nginx.conf /etc/nginx/templates/default.conf.template