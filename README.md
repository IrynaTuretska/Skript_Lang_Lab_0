# Skript_Lang_Lab_0

Вступна практична робота #0

Изначально JavaScript был создан, чтобы «сделать веб-страницы живыми».

Программы на этом языке называются скриптами. Они могут встраиваться в HTML и выполняться автоматически при загрузке веб-страницы.

Скрипты распространяются и выполняются, как простой текст. Им не нужна специальная подготовка или компиляция для запуска.

Как работают движки?
Движки сложны. Но основы понять легко.

Движок (встроенный, если это браузер) читает («парсит») текст скрипта.
Затем он преобразует («компилирует») скрипт в машинный язык.
После этого машинный код запускается и работает достаточно быстро.
Движок применяет оптимизации на каждом этапе. Он даже просматривает скомпилированный скрипт во время его работы, анализируя проходящие через него данные, и применяет оптимизации к машинному коду, полагаясь на полученные знания. В результате скрипты работают очень быстро.

Итого
JavaScript изначально создавался только для браузера, но сейчас используется на многих других платформах.
Сегодня JavaScript занимает уникальную позицию в качестве самого распространённого языка для браузера, обладающего полной интеграцией с HTML/CSS.
Многие языки могут быть «транспилированы» в JavaScript для предоставления дополнительных функций. Рекомендуется хотя бы кратко рассмотреть их после освоения JavaScript.

IDE
Термином IDE (Integrated Development Environment, «интегрированная среда разработки») называют мощные редакторы с множеством функций, которые работают в рамках целого проекта. Как видно из названия, это не просто редактор, а нечто большее.

IDE загружает проект (который может состоять из множества файлов), позволяет переключаться между файлами, предлагает автодополнение по коду всего проекта (а не только открытого файла), также она интегрирована с системой контроля версий (например, такой как git), средой для тестирования и другими инструментами на уровне всего проекта.

Если вы ещё не выбрали себе IDE, присмотритесь к этим:

Visual Studio Code (бесплатно).
WebStorm (платно).

Инструменты разработчика позволяют нам смотреть ошибки, выполнять команды, проверять значение переменных и ещё много всего полезного.
В большинстве браузеров, работающих под Windows, инструменты разработчика можно открыть, нажав F12. В Chrome для Mac используйте комбинацию Cmd+Opt+J, Safari: Cmd+Opt+C (необходимо предварительное включение «Меню разработчика»).

Мы можем объявить переменные для хранения данных с помощью ключевых слов var, let или const.

let – это современный способ объявления.
var – это устаревший способ объявления. Обычно мы вообще не используем его, но мы рассмотрим тонкие отличия от let в главе Устаревшее ключевое слово "var" на случай, если это всё-таки вам понадобится.
const – похоже на let, но значение переменной не может изменяться.
Переменные должны быть названы таким образом, чтобы мы могли легко понять, что у них внутри.

Функции – это значения. Они могут быть присвоены, скопированы или объявлены в другом месте кода.
Если функция объявлена как отдельная инструкция в основном потоке кода, то это Function Declaration.
Если функция была создана как часть выражения, то считается, что эта функция объявлена при помощи Function Expression.
Function Declaration обрабатываются перед выполнением блока кода. Они видны во всём блоке.
Функции, объявленные при помощи Function Expression, создаются, только когда поток выполнения достигает их.
