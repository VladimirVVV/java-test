Базовое задание (по основам):
- Создать класс Matrix с полем двухмерного массива вещественных чисел и методами: сложение с другой матрицей, умножение на другую матрицу, транспонирование, вывод на печать. Написать метод main, создающий несколько матриц и использующий их методы.
- Определить систему из 3х классов: «фигура», «прямоугольник», «треугольник». Фигура должна быть абстрактным классом с абстрактным методом вывода на экран, методом перемещения и абстрактным методом масштабирования. Имплементация функций вывода на экран должна выводить в System.out координаты свойства фигуры в текстовом виде.
- Создать массив различных фигур с помощью Random и нарисовать их (вывести в текстовом виде координаты и размер). Определить соответствие фигура = индекс и вывести его на экран. Это соответствие должно устанавливаться с помощью reflection или с помощью ключевого слова.


Основное задание (веб-разработка):
Написать веб-ориентированную систему, которая содержит информацию о пользователях и их ролях. Пользователь должен иметь такие свойства как: логин, пароль, имя, фамилия, отчество, дата рождения. Каждая сущность роли, должна иметь такие свойсва как: название роли и описание роли. Каждый пользователь системы может иметь как одну роль, так и две роли. Всего в системе должно быть 2 роли: юзер и администратор. При запуске приложения, пользователю должна отображаться страница с авторизацией. Если пользователь не зарегистрирован - он должен иметь возможность зарегистрироваться. Всем пользователям, которые регистрируются, автоматически присваивается роль "юзер". Если пользователь уже зарегистрирован - он может залогиниться в систему. Если при логине в систему, у пользователя роль "юзер", то его должно после логина перекинуть на страницу, где выведеться текст "Привет, имя_пользователся!". Если у пользователся роль "администратор", то его должно перекинуть на страницу со списком всех пользователей, в котором будут отображаться все пользователи и все их поля. Администратор может удалить любого пользователя из этого списка, отредактировать иноформацию о пользователе, изменить роль любого пользователя или же создать нового пользователя. Если пользователь имеет роль и администратора и юзера, то при логине его должно перебросить на промежуточную страницу, где будут две ссылки "К странице администратора" и "К странице пользователя". При переходе по этим ссылкам должна отображаться соответсвующая информация.
Также необходимо реализовать политику безопасности в системе, чтобы пользователь не мог по прямой ссылке перейти на страницу, для которой у него нет прав. Также при добавлениии, редактировании или регистрации пользователей, информация должна проходить валидацию: все поля должны быть обязательными для заполнения, дата рождения должна приниматься только в определенном формате.
Приложение должно быть написано на Spring, для проверки ролей можно использовать Spring Security, для работы с базой данных нужно использовать Hibernate с использованием аннотаций. Для отображения можно использовать JSP или JSF(на свое усмотрение).
