# Проект 2-го спринта: задание
Посвящён Яндекс Маршрутам и состоит из четырёх заданий. Прочитай их целиком, прежде чем приступать к работе. 
Постановка задачи
Предстоит протестировать каршеринг: составить тестовую документацию, выполнить проверки, завести баг-репорты.
Вот макеты 
 https://www.figma.com/design/42mNwme0cBfZwNZUIcN1mh/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81.%D0%9C%D0%B0%D1%80%D1%88%D1%80%D1%83%D1%82%D1%8B?node-id=2-18586&node-type=canvas&t=uyTgjNwzTTAuzdRy-0 
и требования
 https://praktikum.notion.site/74dd6e68fda34387ac4d43137a601c6e
к каршерингу (можно выбрать один любой тариф).
# 1. Подготовь чек-лист на вёрстку полей
Выбери один тариф: например, «Роскошный».
Если требования и макеты не сходятся — ориентируйся на требования. 
Составь чек-лист на вёрстку следующих блоков:
форма бронирования;
элементы на навигационной карте: это иконки автомобилей и действия с ними.
Предварительная работа:
Внимательно изучи макеты каршеринга в Figma — вкладка Marshruti car sharing.
В макетах каршеринга не хватает блока «Требования к заказу». Но практически аналогичные макеты для «Требований к заказу» лежат на вкладке с такси: Marshruti taxi → UI-kit.
Так вышло, потому что твои коллеги-дизайнеры ещё не успели подготовить UI kit для каршеринга. Так бывает.

Не переживай: вёрстка элементов (например, чекбоксов) в такси и каршеринге одинаковая, отличаются только тарифы и текст. Подробнее о работе панели «Требования к заказу» в каршеринге можно прочитать в текстовых требованиях.
Составление чек-листа:
Выбери только один тариф и составь чек-лист, по которому будешь тестировать вёрстку формы бронирования и вёрстку элементов на навигационной карте.
Учитывай орфографию, расположение элементов, их внешний вид.
Обрати внимание: 
✔️ У полей «Добавить права» и «Способ оплаты» есть разные состояния. Например, у поля «Добавить права» таких состояний два: документы прошли верификацию; документы не прошли верификацию. 
✔️ Окна «Машина забронирована», «Вы уверены, что хотите отменить поездку?» и «Поездка отменена» тоже нужно покрыть тестами.
✔️ Иконки машин — тоже часть вёрстки. Например, по требованиям иконка ближайшей машины увеличивается и над ней появляется чёрная плашка с маркой.
❌ Не нужно покрывать тестами валидацию полей. 
❌ Не нужно покрывать тестами вёрстку окон «Добавление прав», «Способ оплаты», «Добавление карты». Это значит, что тебе не надо нажимать на поля «Добавить права» и «Способ оплаты» и «проваливаться» дальше, в следующие окна.
# ![chrome_kYGj8QjgIe](https://github.com/user-attachments/assets/9841a98d-8bfc-4533-a5c1-b6fed8b4efab)
# ![chrome_90qI8VzVlh](https://github.com/user-attachments/assets/751cac14-3a90-41fd-895b-c94a9230f708)
# ![chrome_l9ArcnSR9X](https://github.com/user-attachments/assets/575b7ab6-1a74-4dd7-b1e3-c2a3c84efd00)

# 2. Подготовь чек-лист и тест-кейсы на логику работы окон
Составь следующую тестовую документацию: 
чек-лист на логику окон «Способ оплаты» и «Добавление карты»,
тест-кейсы на кнопку «Забронировать».
Подробности
Предварительная работа:
Для чек-листа изучи такие пункты требований: «Поле „Способ оплаты“» и «Окно „Добавление карты“».
Для тест-кейсов на кнопку «Забронировать» — см. пункт требований «Кнопка „Забронировать“».
Составление чек-листа:
Составь чек-лист, по которому будешь проверять логику окон «Способ оплаты» и «Добавление карты».
Там, где необходимо, используй технику разбиения на классы эквивалентности и выделения граничных значений. Отправлять КЭ и ГЗ ревьюеру не нужно, это только для тебя.
Не забудь про позитивные и негативные проверки.
Подготовка тест-кейсов:
Составь тест-кейсы на логику работы кнопки «Забронировать».
Не забудь про позитивные и негативные проверки.
Пропиши предусловия.
Обрати внимание: 
На кнопке «Забронировать» указаны расстояние и время в пути. Например: «Маршрут составит 3 км и займёт 4 мин.» Тебе не нужно проверять, правильно ли рассчитаны эти данные.
# ![chrome_chpNV5BIyV](https://github.com/user-attachments/assets/cf9044f0-038e-47f4-b2e1-672144ba97c3)
# ![chrome_cPNTkdSIAG](https://github.com/user-attachments/assets/f524fd25-a00b-45e9-9b31-9cbb98f23929)
# ![chrome_rSOM7S01dC](https://github.com/user-attachments/assets/6433e619-458c-4a60-a147-6fe6a08cda07)

Ссылка на Youtrack https://gamanstela.youtrack.cloud/issues?q=tag:%20%7BSprint2Practice%7D

Ссылка на гугл таблицу https://docs.google.com/spreadsheets/d/1Ezg1M_SYMQjvvMUMBANzAyFRmAQAIZsmEG58782tjlg/edit?usp=sharing


