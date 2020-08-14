# postsReactNative

![photo](maket_rn.jpg)

Необходимо разработать мобильное приложение на React Native с использованием Redux под Android.
Для оценки задания прислать apk-файл и исходный код приложения.

Описание:

Экраны:
- авторизация
- список
- элемент

Авторизация:
Элементы:
- заголовок
- произвольный текст, который занимает 2/3 экрана
- поле для ввода логина
- поле для ввода пароля
- Кнопка подтверждения
Авторизация не производится, логин сохраняется для последующего отображения на других экранах
При вводе значений в текстовых полях появляющаяся клавиатура не должна перекрывать элементы

Список
На экране используется структура json формата:
[
        {
              id: (тип integer
                title: (тип string), // произвольный текст до 200 символов
                description: (тип string), // произвольный текст от 100 до 400 символов
        }
]

Шапка должна состоять (все в одной строке):
- заголовок 'Список'
- логин, введенный на странице авторизации
Элемент списка должен включать в себя только заголовок. При нажатии на который должно открываться окно/страница "Элемент"

Элемент
На экране в шапке должны быть заголовок "Элемент" и логин, введенный на странице авторизации
Ниже должно отображаться описание элемента (свойство description)

Внизу экрана должны быть кнопки "назад" и "выход". При нажатии на кнопку "назад" приложение должно возвращаться на экран "список", при нажатии на "выход" - на страницу авторизации с очищением в памяти логина и введенных значений
