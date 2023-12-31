# Описание рисков
## Бизнесс-риски
1. Приложение "не зайдет". Как бы великолепно не звучала идея, не исключнено, что это будет просто "работой в стол" с большими финансовыми потерями. Комплексный риск, состоящий из:
    1. Неверная целевая аудитория. Если реклама расчитана на сильных, накачанных мужиков и женщин, а устройствами пользуются "утонченные" натуры нетрадиционных ориентаций - она не окупится и приложение не взлетит. 
    2. Ошибки в дизайне. Иметь ярко-розовый миленький дизайн с понями в приложении, расчитаном на сильных брутальных спортсменов - просто не является допустимым в этой среде.
    3. Недостаточная реклама. Да, элементы соц.сети позволят приложению рекламировать само себя. Но на начальных этапах до набора определенной критической массы - о приложении не узнают и т.д.
2. Юридические ограничения в конкретных станах. Это приложение с серьезным набором персональных данных, потому вполне верятны наличия требований по их расположению. Что самое грустное - в любой момент эти правила могут поменяться.
3. Наличие конкурентов. Конкуренты у нас по определению есть и, если не зайдет наша фишка, молодое неизвестное приложение свою аудиторию отбить не сможет. Так же интересные фишки очень быстро могут быть скопированы, если юридически это всё не защитить
4. Интеллектуальная собственность. Есть риск зайти на "чужую территорию", реализуя фичи, защищенные патентами на интеллектуальное право.
5. Санкционная политика отдельных государств, регулирование бизнеса "политическими" методами из-за "политических" причин. 
6. Существенное превышение финансовых затрат на разработку и поддержание сервиса на приносимой пользой. Комплексный риск:
    1. Слишком мощная инфраструктура, требующая огромных финансовых затрат на поддержку при почти отсутствующей загрузке. Например, отдлельный кластер в стране, где всего полтора пользователя знают, что такое "кроссовки".
    2. Выбор технологий, требущий множество редких и дорогих специалистов, когда эти технологии не особо-то и нужны и т.д.

## Технические риски
### Серверная часть
1. Ошибки в расчетах ресурсов серверов. Выделить мало - приложение будет работать медленно. Много - это будет дорого.
2. Отдача слишком многих функций на сервер
    1. Он не резиновй и мощность его ограничена.
    2. Пользователь может бегать там, где нет интернетов и приложение не должно превращаться в "кирпич"
    3. Общение с сервером - время, зависящее от интернета пользователя, возможны существенные проседания по скорости загрузки и т.д.
3. Наличие "узких мест" инфраструктуры. Если всего один сервер - нужно хотя бы элементарный балансировщик и несколько экземпляров сервиса.
4. Наличие "критических узлов", смерть которых сделает всю систему нерабочей.
5. Недостаточное бекапирование. Это пользовательские данные и потеря их данных - серьезный репутационный удар.
6. Ошибки с распределением БД и сервисов. Очень хочется всё иметь в одном месте - но это не безопасно (мало ли пожар и капец серверам). С другой строны, все в разных частях земного шара - и общение между сервисами превратится в долгоиграющий ад.
### Прилложение
1. Множество версий ОС. Множество разрешений экранов. Множество используемого оборудования. Где-то, да что-то работать будет не так. 
2. Несовместимость встроенных в устройство протоколов, сертификатов, оборудования, используемых портов с используемыми в Приложении и т.д.

---
<p align="right"><a href="06_wayToBuild.md">[Далее]</p>