## 1 СОДЕРЖАНИЕ:

1 СОДЕРЖАНИЕ

2 ОБЩИЕ ПОЛОЖЕНИЯ	

2.1 Полное наименование системы и ее условное обозначение	

2.2 Номер договора (контракта)	

2.3 Наименования организации-заказчика и организаций-участников работ	

2.4 Перечень документов, на основании которых создается система	

2.5 Плановые сроки начала и окончания работы по созданию системы	

2.6 Источники и порядок финансирования работ	

2.7 Порядок оформления и предъявления заказчику результатов работ по созданию системы	

2.8 Перечень нормативно-технических документов, методических материалов, использованных при разработке ТЗ	

2.9 Определения, обозначения и сокращения	

3 НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ СИСТЕМЫ	

3.1 Назначение системы	

3.2 Цели создания системы	

4 ХАРАКТЕРИСТИКА ОБЪЕКТА АВТОМАТИЗАЦИИ

5 ТРЕБОВАНИЯ К СИСТЕМЕ	

5.1 Требования к системе в целом	

5.1.1 Требования к структуре и функционированию системы	

5.1.2 Требования к надежности	

5.1.3 Требования к безопасности	

5.1.4 Требования к эргономике и технической эстетике	

5.1.9 Требования к защите информации от несанкционированного доступа	

5.1.10 Требования по сохранности информации при авариях

5.2 Требования к функциям (задачам), выполняемым системой	

6 СОСТАВ И СОДЕРЖАНИЕ РАБОТ ПО СОЗДАНИЮ (РАЗВИТИЮ) СИСТЕМЫ	

7 ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ СИСТЕМЫ	

7.1 Виды, состав, объем и методы испытаний системы	

8 ИСТОЧНИКИ РАЗРАБОТКИ	


 ##  2 ОБЩИЕ ПОЛОЖЕНИЯ
 
2.1 Полное наименование системы и ее условное обозначение

Система контроля игр на бильярде – (СК)
  
2.2 Номер договора (контракта)

123456789

2.3 Наименования организации-заказчика и организаций-участников работ

Заказчик – организация “BSUIR Billiard Club”

Организация исполнитель – “Bedyuk Soft”.

2.4 Перечень документов, на основании которых создается система

Лист технического задания.

2.5 Плановые сроки начала и окончания работы по созданию системы

01.10.22 – 01.12.22

2.6 Источники и порядок финансирования работ

Источник финансирования: Заказчик

20% - после подписания договора

30% - после показа прототипа системы

50% - после сдачи проекта

2.7 Порядок оформления и предъявления заказчику результатов работ по созданию системы

Каждую неделю компания-исполнитель обязана присылать отчет о проделанных работах. 

По окончанию всех работ компания-исполнитель обязана предоставить исходный код программы заказчику.

Во время разработки и после приёма работы компанией-заказчиком, компания-исполнитель не имеет права предоставлять программное обеспечение другим заказчикам.

2.8 Перечень нормативно-технических документов, методических материалов, использованных при разработке ТЗ

Документация ЯП С++

Документация SQL баз данных

ГОСТ 34.602-89

Правила игры в снукер

2.9 Определения, обозначения и сокращения

Бильярд - игра шарами на специальном столе с лузами или без них (карамболь) по особым правилам.

Снукер - вид игры в бильярд с 22 шарами на столе, 15 из которых - красные, и по одному шару жёлтого, зелёного, коричневого, синего, розового, чёрного и белого цветов.

Удар - движение кием в сторону битка с последующим их контактом. Так же под ударом подразумевается касание битка любым другим предметом, в таком случае удар считается нанесённым не по правилам (фол).

Кий - инструмент для игры в бильярд, который представляет собой деревянную палку с наклейкой (наконечником) из специально обработанной кожи со встроенным датчиком касания, предназначенную для нанесения ударов по шарам.

Шар - твёрдый объект шарообразной формы, с датчиком касания.

Луза - каждое из шести отверстий у борта бильярдного стола, в которые во время игры забивают шары.

Цветной шар - шар жёлтого, зелёного, коричневого, синего, розового или чёрного цвета.

Биток - шар, по которому наносится удар кием.

