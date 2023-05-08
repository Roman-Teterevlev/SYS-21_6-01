# SYS-21_6-01
## Задание 1
Ответьте на вопрос в свободной форме.
Чем частное облако отличается от общедоступного, публичного и гибридного?

### Ответ:
Частное облако полностью принадлежит лицу/компании, в публичном (или общедоступном) облаке лицо/компания может взять в аренду нужный объем ресурсов, а в гибридном облаке сочетаются преимущества двух этих моделей. Публичное облако лучше и проще масштабируется, часто надежнее и безопаснее, так как там уже настроено аварийное восстановление. Кроме того, провайдеры публичных облаков предлагают клиентам лучшие технологические решения. Публичное облако подходит почти всем компаниям, частые облака чаще строят в компаниях, подпадающих под специальные требования безопасности, например — в силу законодательных требований к специфике их работы. Гибридное облако выбирают те, кто хочет совместить возможности публичного облака с возможностью соблюдать более суровые требования безопасности в частной инфраструктуре.

## Задание 2
Что обозначают: IaaS, PaaS, SaaS, CaaS, DRaaS, BaaS, DBaaS, MaaS, DaaS, NaaS, STaaS? Напишите примеры их использования.

### Ответ:
1. IaaS (инфраструктура как услуга) - это модель службы облачных вычислений, где вычислительные ресурсы размещаются в публичном облаке, частном облаке или гибридном облаке. С помощью модели IaaS компании могут частично или полностью переместить в облако локальную или распределенную инфраструктуру центра обработки данных, где ее обслуживанием и управлением займется поставщик облачных решений. Примеры IaaS:
+ Разработка и тестирование (при использовании IaaS группы DevOps могут создавать и удалять среды для тестирования и разработки быстро и с низкими затратами, благодаря чему сокращается время вывода новых приложений на рынок);
+ Традиционные приложения (IaaS поддерживает как облачные, так и обычные приложения, в том числе ERP и приложения для бизнес-аналитики);
+ Размещение веб-сайтов и веб-приложений (чтобы оптимизировать расходы, многие компании размещают свои веб-сайты на IaaS. IaaS также поддерживает веб- и мобильные приложения, которые можно быстро развертывать и масштабировать);
+ Хранение, резервное копирование и восстановление (хранение и резервное копирование данных в локальных системах, а также планирование и выполнение аварийного восстановления требуют значительного времени и опыта. Перенос инфраструктуры в облако помогает компаниям сократить затраты и высвободить время для решения других задач);
+ Высокопроизводительные вычисления (благодаря модели «оплата по мере использования» IaaS делает высокопроизводительные вычисления (HPC) и другие проектно-ориентированные задачи, требующие больших объемов данных, более доступными).
+ *Типичные примеры IaaS – виртуальные сервисы Microsoft Azure, Amazon EC2, Timeweb Cloud, Cisco Metacloud, Google Compute Engine (GCE), публичные облака вроде Elastic Cloud.*
2. PaaS (платформа как услуга) - это набор облачных сервисов, который используется для создания и контроля современных приложений и данных локально или в облаке. PaaS предоставляет инфраструктуру и компоненты промежуточного ПО в облаке, которые дают возможность разработчикам и ИТ-администраторам создавать мобильные и веб-приложения, а также управлять ими. Варианты использования PaaS:
+ Подключение и расширение приложений (например, использование готовых встроенных адаптеров для интеграции локальных и облачных приложений);
+ Поддержка разработки современных приложений (например, поддержка языков, платформ и сред на основе открытого кода без ущерба для переносимости);
+ Поддержка блокчейна (обеспечение поддержки API сервиса блокчейна для безопасного обмена информацией и проведения транзакций);
+ Поддержка переноса нагрузок в облако (например, использование функциональной совместимости платформ для обеспечения доступа к инструментам, нагрузкам с целью быстрого развертывания DevTest, функциям аварийного восстановления и производственным средам);
+ Поддержка бизнес-аналитики (например, использование средств и методов для углубленного и расширенного анализа данных в области статистики, прогнозирования и машинного обучения).
+ *Типмчные примеры PaaS: Google App Engine, IBM Bluemix, Microsoft Azure, VMWare Cloud Foundry.*
3. SaaS (ПО как услуга) - это программное обеспечение, размещенное в «облаке» и доступное через Интернет. У пользователей SaaS нет необходимости скачивать и устанавливать приложение к себе на компьютер, ноутбук или смартфон. Они просто оформляют ежемесячную или ежегодную подписку с фиксированной оплатой — ПО размещается на удаленном сервере поставщика услуги и работает в онлайн-режиме.
+ *Пример - стриминговый сервис Netflix.*
4. CaaS - (коммуникация как услуга) - это решение ИТ-аутсорсинга для корпоративной связи, арендованной у одного провайдера. В неё входит сервис интернет-телефонии (передача голоса по IP, то есть VoIP), мессенджеры (IM-приложения), интерфейсы совместной работы или синхронизации изменений в рабочих документах, видеоконференции. Вы заказываете то, что требуется для связи и исключаете затраты на инфраструктуру и программное обеспечение с динамическим расширением мощностей и покрытия по требованию. Другой вариант: (контейнер как услуга) - это модель облачного сервиса, которая позволяет пользователям загружать, редактировать, запускать, останавливать, оценивать и иным образом управлять контейнерами, приложениями и коллекциями. Она обеспечивает выполнение этих процессов с помощью виртуализации на основе инструментов, интерфейса программирования (API) или интерфейса веб-портала. Помогает пользователям создавать многофункциональные, безопасные и фрагментированные приложения через локальные или облачные центры обработки данных.
+ *Примеры: IBM Kubernetes, AWS Container и GoogleContainer Engine.*
5. DRaaS (аварийное восстановление как услуга) - позволяет строить катастрофоустойчивые решения с помощью облака провайдера. Площадка поставщика облачных услуг является при этом «запасным аэродромом», на который постоянно реплицируются данные с основной площадки клиента. При выходе из строя сервисов клиента, они в течении нескольких минут перезапускаются, но уже в облаке. Такие решения особенно интересны компаниям с большим количеством бизнес-критичных приложений.
+ *Пример - Mail.ru Cloud Solutions.*
6. BaaS - (резервное копирование как улуга) - это модель облачных сервисов, обеспечивающая сохранность данных. Другой вариант: Бэкэнд как услуга - в его основе лежит облачная backend-платформа, которая ускоряет и упрощает процесс разработки корпоративных, мобильных и веб-приложений. Третий вариант: Блокчейн как услуга - это уникальный продукт, в котором потребители могут использовать облачные решения для создания, использования и размещения своих блокчейн-решений, функций и смарт-контрактов.
+ *Пример - BAAS Microsoft Azure.*
7. DBaaS - (база данных как услуга) - это облачный сервис предоставляющий возможности подключаться к базам данных развернутых в облаке. Клиент платит за аренду, в зависимости от количества пользователей и объема самой базы. Стоит отметить, что такая база данных никогда не упадет по причине отсутствия свободного места на дисках.
+ *AWS – лидер рынка DBaaS.*
8. MaaS - (мониторинг как услуга) — позволяет отслеживать ключевые параметры инфраструктуры и программного обеспечения, которые вы задаёте через центральную панель управления в веб-интерфейсе онлайн. Пока ещё новое звено этой большой облачной головоломки, но уже считается неотъемлемой частью будущего IT-отрасли и обработки Big Data. Помогает снизить риски непредвиденных расходов и оптимизировать работу предприятия.
+ *Примеры: Amazon CloudWatch, Azure Monitor, Solarwinds, Zabbix.*
9. DaaS - (рабочий стол как услуга) - предоставление пользователям удаленных рабочих столов. С помощью данной услуги можно быстро и с минимальными затратами организовать новый офис, с централизованным управлением рабочих мест. Также, одним из преимуществ данной услуги является возможность работы с любого устройства, что особенно ценно для сотрудников в командировках и постоянных разъездах.
+ *Примеры: Microsoft, V2Cloud, Amazon Workspaces, Citrix, VMware.*
10. NaaS - (сеть как услуга) - позволяет организовать полноценную, сложную сетевую инфраструктуру в облаке провайдера. Этот сервис включает в себя инструменты маршрутизации, организацию безопасности, а также использование различных сетевых протоколов.
+ *Примеры: perimeter 81, PRISMA, CLOUDFLARE, Cisco PLUS, Megaport.*
11. STaaS - (хранилище как услуга) - предоставление дискового пространства в облаке провайдера. При этом для пользователей такое пространство будет обычной сетевой папкой или локальным диском. Сильная сторона данного решения заключается в повышенной безопасности данных, так как в облаке провайдера работают надежные системы хранения данных.
+ *Примеры: Google Drive, Dropbox, Яндекс.Диск.*

