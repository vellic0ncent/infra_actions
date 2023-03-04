# infra_actions
Учебный проект для изучения работы GitHub Actions (Яндекс Практикум)

### Чтобы запустить проект:

А. Локально

1) Перейдите в папку `infra_project` и запустите сервер:

```bash
cd infra_project
python manage.py runserver
```

2) В docker-контейнере

```bash
docker build .
docker image ls 
docker run -p 5000:5000 <IMAGE_ID>
```
