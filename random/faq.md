Q: **Как смазывать принтер?**
A: Перед смазкой принтера ОБЯЗАТЕЛЬНО уберите магнитную пластину или накройте стол несколькими слоями газеты! Масло точно будет капать вниз и оно может не отмыться со стола. Ремни смазывать не надо! Избегайте попадания смазок на ремни, масло может привести к их повреждению.

Ось X - смыть с валов старую смазку растворителем (спиртом), затем нанести на вал маленькое количество жидкого машинного масло (для швейных машинок, либо что-то похожее на И-20А) и распределить по всей длине. Оптимальнее всего отвести голову в один конец до упора, накапать на оба вала масло прямо перед головой, увести голову в другой конец до упора, снова накапать на оба вала масло прямо перед головой, и провести из конца в конец голову несколько раз чтобы масло распределилось равномерно.
Если где-то по ходу движения головы заедает, можно нанести масло в эту конкретную точку, и так же распределить
Если видите, что после нанесения масла под втулкой остаётся чёрная жижа - это масло смешалось с угольной пылью из втулки, протрите салфеткой и добавьте ещë масло на замену. Ацетон в качестве растворителя использовать можно, но следите, чтобы он ни в коем случае не попал на пластиковые части печатной головки - разъест. Лучше использовать спирт.

Ось Y, Z - рекомендуется заполнить линейный подшипник адгезионной смазкой (смазка для петель автомобильных дверей). Сквозь зазор у сальника впрыснуть в принципе реально. Можно нанести на сам вал и очень долго катать по нему подшипник, пока смазка не покроет все шарики. Также можно использовать смазку из комплектного тюбика.
Для приводных винтов также можно использовать адгезионную смазку, можно использовать литол или другую литиевую смазку, но обратите внимание, что и то, и другое ОЧЕНЬ сильно пачкает руки.

Q: **Можно что-то сделать с кабельной цепью, которая постоянно щёлкает, когда печатная головка оказывается слева?**
A: Есть два вариант - поднять конец цепи со стороны печатной головки (это также упростит снятие её крышки), или заменить цепь полностью на кабельный рукав "змеиная кожа".

Q: **При загрузке пластика он очень плохо заходит в фидер, приходится постоянно отстёгивать трубку, а печати композитами пруток заламывается на входе в фидер, что делать?**
A: Это всё виноват очень крутой изгиб тефлоновой трубки, но по другому её не проложить, т.к. она упирается в крышку принтера. Для исправления ситуации надо сделать так, чтобы крышка была выше. Для этого есть так называемые "райзеры".
Отдельно стоит упомянуть версию райзера, которая позволяет не только распрямить тефлоновую трубку, но и переместить сенсор филамента и кабельный жгут повыше.
В основной группе есть несколько разных райзеров, здесь прикреплю несколько ссылок на разные версии одного, который хорошо себя зарекомендовал:
* Сам райзер: https://www.printables.com/model/545370-creality-k1-k1-max-riser
* Вариация с перемещением сенсора: https://www.printables.com/model/665955-creality-k1-max-riser-improved-filament-path-k1-ad
* Вариация для новых ревизий K1 Max: https://www.printables.com/model/939647-k1-max-riser-corner-piece-for-newer-revisions

В ремиксах у каждой из них вы можете найти нужные вам модификации.

Q: **Дверца открывается только на 90 градусов и очень нехорошо стоит в открытом положении, страшно случайно надавить на неё и разбить**
A: Петли дверцы можно заменить на печатные, открывающиеся на 270 градусов.
Есть несколько вариантов, я настоятельно рекомендую вот этот: https://www.printables.com/model/735524-creality-k1k1ck1-max-door-hinges-geared
Для печати обязательно использовать версию с зазором 0.2, слой 0.2 миллиметра и обязательно переключить движок с Arachne на классический (в противном случае шестерни и оси склеиваются между собой прямо в слайсере).