Прицельный шар - шар того цвета, в который игрок планирует направить биток.

Фол - удар, нанесённый не по правилам.

Штраф - начисление очков сопернику в случае фола. Минимальный штраф составляет 4 очка, максимальный - 7 очков.

Свободный шар - игровая ситуация, которая может возникнуть после фола, в случае если игрок, которому перешла очередь удара, не сможет направить биток в любую точку прицельного шара по прямой линии.

Промах - удар, нанесённый по правилам, в результате которого не был забит ни один из шаров.

Видеокамера - устройство для записи видео и последующего его воспроизведения.

Компьютер - вычислительная машина с подключённым к ней монитором, на котором отображается информация о текущем счёте и на котором сохранятся запись с видеокамеры.

Телевизионный стол - стол для игры в бильярд, оснащённый видеокамерой над столом, компьютером, сохраняющим информацию об игре, и монитором, для отображения текущего счёта игры.

Табло - монитор, подключённый к компьютеру через HDMI-кабель. 

Игрок - человек, играющий в бильярд на телевизионном столе.

Сеанс - время работы системы с момента последнего включения.

Мокап - модель какого-либо дизайна, используемая для демонстрации и оценки стиля еще не выпущенного продукта.

Съёмный носитель - переносное устройство хранения информации, временно подключаемое к компьютерам, ноутбукам, планшетам и т.д. через стандартные разъёмы.

ЯП – язык программирования - формальный язык, предназначенный для записи компьютерных программ

БД - база данных - это упорядоченный набор структурированной информации или данных, которые обычно хранятся в электронном виде в компьютерной системе.

ПО - программное обеспечение - это набор инструкций, позволяющий пользователю взаимодействовать с компьютером.

 ## 3 НАЗНАЧЕНИЕ И ЦЕЛИ СОЗДАНИЯ СИСТЕМЫ
 
3.1 Назначение системы 

Система предназначена для контроля за игрой в бильярд и выявления победителя игры.

3.2 Цели создания системы

Цель системы – обеспечить игроков возможностью игры с автоматическим подсчётом очков с помощью видеокамеры, которая будет закреплена над столом и которая должна отслеживать положение шаров на столе и в лузах, а также с помощью датчиков, которые должны осуществлять контроль за соблюдением всех правил игры.

 ## 4 ХАРАКТЕРИСТИКА ОБЪЕКТА АВТОМАТИЗАЦИИ

Система состоит из нескольких объектов: 

1. Видеокамера для записи видео с целью контроля за соблюдением правил игроками, а также для передачи видеокартинки в программный продукт.

2. Компьютер, на котором происходит распознавание видеокартинки, сохранение её в отдельный файл, а также ведение счёта игры.
 
3. Стол для игры в снукер стандартного размера (366 см х 183 см).

4. Монитор (табло) с помощью которого игроки в реальном времени смогут отслеживать текущий результат игры.

 ## 5 ТРЕБОВАНИЯ К СИСТЕМЕ
 
5.1 Требования к системе в целом

Система должна производить корректный подсчёт очков при игре в снукер. Под корректным подсчётом подразумевается соблюдение всех правил игры, описанных в пункте 5.2.

5.1.1 Требования к структуре и функционированию системы

Программный продукт должен иметь возможность выбирать игроков из базы данных или заносить туда новых игроков.

Программный продукт должен включать в себя три режима игры в снукер (с 6, 10 и 15 красными).

Система должна быть разработана с учетом возможности модернизации ПО (добавление других видов игры в бильярд и других языков интерфейса). 

ПО должно быть разработано в виде приложения на компьютер с операционной системой Windows 10.

5.1.2 Требования к надежности

Система должна быть разработана с расчётом на то, что у компьютера не будет доступа в сеть Интернет, а также не будет портов для передачи информации.

5.1.3 Требования к безопасности

Система должна быть защищена от возможной утечки данных в Интернет.

5.1.4 Требования к эргономике и технической эстетике

Данный программный продукт на выходе должен соответствовать всем запросам компании-заказчика, прописанным в требованиях к системе.

Интерфейс программного продукта должен соответствовать мокапам, которые предоставлены компанией-заказчиком, а также должен быть выполнен на русском и английском языках, с возможностью выбора.

