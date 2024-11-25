# Лабораторная 4
Я установила приложение aafire в контейнер, введя в Dockerfile команду ```RUN apt-get install -y libaa-bin``` . Командой ```aafire``` в контейнере проверила его работу: <br><br>
![](aafire.jpg) <br><br>
Результат вывода списка работающих контейнеров на машине:
![](2containers.jpg) <br><br>
Подключение контейнеров к созданной сети и результаты команды ```docker network inspect myNetwork```:<br><br>
![](network.jpg) <br><br>
Командой ```ping``` проверила связь между контейнерами:<br><br>
![](ping.jpg) <br><br>
