# Связываем локальный и удалённый репозитории

``$ cd ~/dev/first-project
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git``

# Убедиться, что репозитории связаны

``git remote -v``

## Синхронизируем локальный и удалённый репозитории
В первый раз эту команду нужно вызвать с флагом -u

``$ git push -u origin ``