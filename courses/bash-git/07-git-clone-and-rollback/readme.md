# Клонирование и версии

### git clone

Для того чтобы скачать код с репозитория, нужно ввести команду
```sh
git clone <url>
```
где url это ссылка на твой проект, выглядит он примерно так:  

```sh
git clone https://github.com/sakenism/test.git
```

Очевидно, перед скачиванием git попросит твои данные: _username, password_
    
___

### Откат к старой версии
    
Если по какой-то причине тебе нужно откатиться на одну из прошлых версий своего проекта, нужно сделать следующие операции:

```sh
git log
```

Выйдет список коммитов — здесь можно узнать хэш (номер) старого коммита. Выглядит он примерно так

```
12345678901234567890123456789012345678ab
```

```sh
git checkout <hash>
```
вместо `<hash>` вставляешь хэш коммита который тебе нужен.

Поздравляю, теперь ты видишь свой старый код!🥳

<iframe width="100%" height="315" src="https://www.youtube.com/embed/RIYrfkZjWmA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

