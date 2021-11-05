# Тестовое задание
1 Задание. Составить список девайсов для тестирования мобильного приложения Velas Wallet на платформах Android/IOS

Browser:Google Chrome,Safari (для ОС: Android,IOS). Хотя в других источниках считают что на 2 месте браузер является Firefox. Сафари есть только в Айфоне, в других платформах его не бывает.

https://gs.statcounter.com/browser-market-share

Разрешение Экрана для Android 
1.2400 x 1800 (31,1%)
2.2340 х 1080 (26,2%)
3.Other (20,2%)

https://bloha.ru/news/samoe-populyarnoe-razreshenie-yekrana-n/

А также девайсы:(Я бы к примеру закупил:Apple,Samsung,Xiaomi,Huawei)
1.Samsung Galaxy M52 XIAOMI REDMI 9 (2400 х 1080) 
2. SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080) 
3.SAMSUNG Galaxy A12 XIAOMI Redmi 9 (1600x720)
Самые востребованные девайсы.
OS: Android (актуальные: 9 10 11)

https://ru.wikipedia.org/wiki/%D0%98%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B9_Android

IOS (актуальные: 12 13 14) так как на данный момент большинство людей еще пользуются предыдущими версиями Айфон(Взял бы последние 3 актуальные версии а именно:Iphone X, Iphone 11, Iphone 12).

https://www.itrew.ru/smartphone/iphone-poslednie-i-aktualnye-modeli.html

IOS 12 была представлена 4 июня 2018 года
(Поддерживает такие устройства):
iPhone 5s
iPhone SE
iPhone 6
iPhone 6 Plus
iPhone 6s
iPhone 6s Plus
iPhone 7
iPhone 7 Plus
iPhone 8
iPhone 8 Plus
iPhone X
iPhone XR
iPhone XS
iPhone XS Max

IOS 13 выпущена 19 сентября 2019 года. Поддерживает такие устройства:
iPhone
iPhone SE
iPhone 6s
iPhone 6s Plus
iPhone 7
iPhone 7 Plus
iPhone 8
iPhone 8 Plus
iPhone X
iPhone XR
iPhone XS
iPhone XS Max
iPhone 11
iPhone 11 Pro
iPhone 11 Pro Max
iPhone SE (2 поколения)
iPod Touch
iPod Touch (7)

Разрешение экрана / Девайсы | OS | Browser |
------------ | ------------- | -------------
Samsung Galaxy M52 XIAOMI REDMI 9 (2400 x 1080) | Android 9 | Google Chrome
SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080)  | Android 10 | Google Chrome
SAMSUNG Galaxy A12 XIAOMI Redmi 9 (Other)  | Android 11 | Google Chrome
IphoneX | IOS 12 | Safari
Iphone 11 | IOS 13 | Google Chrome
Iphone 12 | IOS 14 | Safari

Выполняем попарное тестирование

Разрешение экрана / Девайсы | OS | Browser |
------------ | ------------- | -------------
Samsung Galaxy M52 XIAOMI REDMI 9 (2400 x 1080) | Android 9 | Google Chrome
SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080) | Android 9 | Google Chrome
SAMSUNG Galaxy A12 XIAOMI Redmi 9 (Other) | Android 9 | Google Chrome
Samsung Galaxy M52 XIAOMI REDMI 9 (2400 x 1080 | Android 10 | Google Chrome
SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080) | Android 10 | Google Chrome
SAMSUNG Galaxy A12 XIAOMI Redmi 9 (Other) | Android 10 | Google Chrome
Samsung Galaxy M52 XIAOMI REDMI 9 (2400 x 1080) | Android 11 | Google Chrome
SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080) | Android 11 | Google Chrome
SAMSUNG Galaxy A12 XIAOMI Redmi 9 (Other) | Android 11 | Google Chrome
IphoneX | IOS 12 | Google Chrome
IphoneX | IOS 12 | Safari
IphoneX | IOS 13 | Google Chrome
IphoneX | IOS 13 | Safari
Iphone 11 | IOS 13 | Google Chrome
Iphone 11 | IOS 13 | Safari
IphoneX | IOS 14 | Google Chrome
IphoneX | IOS 14 | Safari
Iphone 11 | IOS 14 | Google Chrome
Iphone 11 | IOS 14 | Safari
Iphone 12 | IOS 14 | Google Chrome
Iphone 12 | IOS 14 | Safari

