### Посібник користувача: Ticker Link Enhancer - розширення для браузера Chrome

#### Вступ

Ticker Link Enhancer — це розширення для браузера Chrome, яке покращує функціональність перегляду інформації про біржові тікери на платформі Interactive Brokers. Розширення додає зручні іконки поруч з тікерами акцій, дозволяючи швидко отримати доступ до інформації про ці акції на популярних фінансових ресурсах.

#### Встановлення

1. Завантажте розширення з Chrome Web Store
2. Натисніть кнопку "Встановити"
3. Після встановлення у правому верхньому куті браузера з'явиться іконка розширення

#### Основні можливості

- **Автоматичне додавання іконок**: Розширення автоматично визначає тікери акцій на сторінці Interactive Brokers і додає поруч з ними іконки для швидкого доступу до інформації
- **Підтримка популярних фінансових ресурсів**: Надає швидкий доступ до інформації на GuruFocus, Yahoo Finance, Finviz та MarketBeat
- **Режим інкогніто**: Можливість відкривати посилання в режимі інкогніто для приватного перегляду
- **Історія переглядів**: Збереження історії переглянутих тікерів
- **Ручний пошук**: Можливість вручну ввести тікер і отримати посилання на фінансові ресурси

#### Як це працює

##### На сторінці Interactive Brokers

1. Відкрийте будь-яку сторінку на сайті Interactive Brokers (https://www.interactivebrokers.ie/), де відображаються тікери акцій
2. Розширення автоматично визначить тікери та додасть поруч з ними іконки фінансових ресурсів
3. Натисніть на будь-яку іконку, щоб відкрити відповідний ресурс з інформацією про вибраний тікер
4. Залежно від налаштувань, посилання відкриється у звичайному режимі або в режимі інкогніто

##### Налаштування розширення

1. Натисніть на іконку розширення у правому верхньому куті браузера, щоб відкрити меню налаштувань
2. У розділі "Налаштування" ви можете:
   - Вибрати, які іконки фінансових ресурсів будуть відображатися (GuruFocus, Yahoo Finance, Finviz, MarketBeat)
   - Увімкнути або вимкнути режим інкогніто для всіх посилань
   - Натисніть "Зберегти", щоб застосувати зміни

##### Історія переглядів

1. Відкрийте меню розширення та перейдіть на вкладку "Історія"
2. Тут відображаються останні 20 переглянутих тікерів із зазначенням часу перегляду
3. Для кожного тікера доступні посилання на всі підтримувані фінансові ресурси
4. Поруч з кожним посиланням є іконка "🕶", що дозволяє відкрити ресурс у режимі інкогніто
5. Ви можете видалити окремі записи з історії, натиснувши на кнопку "✖" поруч із записом
6. Щоб очистити всю історію, натисніть кнопку "🗑 Очистити історію"

##### Ручний пошук тікерів

1. Відкрийте меню розширення та перейдіть на вкладку "Ручний пошук"
2. Введіть тікер акції в поле вводу
3. Розширення автоматично згенерує посилання на всі підтримувані фінансові ресурси
4. Натисніть на назву ресурсу, щоб відкрити інформацію про тікер
5. Використовуйте іконку "🕶", щоб відкрити ресурс у режимі інкогніто

#### Детальний опис функціональності

##### Підтримувані фінансові ресурси

1. **GuruFocus** - Надає детальну фінансову інформацію, включаючи оцінку вартості акцій, фінансові показники та аналіз від відомих інвесторів
2. **Yahoo Finance** - Популярний ресурс з котируваннями, новинами, фінансовою звітністю та аналітикою
3. **Finviz** - Фінансовий візуалізатор з технічними графіками, скринерами акцій та детальною інформацією про компанії
4. **MarketBeat** - Надає аналітичні дані, рейтинги аналітиків, інсайдерські угоди та дивідендну інформацію

##### Автоматичне оновлення

Розширення постійно відстежує зміни на сторінці Interactive Brokers і автоматично додає іконки до нових тікерів, які з'являються при навігації або оновленні даних. Це забезпечується за допомогою:

- Періодичної перевірки кожні 2 секунди
- Використання MutationObserver для відстеження динамічних змін на сторінці

##### Зберігання даних

Розширення використовує два типи сховища:

1. **chrome.storage.sync** - Для зберігання налаштувань користувача (відображувані іконки, режим інкогніто). Ці налаштування синхронізуються між пристроями користувача.
2. **chrome.storage.local** - Для зберігання історії переглядів тікерів. Історія зберігається локально на пристрої.

#### Технічні особливості

- Розширення працює тільки на домені Interactive Brokers (https://www.interactivebrokers.ie/)
- Для коректної роботи потрібен дозвіл "storage" для зберігання налаштувань та історії
- Розширення використовує service worker для фонової обробки запитів
- Іконки фінансових ресурсів зберігаються локально в папці "ico"

#### Усунення несправностей

##### Іконки не відображаються

1. Переконайтеся, що ви знаходитесь на сайті Interactive Brokers (https://www.interactivebrokers.ie/)
2. Перевірте, що розширення увімкнено (в меню розширень Chrome)
3. Відкрийте налаштування розширення та переконайтеся, що вибрані потрібні іконки для відображення
4. Оновіть сторінку

##### Посилання не відкриваються

1. Перевірте підключення до інтернету
2. Якщо проблема з відкриттям у режимі інкогніто, переконайтеся, що в налаштуваннях Chrome дозволено використання розширень у режимі інкогніто

##### Налаштування не зберігаються

1. Переконайтеся, що ви натиснули кнопку "Зберегти" після зміни налаштувань
2. Перевірте, що у розширення є дозвіл на використання сховища (в налаштуваннях розширень Chrome)

#### Конфіденційність та безпека

- Розширення не збирає і не передає жодні дані на зовнішні сервери
- Історія переглядів зберігається тільки локально на вашому пристрої
- Режим інкогніто забезпечує додаткову приватність при перегляді фінансової інформації

#### Висновок

Ticker Link Enhancer значно спрощує процес дослідження акцій, дозволяючи швидко отримати доступ до інформації про тікери на різних фінансових ресурсах прямо зі сторінки Interactive Brokers. Налаштовувані параметри, історія переглядів та можливість ручного пошуку роблять це розширення потужним інструментом для трейдерів та інвесторів, економлячи час і підвищуючи ефективність аналізу фінансових інструментів.