## Задание 3
Ответьте на вопрос в свободной форме.
Напишите, какой вид сервиса предоставляется пользователю в ситуациях:
+ Всеми процессами управляет провайдер - SaaS.
+ Вы управляете приложением и данными, остальным управляет провайдер - PaaS или SaaS.
+ Вы управляете операционной системой, средой исполнения, данными, приложениями, остальными управляет провайдер - IaaS.
+ Вы управляете сетью, хранилищами, серверами, виртуализацией, операционной системой, средой исполнения, данными, приложениями - Colocation.

## Задание 4
Вы работаете ИТ-специалистом в своей компании. Перед вами встал вопрос: покупать физический сервер или арендовать облачный сервис от Yandex Cloud.
Выполните действия и приложите скриншоты по каждому этапу:

1. Создать платёжный аккаунт:
+ зайти в консоль;
+ выбрать меню биллинг;
+ зарегистрировать аккаунт.
2. После регистрации выбрать меню в консоли Computer cloud.
3. Приступить к созданию виртуальной машины.

<img width="960" alt="6-01_4 1" src="https://user-images.githubusercontent.com/132853752/236874279-9cb7d044-a826-4ea3-b0a0-b1c655b266e3.png">

<img width="960" alt="6-01_4 2" src="https://user-images.githubusercontent.com/132853752/236874349-f8dc9178-f025-4230-82f1-49f88fedd88d.png">

