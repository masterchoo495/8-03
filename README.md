### Задание 1

**Что нужно сделать:**

1. Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в [этом репозитории](https://github.com/netology-code/sdvps-materials/tree/main/gitlab).   
2. Создайте новый проект и пустой репозиторий в нём.
3. Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.

В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

### Решение

1. Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в [этом репозитории](https://github.com/netology-code/sdvps-materials/tree/main/gitlab).   
![alt text](https://github.com/masterchoo495/8-03/blob/main/img001.png)

2. Создайте новый проект и пустой репозиторий в нём.
![alt text](https://github.com/masterchoo495/8-03/blob/main/img002.png)

3. Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.
![alt text](https://github.com/masterchoo495/8-03/blob/main/img003.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img004.png)

---

### Задание 2

**Что нужно сделать:**

1. Запушьте [репозиторий](https://github.com/netology-code/sdvps-materials/tree/main/gitlab) на GitLab, изменив origin. Это изучалось на занятии по Git.
2. Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.

В качестве ответа в шаблон с решением добавьте: 
 * файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне; 
 * скриншоты с успешно собранными сборками.

 ### Решение

1. Запушьте [репозиторий](https://github.com/netology-code/sdvps-materials/tree/main/gitlab) на GitLab, изменив origin. Это изучалось на занятии по Git.
![alt text](https://github.com/masterchoo495/8-03/blob/main/img005.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img006.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img007.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img008.png)

3. Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.
![alt text](https://github.com/masterchoo495/8-03/blob/main/img009-1.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img009.png)

![alt text](https://github.com/masterchoo495/8-03/blob/main/img010.png)

---
## Дополнительные задания* (со звёздочкой)

Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

---

### Задание 3*

Измените CI так, чтобы:

 - этап сборки запускался сразу, не дожидаясь результатов тестов;
 - тесты запускались только при изменении файлов с расширением *.go.

В качестве ответа добавьте в шаблон с решением файл gitlab-ci.yml своего проекта или вставьте код в соответсвующее поле в шаблоне.
