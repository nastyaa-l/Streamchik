# Анализ игрового интернет-магазина

Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

Исходные данные - исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы.

На первом этапе мы выявили и заполнили средним значенимяи пропуски, где это было возможно. Удалили дубликаты в данных по строке название-жанр-год выпуска. А также добавили столбец с общим количеством проданных копий во всех регионах.

На втором оценили как стоит распределять кампанию на 2017 год:
<br> - Платформы PS4, XOne, WiiU - находятся на этaпе своего роста и развития, поэтому основные суммарные продажи следует ожидать от этих платформ. Особое внимание следует уделить плафторпме PS4, так как в предыдущие годы предшествующие выерси платформы PS2 и PS3 были самыми популярными в Северной Америке и Европе, а также количество миллионов копий проданных на джанной платформе сущесвтенно выше, чем на остальных.
<br> - Наиболее популярные жанры игр shooter, sports, platformr.
<br> - Вляиние оценки критиков на суммарные продажи среднее. Оценки пользователей незначительно влияют на продажи.
<br> - Игры с рейтингом Е имеют большее количество проданных копий. При этом певрончально игр с таким рейтингом больше остальных, а также большое количество игр не имеющих рейтинг. Для более подробного анализа рекомендуется улучшить сбор данных, уменьшить пропущенные значения.

На третьем эатпе были проверены 2 гипотезы, обе из которых не удалось опровергнуть, это значит, что мы можем говорить о том, что:
1. Средние пользовательские рейтинги платформ Xbox One и PC одинаковые.
2. Средние пользовательские рейтинги жанров Action и Sports одинаковые.

Таким образом, рекламный бюджет следует выделить на платфору PS4 c жанром Shooter и рейтингом М, рекламировать в регмонах Северной Америки и Европы. Отзывы критиков и пользователей незначительно влияют на продажи, поэтому на них обращать внимание не стоит.