<img width="960" alt="6-01_4 3" src="https://user-images.githubusercontent.com/132853752/236874414-1aae9c8c-ecc9-483b-a0e0-e0bf8d9442de.png">

Ответьте на вопросы в свободной форме:
+ Какие ОС можно выбрать?
*18 вариантов (Ubuntu, Debian, CentOS, Fedora, FreeBSD и др.).*
+ Какие параметры сервера можно выбрать?
*Тип физического процессора, наличие GPU и набор допустимых конфигураций vCPU и RAMб а также тип жесткого диска HDD/SSD и его объем, кроме того, варианты сетевых настроек и параменры доступа.*
+ Какие компоненты мониторинга можно создать?
*На Cloud.Market в разделе инструменты для разработчика возможно установить систему мониторинга Zabbix.*
+ Какие системы безопасности предусмотрены?
*Защита от DDOS-атак, оплачиваемая за каждый очищенный гигабайт, на Cloud.Market в разделе безопасность можно выбрать антивирусные продукты, межсетевые экраны и vpn-серверы, предусмотрен вход на удаленный серсер по SSH ключам.*
+ Как меняется цена от выбранных характеристик? Приведите пример самой дорогой и самой дешёвой конфигурации.
*Цена изменяется в большую или меньшую сторону в зависимости от выбранных характеристик, для Ubuntu от 450 руб. до 2,5 млн руб. в месяц.*

*Дополнительные задания* (со звёздочкой)*
*Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.*

## Задание 5*
Выполните действия и приложите скриншот:
+ Создайте виртуальную машину на Yandex Cloud.
+ Создайте сервисный аккаунт.
+ Отсканируйте SSH-ключ.
+ Придумайте логин.
+ Подключитесь к облаку через SSH.
