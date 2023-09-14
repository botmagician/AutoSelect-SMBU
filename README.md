# AutoSelect-SMBU

Всех приветствую! Эта программа одним из первых запишет вас на курс с сайта [elective.smbu.edu.cn](https://elective.smbu.edu.cn).
#### Ссылки:

1. [Требования](#Требования)
2. [Установка](#Установка)
3. [Пользование](#Пользование)
4. [Правила и условия](#Правила и условия)


# Требования:

- python 3.6+
- Любая среда разработка (IDE) поддерживающая python

# Установка:

#### Скачиваем репозиторий

Напишите в командной строке

```
git clone https://github.com/MuxaWinLol/AutoSelect-SMBU
```

Или напрямую скачайте и распакуйте zip-архив с [гитхаб](https://github.com/MuxaWinLol/AutoSelect-SMBU/archive/refs/heads/master.zip)


#### Скачиваем необходимые библиотеки.


```
cd AutoSelect-SMBU
```

```
pip install -r requirements.txt
```

### 🎉Теперь всё готово к использованию!🎉




# Пользование

Все шаги выполняем ***ЗАРАНЕЕ!*** 

Открываем файл `main.py` и запускаем его.

В консоли заполняем время начала выбора курса в указанном формате. 

Затем переходим на сайт [elective.smbu.edu.cn](https://elective.smbu.edu.cn)
Входим в личный кабинет.
В личном кабинете нажимаем на кнопку `выбор курсов`.

_Открываем консоль разработчика_ (обычно `F12` или `Ctrl + Shift + C`)
Сверху выбираем вкладку `Network` или `сеть`:

![[Pasted image 20230914223202.png]]

Далее, не закрывая панели, нажимаем на нужном курсе кнопку `Выбрать` и после во всплывающем окне `Ок`:

![[Pasted image 20230914223644.png]]

Справа в панели разработчика должен был появиться запрос `add` — нажимаем на него и переходим в раздел `Headers` или `Заголовки`:

![[Pasted image 20230914224620.png]]

Отсюда копируем и вставляем в программу значения, соответствующие полям
- `Authorization` (номер 1)
- `Batchid` (номер 2) 
- `Cookie` (номер 3)

Затем переходим в раздел `Payload` или `Полезные данные`:

![[Pasted image 20230914225400.png]]

Вписываем в программу значения, соответствующие полям
- `clazzType`
- `clazzId`
- `secretVal`

### Если вы всё проделали правильно, дальше программа сработает сама!

> **Важно!** Не закрывайте вкладку с сайтом в браузере (консоль разработчика — можно, — для этого нажмите на крестик справа вверху).

# Правила и условия

---

**Правила:**

- Не сничим.
- Не распространяем.
- Получаем удовольствие!

## Если хотите создать форк

  🤦‍♂️Милости просим! XD

---
