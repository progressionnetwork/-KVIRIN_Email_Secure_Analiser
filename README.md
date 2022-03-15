# -KVIRIN_Email_Secure_Analiser
# Хакатон Startup Hackathon 12|21.

## Case \ Кейс: Group-IB
## Task \ Задача: Разобраться в различных техниках проведения BEC-атак и разработать подходы, позволяющие обнаруживать их на ранних стадиях.
### Command \ Команда: Security Band \ 2021.


## Dashboard, панель администратора:
Кабинет администратора позволяет оценить вероятность поддельного (фейкового) письма и статус проверки ML алгоритмов.
The admin area allows you to assess the likelihood of a fake (fake) email and the status of the ML algorithm check.
![alt text](https://github.com/progressionnetwork/-KVIRIN_Email_Secure_Analiser/blob/main/image_2021-12-11_09-37-35.png?raw=true)


## Технические мероприятия

Поскольку BEC-письма не содержат ссылок, вложений и, как правило, не имеют типичных признаков вредоносных писем, традиционные защитные решения не справляются с их выявлением. Помочь тут может комплексная защита для электронной почты с использованием искусственного интеллекта и машинного обучения.

Мы используем ИИ-инструмент, получивший название BEC Protector. Он имитирует процесс принятия решения специалистом по безопасности. Для этого система оценивает провайдера, от которого отправлено письмо, сопоставляет адрес электронной почты отправителя с действительным адресом организации. Если письмо пришло от руководителя организации, производится проверка наличия такого руководителя в штатном расписании, а также его доступность по контактным данным.

На следующей стадии экспертная система выполняет контент-анализ содержимого электронного письма, выявляя намерения отправителя на предмет характерных для BEC-писем факторов — срочности, важности и требований выполнить финансовые действия. Результаты анализа передаются в систему машинного обучения.

Если в письме не выявлено ничего подозрительного, в дело вступает система анализа стиля текста — Writing Style DNA («ДНК стиля письма»). Эта разработка  использует систему машинного обучения, чтобы сравнить послание руководителя или контрагента с его предыдущими сообщениями. Writing Style DNA использует более 7 тысяч характеристик сообщения для выявления уникального стиля отправителя. В их числе использование заглавных букв в словах и знаков препинания, длина предложений, излюбленные слова и выражения и многое другое.

Для создания модели стиля искусственному интеллекту требуется проанализировать от 300 до 500 ранее отправленных писем. Важный момент: для защиты конфиденциальности ИИ извлекает только метаданные, характеризующие стиль отправителя, но не сам текст.

## Что в итоге

Компрометация деловой переписки отличается от обычных атак минимальной технологичностью. Успех BEC-атак напрямую зависит от качества собранной информации и работы социальных инженеров. Фактически эти атаки ближе к обычному «офлайновому» мошенничеству, что и обуславливает сложность противодействия им с помощью традиционных технических решений.

Успешно выявлять и блокировать BEC-атаки позволяет использование защитных систем на базе машинного обучения и искусственного интеллекта в сочетании с обучением сотрудников и другими организационными мероприятиями.

## Technical measures

Since BEC emails do not contain links, attachments, and generally do not have the typical signs of malicious emails, traditional security solutions fail to detect them. Comprehensive protection for emails using artificial intelligence and machine learning can help.

We use an AI tool called BEC Protector. It simulates the decision-making process of a security specialist. It does this by evaluating the provider the email was sent from, comparing the sender's email address to the actual address of the organization. If the email came from the head of the organization, the system checks if the head is on the staff, and if he is available by contact information.

At the next stage, the expert system performs a content analysis of the email content, identifying the intentions of the sender on the factors characteristic to BEC emails - urgency, importance and requirements to perform financial actions. The results of the analysis are sent to the machine learning system.

If nothing suspicious is detected, the Writing Style DNA is used. This project uses machine learning to compare an executive's or counterparty's message to previous messages. Writing Style DNA uses over 7,000 message characteristics to identify the sender's unique style. These include the use of capitalization in words and punctuation marks, sentence length, favorite words and expressions, and more.

Artificial Intelligence needs to analyze between 300 and 500 previously sent emails to build a style model. To protect confidentiality, the AI only extracts metadata describing the sender's style, but not the text itself.

## What's the bottom line

Business correspondence compromise differs from usual attacks by its minimal technological sophistication. The success of BEC attacks directly depends on the quality of collected information and the work of social engineers. These attacks are in fact closer to regular "offline" fraud, which makes them quite difficult to counter with the traditional technical solutions.

The use of machine learning and artificial intelligence-based defenses, combined with employee training and other organizational measures, can successfully detect and block BEC attacks
