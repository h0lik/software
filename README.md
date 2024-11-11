# Work script:
### Install
Установка:  в папку opt клонируем репозиторий 
```bash
sudo -i 
cd /opt
git clone  https://github.com/h0lik/software.git
```
### Install - work-help
```bash
ln -s /opt/software/work-help /usr/local/bin/work-help
```
### Install gen-sha
```bash
ln -s /opt/software/gen-sha /usr/local/bin/gen-sha
```
- Скрипт хеширует пароль который вы ему передаете в SHA512
### Install ssh-host
```bash
ln -s /opt/software/ssh-host /usr/local/bin/ssh-host
```
- Скрипт показывает все алиасы SSH (Это в директории **.ssh** файл config)