Q: **Принтер дребезжит при печати, особенно сильно слышно при калибровке шейперов, что делать?**
A: Дребезжит сильнее всего нижняя панель. Её можно полностью снять (Сначала напечатайте рамку для вентилятора от Henlor - https://www.printables.com/model/540070-motherboard-fan-mount-mk2-collection-creality-k1-s/files), а можно проклеить по периметру рамы под ней уплотнительную ленту (можно тканевую антискрипную) и поставить обратно. Если дребезг не ушёл полностью, попробуйте ослабить все винты на боковых панелях и затянуть их все обратно.

Q: **При печати первого слоя заметно, что карта стола неточная - где-то принтер пытается печатать дальше чем надо от стола, как это исправить?**
A: К сожалению, это дефект обработки тензодатчиков стола, который не исправить только программными методами. Потребуется установка тензомода, которому посвящена группа [тензомода.](https://t.me/K1_Tenso_Mod/1619) К сожалению, в отличие от остальных модификаций, перечисленных в данном разделе, для установки этой модификации требуется большое количество навыков, включая пайку, исправление конфигов и работу с Linux, так что это мод "не для всех".

Q: **Что такое хелпер скрипт? Как устанавливать Fluidd?**

*Замечание: Здесь и далее будет выполняться работа с консолью Linux (командной строкой, терминалом). Консоль Linux и консоль Klipper - это две разные консоли, и во избежание путаницы везде будет явно указано, в какой момент с какой из них будет выполняться работа. Описанные здесь действия не являются заменой прошивки и не влияют на её работу. Тем не менее, для выполнения этих действий потребуется получение ROOT-доступа к принтеру (делается через экран). При работе с консолью Linux все надписи будут только на английском языке. В данной инструкции будут представлены переводы и описания для надписей, относящихся к основным действиям, однако, ожидается, что вы можете самостоятельно понять надпись или найти перевод.*

A: Для полноценной работы ряда функций, которые обычно ожидаются от такой продвинутой прошивки как Klipper, на принтерах Creality потребуется установка дополнительного ПО. Однако, следует учитывать, что принтер работает под OS Linux, на которой установка ПО сильно отличается от таковой под Windows, и может являться нетривиальной задачей. Для упрощения операций по установке был написан специальный скрипт-помощник (хелпер-скрипт), который поможет избавить вас от ошибок при выполнении тех или иных действий. Инструкция по установке хелпер-скрипта на английском языке представлена здесь: https://github.com/Guilouz/Creality-Helper-Script-Wiki/blob/main/docs/helper-script/helper-script-installation.md, а в данной инструкции будет представлен адаптированный перевод на русский язык.

В первую очередь, потребуется получить доступ к консоли Linux вашего принтера. Для этого нужно на экране принтера перейти в меню настройки и разблокировать Root-доступ. Без этого получить доступ к консоли невозможно. Разблокировка Root-доступа запустит на принтере SSH-сервер, к которому мы и будем подключаться. Помимо этого, на экране будут отображены логин и пароль для подключения (Это всегда логин root и пароль creality_2023)

Для подключения вам потребуется SSH-клиент на вашем ПК. Под Windows удобным клиентом является программа PuTTY (https://www.putty.org/). Также можно подключиться со смартфона Android, используя клиент Juice SSH из Google Play. Если вы используете Linux или MacOS, вы и так знаете, как установить SSH-клиент и подключиться к принтеру. Для подключения вам нужно будет ввести IP-адрес принтера, а после появления чёрного окна консоли - логин и пароль (описаны выше). Теперь у вас есть доступ к консоли Linux вашего принтера.

Установка хелпер-скрипта выполняется вот такими двумя командами в этой консоли (обратите внимание, что комбинация клавиш Ctrl+V в окне консоли не работает, но можно выполнить вставку нажатием на колёсико мыши, через контекстное меню или комбинацией Shift+Insert):

```
git config --global http.sslVerify false
git clone https://github.com/Guilouz/Creality-Helper-Script.git /usr/data/helper-script
```

Можно скопировать обе команды разом в консоль, после этого нажмите Enter.
Теоретически, первая команда не является обязательной и установка должна пройти нормально без этого, но в последнее время участились жалобы на ошибки при клонировании, которые исправляются первой командой

Если всё пройдёт успешно, хелпер-скрипт установится в папку /usr/data/helper-script на принтере. Запустить его можно командой:

```
sh /usr/data/helper-script/helper.sh
```

После запуска откроется меню, в котором можно выбрать, что требуется сделать.


Список программ, доступных для установки, иногда изменяется, поэтому не следует полагаться на актуальность представленного здесь скриншота.

Ниже будет кратко перечислено, какой из пунктов для чего нужен.

**1 - Moonraker.**

 Это HTTP API для Klipper, позволяющее отправлять файлы на принтер напрямую из слайсеров (Prusa, Orca), добавив в слайсер физический принтер с указанием IP-адреса и порта 7125 (порт указывается через двоеточие).

**2 или 3 - Fluidd и Mainsail** - это веб-интерфейсы для Klipper, позволяющие полноценно управлять принтером через браузер. Обычно при установке Klipper подразумевается наличие одного из них как основного метода управления принтером. Они взаимозаменяемы между собой, можно выбрать любой (в инструкциях ниже будет использоваться Fluidd). Одна из полезнейших вещей, которые предоставляют веб-интерфейсы - доступ к редактированию файлов конфигурации и макросов.

Веб-интерфейсы после установки не знают о наличии в принтере веб-камеры, её нужно добавить в настройках.

**4 - Entware** - это пакетный менеджер для установки программ (здесь уже именно программ). Для пользователей, знакомых с Ubuntu - это аналог apt, запускаемый через команду opkg. Он нужен для некоторых из идущих ниже пунктов, скрипт попросит вас установить Entware при необходимости - просто так его ставить не нужно.

**5** - Функционал для запуска команд Linux из макросов Klipper. Он нужен для работы спикера (Buzzer) и графиков шейперов.

Идущие ниже пункты раздела Improvements - это различные макросы. Самые полезные из них - это KAMP и Improved Shapers.
**6 - KAMP** - один из самых полезных пунктов в списке, если у вас установлена стоковая прошивка: Адаптивное измерение карты стола, позволяет ускорить начальную подготовку к печати. KAMP будет считывать список объектов из файла G-кода и измерять карту стола только вокруг перечисленных там объектов.
Для пользователей тензомода с чистым клиппером, в "полноценном" Klipper не от Creality вместо KAMP есть Adaptive Bed Mesh
Для работы этой функции нужно включить описание названий моделей в слайсере (настройки печати - выходные параметры - Название моделей - "Зависит от типа прошивки")

**7 - Поддержка спикера (Buzzer - команды BEEP)**. Позволит принтеру издавать писк по команде. В последних партиях К1с спикер был не распаян, в них может не заработать.

**8 - ускорение старта печати** небольшое ускорение старта за счет оптимизации макроса. 

**9 - изменение логики кулеров** обьединение датчика температуры с задним вентилятором дает возможность контролировать температуру внутри камеры.  SocFan это изменение логики вентилятора обдува материнской платы. по умолчанию он включается как только становятся активными моторы икс и игрек.  после изменения можно регулировать температуру с дельтой 2 - тоесть когда стоит температура 45 кулер включится при достижении 47 градусов и отключится при достижении 43 градусов. 

однако  где то в глубине китайских скриптов есть макрос который проверяет работает ли этот кулер во время печати и если в этот момент он не работает выдает на экран "ошибка вентилятора материнской платы" что можно смело игнорировать.
 
**10 - Improved Shapers** - Улучшенные макросы для упрощения калибровки шейперов а так же механизм и библиотеки необходимые для создания графиков (Input Shaping).

**12 - Save Z-Offset Macros** - Макросы для настройки и сохранения на ходу значения Z-Offset (настройка зазора сопла от стола). В стоке предполагается, что карта стола строится идеально и настройка этого зазора из интерфейса не предусмотрена. Есть способы обойтись без этого макроса, будут описаны ниже.

Пункт 13 (Screws Tilt Adjust) не работает на принтерах серии K1, он нужен для Ender 3 KE

**16 - Moonraker Timelapse** - Функционал таймлапсов (интервальной съёмки), который будет доступен из Fluidd. Обратите внимание, что хоть он и повторяет функционал таймлапсов от Creality, они не связаны между собой, и настроить таймлапсы Creality (равно как и скачать видеозаписи тех таймлапсов) через Fluidd невозможно. Перед использованием рекомендуется настроить позицию парковки и параметры ретрактов. Также, напоминаю, что сразу после установки веб-интерфейсы не знают о наличии веб-камеры в принтере, и её нужно добавить в настройках.
Не ставьте позицию парковки для таймлапсов в задние углы! В тех координатах (как минимум на модели Max) голова врезается в двигатели и происходит непостоянное смещение слоёв, которое сложно диагностировать. Оптимальные координаты - сзади по центру (150:300 на Max).

**Раздел Remote Access** - это различные варианты удалённого доступа к принтеру. Обратите внимание, что если вы пытаетесь установить GuppyScreen, то он находится в ДРУГОМ разделе, а GuppyFLO из раздела удалённого доступа никак с ним не связан.

Q: **При печати заметна явная недоэкструзия между 2 и 10(5-50) миллиметрами по координате Z, близко к центру стола, при этом ближе к краю и выше по Z такой проблемы нет**
Либо, наблюдается переэкструзия на этой высоте ближе к краю, при этом по центру всë в порядке

Для исправления требуется доступ к файлам конфигурации - см. выше

A: Такая проблема может вызываться плохо откалиброванным коэффициентом PA. Если это так, то она будет проявляться на случайных высотах, с переэкструзией на коротких линиях.
Если же она проявляется только на указанной высоте независимо от модели, это - результат компенсации экструзии алгоритмом Fade, выравнивающего высоту печати согласно карте стола. К сожалению, этот алгоритм работает из предположения, что оси XY не провисают, и карта показывает исключительно неровности стола, а на принтерах серии K1, помимо неровности стола, на карту также влияет провисание валов под весом механики, больше всего заметное в виде бугра по центру оси Y, идущего вдоль оси X. Больше проявляется на принтерах K1 Max, т.к. там валы длиннее и провисают глубже.

Решение проблемы здесь состоит в отключении алгоритма Fade. Однако, перед этим, необходимо убедиться, что углы на карте стола стоят на одной высоте - настолько, насколько возможно.
Для отключения нужно в файле конфигурации `printer.cfg` в секции `[bed_mesh]` найти параметр `fade_end` и установить его значение в 0.