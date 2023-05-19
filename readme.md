# Лабораторная работа №11

### Цель - изучение процесса создания сеансов совместной разработки с использованием инструмента ngrok

```$ sudo snap install ngrok``` - скачиваю ngrok<br />
```$ ngrok config add-authtoken 2PKbzib3vbB0pJOeY3faOrNxOCL_5nFREJMsewBF1Nfgg467t``` - Добавляю свой токен в ngrok.yml для удобной работы с сервисом<br />
```$ sudo apt-get install openssh-server``` - скачиваю сервер <br />
```$ sudo systemctl start ssh``` - запускаю<br />
```$ sudo systemctl status ssh``` - проверяю<br />
новое окно консоли<br />
```$ python3 -m http.server``` - распакова модуля http.server<br />
![Снимок экрана от 2023-05-04 17-48-51](https://user-images.githubusercontent.com/75660322/236249095-11982ee9-f757-4a86-9848-32edefacd4de.png)
новое окно консоли<br />
```$ nano index.html``` - создаю<br />
```$ ngrok tcp 22``` - запускаю TCP туннель<br />
![Снимок экрана от 2023-05-04 17-47-52](https://user-images.githubusercontent.com/75660322/236249116-1440f0c6-efcf-48b5-92f0-5abd3061cb7c.png)<br />
***ssh 6.tcp.eu.ngrok.io -p 12977***
