Создал файл с тестовой job в локальном репозитории. Создал новый проект и в нем файл с еще одной тестовой job.
![](remote.png)
![](smoke.png)
Указал в pipeline первого проекта include.
![](pipeline.png)
Однако пробный аккаунт не дает создать public репозиторий, поэтому include не сможет его достать.
![](settings.png)
Вот результат job без remote include.
![](result.png)