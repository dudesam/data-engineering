# Getting Started with Data Enngineering 

# Введение
Меня зовут Дмитрий Аношин, я решил создать курс по Инжинирингу данных и поделиться знаниями по работе с данными и созданию аналитических решений, которые я накопил работаю в этой области с 2010 года. 

В те времена понятия Инженер данных не существовало. Было несколько вакансий, которые отвечали за работу с данными:
-	Разработчик Business Intelligence
-	Разработчик Хранилищ Данных (DW)
-	Разработчик ETL
Позже появились вакансии Data Scientist, Machine Learning Engineer, Data Engineer, разработчик BI стал называться BI Engineer. 

Начиная с 2016 года я работаю в Амазон в Канаде Инженером Данных. В своем курсе я хочу помочь вам овладеть этой специальностью с 0. Так же с прошлого года я стал вести свой телеграм канал, в котором постоянно публикую новости и полезные материалы связанные с инжинирингом данных (https://t.me/rockyourdata)

Для того чтобы вам определиться подходит вам этот курс или нет, я хочу рассказать чуть-чуть побольше про свой курс.

Прежде всего, для меня существует два типа Инженера Данных:
1.	Программист, который стал Инженером Данных
2.	BI/DW/ETL разработчик, который стал Инженером Данных

Давайте подробнее рассмотрим отличия. Задача Инженера Данных создание платформы данных, куда автоматически загружаются данные, там они трансформируются в доступную форму для конечных пользователей, как правило бизнес пользователей. 

Источники данных могут быть разными: реляционные базы данных, SFTP, API, файлы с логами, сенсоры. Типа данных тоже может быть разный – структурированные данные в табличном формате, полу-структурированные данные (JSON, XML) и не структурированные данные (видео, аудио).

В зависимости от бизнес требования, Инженеру данных необходимо создать поток данных (data pipeline), который автоматически будет забирать данные и загружать их в платформу данных (хранилище данных или озеро данных). Вам необходимо выбрать инструменты для работы с данными. 

Цель у нас простая, помочь бизнесу извлечь ценную информацию из данных, для этого нужно создать аналитическое решение, где пользователи могут самостоятельно работать с данными, проверять свои гипотезы и анализировать бизнес, используя правильные метрики. 

Чтобы построить такое решение, нужен Инженер Данных. В моем случает это не просто создание потока данных, трансформация и загрузка данных, это полноценная работа с бизнес подразделениями, понимание их нужд и предоставление им инструментов для решения их задач. Я имею ввиду весь цикл построения аналитического решения. Именно это мы будем изучать на курсе. 

И теперь самое интересно, в зависимости от вашего опыта, вы можете использовать языки программирования Java/Python и т.д. для создания решения - типа Инженера Данных №1 (Technical Data Engineer), а можете использовать готовые решения, которые позволять вам создавать масштабируемы и безопасные решения, быстро достигать результаты – типа Инженера Данных №2 (пусть будет Result Oriented Data Engineer). 

Без программирования не обойтись даже для 2го типа, но вам не надо быть гуру программистом, достаточно понимать, как работает Python и использовать небольшие куски кода для кастомизации решения. 

Таким образом, в своем курсе я хочу вам помочь лучше понимать требования бизнеса и создавать end-to-end аналитическое решение. Для этого мы начнем с азов BI и SQL, рассмотрим классические примеры использования ETL, и потом начнем работу с облачными решениями, используя Amazon Web Services (Redshift, Elastic Map Reduce, Spectrum, Glue). Конечно же затронем тему стриминга данных и озер данных. 

Главное в этом курсе даже не зубрежка программирования или конкретного продукта, а понимания принципов по работе с данными, классов инструментов и возможных бизнес задач и пути их решения, а для всего остального есть Google;)


