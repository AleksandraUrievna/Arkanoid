# Arkanoid


Арканоид разработанный на движке Unreal Engine 4.25 c помощью Blueprints. Идейным вдохновителем выступила игра BreakQuest.

Суть игры в том, что игрок контролирует небольшой планер, который можно передвигать горизонтально от одной стенки к другой, подставляя её под шар, предотвращая его падение вниз. Удар шара по блоку приводит к его разрушению.

Была проделана такая работа:

1) Настроены UI для главного меню, меню уровней, опций и геймбара, в последнем идет подсчет очков, количество уцелевших блоков и количество жизней.

 ![Screenshot_4](https://user-images.githubusercontent.com/65093579/88804743-061cea00-d1b7-11ea-85af-0727579c0bb6.png)
 ![Screenshot_1](https://user-images.githubusercontent.com/65093579/88804787-1339d900-d1b7-11ea-84c2-078666d5f91f.png)
![Screenshot_2](https://user-images.githubusercontent.com/65093579/88804792-15039c80-d1b7-11ea-8e11-12fc4102dd0b.png)
![Screenshot_9](https://user-images.githubusercontent.com/65093579/88804799-1765f680-d1b7-11ea-9790-c6351158a504.png)
![Screenshot_14](https://user-images.githubusercontent.com/65093579/88804812-1a60e700-d1b7-11ea-942f-c2ebce5436e6.png)
 
Ниже график Блупринтов Режима игры с помощью которого работает гейм бар .
 
![Screenshot_15](https://user-images.githubusercontent.com/65093579/88804874-2fd61100-d1b7-11ea-81b9-71c9d7deb9fc.png)

2) Настроена траектория полета шара с помощью Blueprints, также добавлено в качестве гейм-фич ускорение мяча. Ниже график Блупринтов мяча.

![Screenshot_10](https://user-images.githubusercontent.com/65093579/88804946-42e8e100-d1b7-11ea-9d12-a4081fd0fe92.png)
 
3)Настроены звуковые эффекты, музыкальное сопровождение уровня.

4)Первый уровень состоит из трех фигур, собранных из блоков.

![Screenshot_3](https://user-images.githubusercontent.com/65093579/88804987-4ed4a300-d1b7-11ea-9938-910bee587829.png)
 
5)Настроены партиклы в хвосте планера, добавлен хвост из частиц к шару и дым при разрушении блоков.

![Аркада](https://user-images.githubusercontent.com/65093579/88805049-5ac06500-d1b7-11ea-8922-b285624735a8.jpg)
 
6)Второй уровень усложнен тремя лопастями, которые крутятся без остановки, тем самым, при попадании на них шара, меняют угол его траектории.
 
![Screenshot_6](https://user-images.githubusercontent.com/65093579/88805128-71ff5280-d1b7-11ea-8581-e1953a66b408.png)
![Screenshot_7](https://user-images.githubusercontent.com/65093579/88805131-71ff5280-d1b7-11ea-8b12-2c25e6225c66.png)
![Screenshot_8](https://user-images.githubusercontent.com/65093579/88805126-70ce2580-d1b7-11ea-8a1f-0a6ed6057414.png)
 
7) Проведена работа с материалами, текстурами  и мешами.
