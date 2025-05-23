# Работа на сервере
## Рыбалко Тимофей Александрович
## г. Москва

---

## 2.1 Знакомство с сервером
1. Суть задания: Определение возможностей использования удаленного сервера
Конкретный вопрос: Для каких задач подходит удаленный сервер?
Правильный ответ: Хранение больших объемов данных; Выполнение сложных вычислений; Хранение конфиденциальных данных; Хранение общедоступных данных
Вывод: Удаленный сервер универсален для хранения и обработки любых данных.
  ![Решение](screenshot_1.png)

2.Суть задания: Безопасность передачи SSH-ключей
Конкретный вопрос: Какой ключ безопасно пересылать?
Правильный ответ: id_rsa.pub
Вывод: Публичный ключ безопасен для передачи.
  ![Решение](screenshot_2.png)

---

## 2.2 Обмен файлами
1.Суть задания: Копирование папки с содержимым на сервер
Конкретный вопрос: Как скопировать папку рекурсивно?
Правильный ответ: scp -r stepic username@server:~/
Вывод: Флаг -r обеспечивает рекурсивное копирование.
  ![Решение](screenshot_3.png)

2.Суть задания: Устранение проблем с установкой пакета через apt-get
Конкретный вопрос: Проверка места на диске; sudo apt-get update; sudo apt-get upgrade; Проверка интернет соединения
Правильный ответ: sudo apt-get update; Проверка интернет соединения
Вывод: Обновление репозиториев и интернет обязательны для установки
  ![Решение](screenshot_4.png)

---

## 2.3. Запуск приложений
1. Суть задания: Способы получения справки о программе
Конкретный вопрос: program ?!; man program; program --help; help program
Правильный ответ: man program; program --help; help program
Вывод: Основные способы - man и --help.
  ![Решение](screenshot_5.png)

2. Суть задания: Определение поддерживаемых форматов входных данных FastQC
Конкретный вопрос: seq; fastqc; bam_mapped; sam_mapped; fasta
Правильный ответ: fastq; bam; sam
Вывод: FastQC поддерживает bam и sam форматы.
  ![Решение](screenshot_6.png)

---

## 2.4 Контроль запускаемых программ
1. Суть задания: Определение состояния фоновых процессов после манипуляций
Конкретный вопрос: Какие программы будут видны в jobs после последовательности команд?
Правильный ответ: Только о program2,3
Вывод: program1 завершен, program2 приостановлен, program3 активен.
  ![Решение](screenshot_7.png)

2. Суть задания: Сравнение идентификаторов процессов в jobs, top и ps
Конкретный вопрос: Одинаковы ли ID процессов в этих утилитах?
Правильный ответ: У ps и top одинаковые.
Вывод: Каждая утилита использует свой тип идентификатора, кроме ps и top.
  ![Решение](screenshot_8.png)

---

## 2.5 Многопоточные приложения
1. Суть задания: Потребление CPU остановленным многопоточным приложением
Конкретный вопрос: Сколько % CPU использует приложение после Ctrl+Z?
Правильный ответ: 0% CPU
Вывод: Остановленные процессы не потребляют процессорное время.
  ![Решение](screenshot_9.png)

2. Суть задания: Потребление памяти остановленным процессом
Конкретный вопрос: Сколько памяти занимает приложение после Ctrl+Z?
Правильный ответ: Столько, сколько оно потребляло в момент остановки
Вывод: Остановка не освобождает выделенную память.
  ![Решение](screenshot_10.png)

---

## 2.6 Менеджер терминала tmux
1. Суть задания: Поведение приостановленного процесса при вызове fg в другой вкладке терминала
Конкретный вопрос: Что произойдет при вызове fg в другой вкладке?
Правильный ответ: Терминал сообщит, что нет процесса для запуска в fg
Вывод: У каждой вкладки терминала свой набор процессов.
  ![Решение](screenshot_11.png)

2. Суть задания: Поведение tmux при выполнении exit в последней вкладке
Конкретный вопрос: Что произойдет при exit в последней вкладке tmux?
Правильный ответ: tmux завершит работу
Вывод: Закрытие последней вкладки завершает tmux-сессию.
  ![Решение](screenshot_12.png)