И ТОГО

Разрешение экрана / Девайсы | OS | Browser |
------------ | ------------- | -------------
Samsung Galaxy M52 XIAOMI REDMI 9 (2400 x 1080) | Android 9 | Google Chrome
SAMSUNG Galaxy A50 XIAOMI Redmi 9 (2340 х 1080) | Android 10 | Google Chrome
SAMSUNG Galaxy A12 XIAOMI Redmi 9 (Other) | Android 11 | Google Chrome
IphoneX | IOS 12 | Google Chrome
Iphone 11 | IOS 13 | Google Chrome
Iphone 12 | IOS 14 | Google Chrome
IphoneX | IOS 12 | Safari
Iphone 11 | IOS 13 | Safari
Iphone 12 | IOS 14 | Safari

Для Huawei специальная ОС,которая набирает сейчас популярность

Девайсы | OS | Browser |
------------ | ------------- | -------------
Huawei P50 | HarmonyOS | Google Chrome
HUAWEI P Smart 2021 | HarmonyOS | Google Chrome

2 Написать чек-лист на логин/регистрацию в веб приложение кошелька https://wallet.velas.com.

Чеклист

1. Убедитесь,что при нажатии https://wallet.velas.com появляется окно ”Выбор языка”. 
2. Убедитесь,что при выборе языка,появляется окно приветствия и выбор “Создать” или “восстановить” аккаунт.
3. При нажатии кнопки “Создать”, убедитесь в том,что появляется окно пароля.  
4. Убедитесь в том,что при нажатии на поле пароль,появляется подсказка об предложенном валидном пароле.
5. Убедитесь в том,что корректный пароль (PIN) это 4 цифры.
6. Убедитесь в том,что если нажать на кнопку “Установить” при пустом поле,то появится уведомление “PIN - это 4 цифры”.
7. Убедитесь в том,что если ввести пароль,который содержит до 4 цифр и нажать на кнопку “Установить”,то появится уведомление “PIN - это 4 цифры”.
8. Убедитесь в том,что если ввести пароль,который содержит до 4 букв и нажать на кнопку “Установить”,то появится уведомление “PIN - это 4 цифры”.
9. Убедитесь в том, что если ввести пароль,который содержит больше 4 цифр - корректный PIN и нажать на кнопку “Установить”,появляется окно под названием “Новая сид фраза”.
10. Убедитесь в том, что если ввести пароль,который содержит больше 4 букв - корректный PIN и нажать на кнопку “Установить”,появляется окно под названием “Новая сид фраза”.
11. Убедитесь в том,что при нажатии на кнопку “Установить”,появляется окно под названием “Новая сид фраза”.
12. Убедитесь в том,что в окне “Новая сид фраза” находятся валидные кнопки такие как: “Назад”, “Распечатать”,”Далее”.
13. Убедитесь в том,что в окне “Новая сид фаза” находятся 24 сид-фразы.
14. Убедитесь,что при нажатии на кнопку “Распечатать”,появляется pdf file “recovery-sheet-24.pdf”.
15. Убедитесь в том,что при нажатии кнопки “Далее”,появляется окно “Подтвердите сид фразу”.
16. Убедитесь в том,что сид-фразу,в поле ввода сид-фразы следует вводить корректно.
17. Убедитесь в том,что при вводе некорректной сид-фразы,появляется ошибка: “Слова не совпадают”.
18. Убедитесь в том,что при вводе другой сид-фразы,появляется ошибка: “Слова не совпадают”.
19. Убедитесь,что при подтверждении всех 24 слов, вас перенаправляет в окно “Terms of use“.
20. Убедитесь в том,что при нажатии на кнопку “Подтвердить”,появляется главное меню аккаунта.
