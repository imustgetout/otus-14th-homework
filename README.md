
### Dockerfile

Создайте свой кастомный образ nginx на базе alpine. 

После запуска nginx должен отдавать кастомную страницу (достаточно изменить дефолтную страницу nginx)

Определите разницу между контейнером и образомВывод опишите в домашнем задании.

Ответьте на вопрос: Можно ли в контейнере собрать ядро?

Собранный образ необходимо запушить в docker hub и дать ссылку на ваш репозиторий.



Что должно быть Dockerfile:

FROM image name

RUN apt update -y && apt upgrade -y 

COPY или ADD filename /path/in/image

EXPOSE portopenning

CMD or ENTRYPOINT or both

#не забываем про разницу между COPY и ADD#or - одна из опций на выбор
