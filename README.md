задача 2 


высоконагруженная база данных MySql, критичная к отказу - паравиртуализация, т.к. меньше расходов на эмуляцию, большая производительность


различные web-приложения - виртуализация уровня ос, т.к. быстрая работа с версиями-контейнерами


Windows-системы для использования бухгалтерским отделом - паравиртуализация на основе hyper v от майкрософт, также меньше расходов на эмуляцию, больше свободных ресурсов


системы, выполняющие высокопроизводительные расчёты на GPU - тут сложно сказать, смотря какая ситуация, если брать как пример рендер-фермы, т оскорее всего паравиртуализация опять же за счет снижения затрат на эмуляции ресурсов


Задача 3

1.  Для этой задачи я бы использовал hyper v, т.к. в основном windows based виртуалки нужны, линукс также можно использовать

2. Xen в режиме PV. стабильаня система, а режим pv лучше показывается себя с windows, чем hpv(полная виртуализация)

3. однозначно hyper v

4. kvm- нативный для линукс систем

Задача 4 

первое что приходит в голову- сложности с перемещением виртуальных машин между разными системами. для минимизации рисков необходимо четко продумать инфраструктуру и на базе каких ос она будет построена из чего будет понятен выбор необходимого средства управления в качестве основного. я бы не стал использовать гетерогенную среду виртуализации без особых на то необходимых причин.
