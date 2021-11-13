# Wildhack 80-20-MP
## Запуск
Авторизуйтесь в GHCR по [персональному токену](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
```
$ export CR_PAT=YOUR_TOKEN
$ echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
> Login Succeeded
```
Запустите приложение
```
$ docker-compose up
```
