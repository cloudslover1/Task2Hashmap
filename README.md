# Task Прототип, Фабричный метод, Абстрактный суперкласс, Реализация Hashmap
Фабричный метод — это порождающий паттерн проектирования, который определяет общий интерфейс для создания объектов в суперклассе, позволяя подклассам изменять тип создаваемых объектов.

Abstract Superclass. Класс, выступающий в этой роли, представляет собой абстрактный суперкласс, в котором инкапсулирована общая логика связанных классов. Связанные классы расширяют этот класс. Таким образом, они могут наследовать его методы. Методы с одинаковыми сигнатурами и общей логикой для всех связанных классов помещаются в суперкласс, поэтому логика этих методов может наследоваться всеми подклассами данного суперкласса. Методы с зависящей от конкретного подкласса данного суперкласса логикой, но с одинаковыми сигнатурами, объявляются в абстрактном классе как абстрактные методы, тем самым гарантируя, что каждый конкретный подкласс будет иметь методы с такими же сигнатурами.

Программа представляет собой приложение реализующие паттерны: Прототип, Фабричный метод, Абстрактный суперкласс и технологию HashMap, 
которое позволяет рисовать фигуры в указанном месте, выбирая их из списка, отрисовка фигур производится на основе технологии HashMap
через паттерн "Фабричный метод"

Рабочее окно приложения

![image](https://user-images.githubusercontent.com/74301524/230320743-f7a0014f-a375-4085-a70a-b489a20d0de6.png)

Архитектура

![image](https://user-images.githubusercontent.com/74301524/230321151-ba717799-ec36-4898-bb22-c028e1a22eab.png)
