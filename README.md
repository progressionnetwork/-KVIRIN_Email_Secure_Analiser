# -KVIRIN_Email_Secure_Analiser
# Хакатон Startup Hackathon 12|21.

## Кейс: Group-IB
## Задача: Разобраться в различных техниках проведения BEC-атак и разработать подходы, позволяющие обнаруживать их на ранних стадиях.
### Команда Security Band \ 2021.


## Dashboard, панель администратора:
Кабинет администратора позволяет оценить вероятность поддельного (фейкового) письма и статус проверки ML алгоритмов.
![alt text](https://github.com/progressionnetwork/-KVIRIN_Email_Secure_Analiser/blob/main/image_2021-12-11_09-37-35.png?raw=true)


## Технические мероприятия

Поскольку BEC-письма не содержат ссылок, вложений и, как правило, не имеют типичных признаков вредоносных писем, традиционные защитные решения не справляются с их выявлением. Помочь тут может комплексная защита для электронной почты с использованием искусственного интеллекта и машинного обучения.

В Trend Micro мы используем ИИ-инструмент, получивший название Expert System. Он имитирует процесс принятия решения специалистом по безопасности. Для этого система оценивает провайдера, от которого отправлено письмо, сопоставляет адрес электронной почты отправителя с действительным адресом организации. Если письмо пришло от руководителя организации, производится проверка наличия такого руководителя в штатном расписании, а также его доступность по контактным данным.

На следующей стадии экспертная система выполняет контент-анализ содержимого электронного письма, выявляя намерения отправителя на предмет характерных для BEC-писем факторов — срочности, важности и требований выполнить финансовые действия. Результаты анализа передаются в систему машинного обучения.

Если в письме не выявлено ничего подозрительного, в дело вступает система анализа стиля текста — Writing Style DNA («ДНК стиля письма»). Эта разработка Trend Micro использует систему машинного обучения, чтобы сравнить послание руководителя или контрагента с его предыдущими сообщениями. Writing Style DNA использует более 7 тысяч характеристик сообщения для выявления уникального стиля отправителя. В их числе использование заглавных букв в словах и знаков препинания, длина предложений, излюбленные слова и выражения и многое другое.

Для создания модели стиля искусственному интеллекту требуется проанализировать от 300 до 500 ранее отправленных писем. Важный момент: для защиты конфиденциальности ИИ извлекает только метаданные, характеризующие стиль отправителя, но не сам текст.

## Что в итоге

Компрометация деловой переписки отличается от обычных атак минимальной технологичностью. Успех BEC-атак напрямую зависит от качества собранной информации и работы социальных инженеров. Фактически эти атаки ближе к обычному «офлайновому» мошенничеству, что и обуславливает сложность противодействия им с помощью традиционных технических решений.

Успешно выявлять и блокировать BEC-атаки позволяет использование защитных систем на базе машинного обучения и искусственного интеллекта в сочетании с обучением сотрудников и другими организационными мероприятиями.
