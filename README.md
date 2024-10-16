## Культура принятия решений на данных

Принятие управленческих решений на основе данных - тренд не новый, основы этого принципа были сформулированы еще в начале XX века. Терабайты данных, логи пользователей и любой цифровой след ежедневно становятся источником принятия решений для бизнеса. Поэтому игнорировать большие данные неразумно, но и обработать их одним условным менеджером со скоростью, которая диктуется рынком, не получится.

Подразделения BigData выводят компании на новый уровень, обогащая опыт и экспертизу своих сотрудников искусственным интеллектом, машинным обучением и алгоритмами обработки больших данных. Бизнес-процессы ускоряются, их автоматизация минимизирует количество ошибок, связанных с ручной обработкой данных.


В профсообществах все еще есть разногласия в определении методов data informed и data driven, тема не раз поднималась во многих статьях.

С нашей точки зрения, ключевое отличие, по которому компания может считаться data driven, – это максимальная чистота данных, высокий приоритет технологического развития компании, а также наличие бизнес-модели, в которой цифры имеют больший вес в принятии решений, чем интуиция менеджмента.

На этапе низкого или среднего уровня доверия результатам отработки машинных алгоритмов data-informed подход в принятии решений считается оптимальным (в сравнении с data-driven):

он достаточно гибкий, но основан на логике, закономерностях и статистическом анализе;

высвобождает ресурсы команд за счет автоматизированной агрегации данных и их первичного анализа;

практически не имеет слепых зон, оставляя место креативности, контексту, нюансам, опыту, аномалиям и исключениям из правил.

Deli – часть data-informed подхода «Ленты»
Фундамент ритейла – ассортимент товаров на полке в магазине. Если сильно упрощать, то ассортимент должен: закрывать потребности покупателя и приносить прибыль владельцу бизнеса.

Если ассортимент - не узкая ниша, а 99% товаров относятся к FMCG, как в «Ленте», то выполнение условий обязательно для каждой из сотен групп товаров. Это же условие соблюдается для бизнеса с широкой географией. В «Ленте» каждое SKU на полке в отдельной секции каждого магазина в каждом городе должно быть доходным, оборачиваемым, востребованным покупателем и желательно - дешевле, чем у конкурента.

Еще в 2019 году наша команда запустила первые пилоты по локализации ассортимента: пробовали наполнять полку, учитывая потребности покупателей конкретного магазина. Для управления матрицей товаров с такой гранулярностью требовалась прозрачная методология определения товаров-аутсайдеров и топовых позиций, агрегация огромного объема информации и, конечно, единое окно принятия решений.

Мы разработали логику рейтинга товаров Top-Flop и использовали ее в алгоритме рекомендаций для каждого магазина. Этот алгоритм вырос до первого MVP приложения и на А/В тестировании показал, что использование нового подхода дает существенный прирост товарооборота в пилотных магазинах.

Как только мы убедились в полезности и окупаемости решения, мы начали разработку Deli (de - delisting/вывод, li - listing/ввод) - аналитического инструмента и рекомендательной системы управления ассортиментом.

Это стало большим шагом к внедрению в «Ленте» data-informed подхода и движению к data-driven: предобработка и анализ больших данных, поиск решений и оценка их влияния на бизнес теперь не замыкаются на конкретном менеджере, а скорость принятия решений - увеличивается.

Главные пользователи Deli
Deli предназначен для сотрудников, ответственных за формирование ассортимента «Ленты»:

федеральных менеджеров категорий,

менеджеров категорий в дивизионах,

директоров по управлению категориями и коммерческих директоров,

аналитиков.

У нас более 120 сотрудников активно используют Deli ежемесячно, и мы ожидаем, что с развитием продукта это число будет только расти. Инструмент стал неотъемлемой частью многоступенчатого бизнес-процесса управления ассортиментом, что помогло нам существенно его оптимизировать

Многозадачный Deli: уровень его возможности
Deli собирает и обрабатывает данные из различных источников и дает рекомендации по изменению ассортиментной матрицы. На вход Deli поступает огромное количество информации:

матрица с данными по категориям продаж на различных уровнях географии (федерация, дивизион, город);

более 30 ключевых показателей за 12 месяцев из более чем 10 витрин данных (их мы обновляем ежедневно);

20 атрибутов для каждого товара;

аналитический прогноз продаж;

мерчструктура и матрешка;

рыночные данные Nielsen;

мониторинг цен и ассортимента конкурентов;

методология TOP-FLOP ранжирования товаров;

эффект от изменений.


В распоряжении пользователя основные KPI товаров и их динамика, ценовое позиционирование «Лента» vs Конкуренты с анализом GAP, рекомендации алгоритма по вводу/выводу/ротации товара, текущая и будущая структура ассортимента. 

На основе этих данных пользователь оценивает выполнение целевых показателей и принимает обоснованное решение об оптимизации матрицы. Пользователь может использовать подсказки алгоритмов Deli или вносить изменения вручную на основе собственной экспертизы, а также оценивает будущий экономический эффект своих действий.

С начала 2024 года создано больше 10 000 сессий для анализа эффективности разных категорий товаров. Мы постепенно увеличиваем конверсию пользователей в инструмент за счет нового функционала, расширения покрытия ассортимента товаров, добавления новых показателей и атрибутов.

Кейс #1: даем прочное основание вывода неэффективных SKU


Причины вывода товара из ассортимента или его замены могут быть разными: от снятия товара с производства и несоблюдения требований по качеству до низкого рейтинга и превышения квот. За 8 месяцев 2024 года из ассортимента «Ленты» выведено или ротировано почти 7000 SKU – колоссальное количество, которое демонстрирует гибкость и скорость в изменении полки магазина.

30% этих товаров (более 2000) выведено на основании данных и рекомендаций Deli:

- низкий рейтинг FLOP – мы отказываемся от малоэффективных или убыточных SKU, напрямую влияя на величину оборота компании;

- переквот (т.е. превышение планового количества товара) – мы соблюдаем вместимость полки, поэтому у каждого товара есть место и возможность завоевать сердце покупателя и, может быть, стать локомотивом всей категории;

- низкий уровень перформанса – мы следим, достаточно ли быстро новинки набирают обороты и как зрелый ассортимент их сбавляет, реагируем раньше, чем это может повлиять на общие показатели категории.
