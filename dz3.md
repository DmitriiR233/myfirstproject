# 1. ServiceLocator
Определение: Это как "диспетчер", который помогает найти нужный сервис.
Пример: В ресторане вы просите администратора найти официанта или повара.

# 2. DIP (Dependency Inversion Principle)
Определение: Нужно зависеть от общих правил (абстракций), а не от конкретных вещей.
Пример: Вы используете любой шнур USB-C, а не только от одного производителя.

# 3. IoC (Inversion of Control)
Определение: Кто-то другой (например, Spring) управляет зависимостями за вас.
Пример: Преподаватель сам решает, какие вопросы задать на экзамене, а не вы.

# 4. Singleton
Определение: Класс, у которого может быть только один экземпляр.
Пример: В стране может быть только один президент.

# 5. Prototype
Определение: Создание нового объекта через копирование существующего.
Пример: Клонирование овечки Долли — создание копии вместо нового животного.

# 6. Юнит-тесты (JUnit)
Определение: Тесты, которые проверяют работу маленьких частей программы.
Пример: Проверка, что калькулятор правильно складывает числа.

# 7. Mockito (mock + spy)
Определение: Инструмент для создания "поддельных" объектов в тестах.
Пример: Тестирование оплаты без реального банковского сервиса.

# 8. @SpringBootTest
Определение: Аннотация для тестирования всего приложения Spring целиком.
Пример: Проверка, как все детали автомобиля работают вместе.

# 9. @Autowired
Определение: Spring сам подставляет нужные зависимости в ваш код.
Пример: Вы заказываете пиццу, а Spring "приносит" её вам.

# 10. @Component
Определение: Аннотация, которая говорит Spring: "Этот класс — важная часть приложения".
Пример: Деталь конструктора, которая нужна для сборки игрушки.

+1 Уникальный факт
Факт: Spring создаёт объекты только тогда, когда они действительно нужны, чтобы не тратить лишние ресурсы.