# Работа на сервере
## Смольняков Данил Евгеньевич
## г. Москва

---

## 2.1 Знакомство с сервером
1. Суть задания: Определение возможностей использования удаленного сервера
Конкретный вопрос: Для каких задач подходит удаленный сервер?
Правильный ответ: Хранение больших объемов данных; Выполнение сложных вычислений; Хранение конфиденциальных данных; Хранение общедоступных данных
Вывод: Удаленный сервер универсален для хранения и обработки любых данных.
  ![Решение](screenshot_1.png)

2.Суть задания: Безопасность передачи SSH-ключей
Конкретный вопрос: Какой ключ безопасно пересылать?
Правильный ответ: id_rsa.pub
Вывод: Публичный ключ безопасен для передачи.
  ![Решение](screenshot_2.png)

---

## 2.2 Обмен файлами
1.Суть задания: Копирование папки с содержимым на сервер
Конкретный вопрос: Как скопировать папку рекурсивно?
Правильный ответ: scp -r stepic username@server:~/
Вывод: Флаг -r обеспечивает рекурсивное копирование.
  ![Решение](screenshot_3.png)

2.Суть задания: Устранение проблем с установкой пакета через apt-get
Конкретный вопрос: Проверка места на диске; sudo apt-get update; sudo apt-get upgrade; Проверка интернет соединения
Правильный ответ: sudo apt-get update; Проверка интернет соединения
Вывод: Обновление репозиториев и интернет обязательны для установки
  ![Решение](screenshot_4.png)

---

## 2.3. Запуск приложений
1. Суть задания: Способы получения справки о программе
Конкретный вопрос: program ?!; man program; program --help; help program
Правильный ответ: man program; program --help; help program
Вывод: Основные способы - man и --help.
  ![Решение](screenshot_5.png)

2. Суть задания: Определение поддерживаемых форматов входных данных FastQC
Конкретный вопрос: seq; fastqc; bam_mapped; sam_mapped; fasta
Правильный ответ: fastq; bam; sam
Вывод: FastQC поддерживает bam и sam форматы.
  ![Решение](screenshot_6.png)

---

## 2.4 Контроль запускаемых программ
1. Суть задания: Определение состояния фоновых процессов после манипуляций
Конкретный вопрос: Какие программы будут видны в jobs после последовательности команд?
Правильный ответ: Только о program2,3
Вывод: program1 завершен, program2 приостановлен, program3 активен.
  ![Решение](screenshot_7.png)

2. Суть задания: Сравнение идентификаторов процессов в jobs, top и ps
Конкретный вопрос: Одинаковы ли ID процессов в этих утилитах?
Правильный ответ: У ps и top одинаковые.
Вывод: Каждая утилита использует свой тип идентификатора, кроме ps и top.
  ![Решение](screenshot_8.png)

---

## 2.5 Многопоточные приложения
1. Суть задания: Потребление CPU остановленным многопоточным приложением
Конкретный вопрос: Сколько % CPU использует приложение после Ctrl+Z?
Правильный ответ: 0% CPU
Вывод: Остановленные процессы не потребляют процессорное время.
  ![Решение](screenshot_9.png)

2. Суть задания: Потребление памяти остановленным процессом
Конкретный вопрос: Сколько памяти занимает приложение после Ctrl+Z?
Правильный ответ: Столько, сколько оно потребляло в момент остановки
Вывод: Остановка не освобождает выделенную память.
  ![Решение](screenshot_10.png)

---

## 2.6 Менеджер терминала tmux
1. Суть задания: Поведение приостановленного процесса при вызове fg в другой вкладке терминала
Конкретный вопрос: Что произойдет при вызове fg в другой вкладке?
Правильный ответ: Терминал сообщит, что нет процесса для запуска в fg
Вывод: У каждой вкладки терминала свой набор процессов.
  ![Решение](screenshot_11.png)

2. Суть задания: Поведение tmux при выполнении exit в последней вкладке
Конкретный вопрос: Что произойдет при exit в последней вкладке tmux?
Правильный ответ: tmux завершит работу
Вывод: Закрытие последней вкладки завершает tmux-сессию.
  ![Решение](screenshot_12.png)

