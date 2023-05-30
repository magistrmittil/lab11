# Лабораторная работа №11

### Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok<br />
```$ ngrok config add-authtoken 2PKbzib3vbB0pJOeY3faOrNxOCL_5nFREJMsewBF1Nfgg467t``` - Добавляю свой токен в ngrok.yml для удобной работы с сервисом<br />
```$ sudo apt-get install openssh-server``` - скачиваю сервер <br />
```$ sudo systemctl start ssh``` - запускаю<br />
```$ sudo systemctl status ssh``` - проверяю<br />
новое окно консоли<br />
```$ python3 -m http.server``` - распакова модуля http.server<br />
![Image alt](https://github.com/magistrmittil/lab11/blob/master/SCREENSHOT.png)<br />
![Image alt](https://github.com/magistrmittil/lab11/blob/master/SCREEN2.png)<br />

```$ nano index.html``` - создаю<br />
```$ ngrok tcp 22``` - запускаю TCP туннель<br />
![Image alt](https://github.com/magistrmittil/lab11/blob/master/SCREEN3.png)<br />
***ssh 6.tcp.eu.ngrok.io -p 12977***