5.1.5 Требования к защите информации от несанкционированного доступа

Система не должна запускаться на компьютере у которого есть доступ в сеть Интернет.

5.1.6 Требования по сохранности информации при авариях

Система должна сохранить данные текущего сеанса в случае внезапного отключения питания или в случае завершения работы при попытке сохранения информации на съёмный носитель.

5.2 Требования к функциям (задачам), выполняемым системой

Задачей системы является контроль за игрой и ведение счёта игры.

Игра ведётся между двумя игроками, все удары должны наноситься кием по битку. В роли битка выступает шар белого цвета. Касание остальных шаров кием, элементами одежды или любыми другими предметами не допускается. Касание битка любым предметом кроме наклейки (наконечника) кия не допускается. Игрок, наносящий первый удар в партии определяется случайным образом. Очередь удара переходит от первого игрока ко второму в случае если не был забит один из шаров или если удар был совершён фол. За забитие шаров разного цвета, начисляется разное количество очков: 1 очко за красный шар, 2 - за жёлтый, 3 - за зелёный, 4 - за коричневый, 5 - за синий, 6 - за розовый и 7 очков за чёрный шар. В соответствии с правилами игры в снукер шары нужно забивать в определённой правилами последовательности: для того, чтобы получить возможность забить цветной шар, сначала нужно забить красный шар и наоборот. Цветные шары после забития возвращаются на стол и выставляются на свои позиции в соответствии с правилами игры в том случае, если на столе есть хотя бы один красный шар. Красные шары на стол не возвращаются. Забитие белого шара является ударом, совершенным не по правилам и наказывается штрафом от 4 до 7 очков. Штраф составляет 4 очка, если удар наносился по красному, жёлтому, зелёному или коричневому шару, 5 очков - если по синему, 6 очков - если по розовому и 7 очков - если по чёрному. Белый шар возвращается на стол и выставляется игроком в зону, обозначенную на столе полукругом в виде буквы D. Фолом также считается непопадание битка по прицельному шару. Штрафуется такой удар аналогичным образом: 4 очка, если удар наносился по красному, жёлтому, зелёному или коричневому шару, 5 очков - если по синему, 6 очков - если по розовому и 7 очков - если по чёрному. В случае, если сумма очков в розыгрыше больше, чем разница очков между игроками, игрок, которому перешла очередь удара, может попросить вернуть позицию, которая была на столе до нанесения последнего удара. Если первый игрок совершил фол, то второй игрок имеет возможность передать очередь удара первому игроку. В случае промаха при ударе по цветному шару, игрок теряет эту возможность при следующем ударе. Он должен наносить удар битком по красному шару. В ситуации, когда красных шаров на столе не осталось, прицельным шаром будет считаться самый дешёвый цветной шар - шар, за забитие которого начисляется меньшее количество очков. Партия заканчивается, когда на столе кроме битка нет шаров или когда один из игроков признает своё поражение. В случае, если игроки набрали равное количество очков по окончанию партии, на стол возвращается чёрный шар, и игроки по очереди начинают наносить удары до того момента, пока чёрный шар не окажется в лузе, или один из игроков не совершит фол.

 ## 6 СОСТАВ И СОДЕРЖАНИЕ РАБОТ ПО СОЗДАНИЮ (РАЗВИТИЮ) СИСТЕМЫ

01.10.22 – 01.11.22 – разработка прототипа системы

01.11.22 – 10.11.22 – доработка системы

10.11.22 – 20.11.22 – тестирование

20.11.22 – 01.12.22 -  написание гайда и документации по использованию системы

 ## 7 ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ СИСТЕМЫ

7.1 Виды, состав, объем и методы испытаний системы

Необходимо протестировать возможность запуска системы на компьютере с возможностью выхода в сеть Интернет, проверить возможность сохранить видеофайл на съёмный носитель информации.

Также необходимо проверить корректность распознавания цветов шаров с видеокамеры, работоспособность датчиков. 

Проверить распознавание всех видов ударов, нанесённых не по правилам. Протестировать работу логики системы в режиме реальной игры.

## 8 ИСТОЧНИКИ РАЗРАБОТКИ

ТЗ разрабатывалось на основе потребности рынка.
