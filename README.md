# что это
 
это заготовка для директории, где будут лежать решения по чеснокам в формате жупитер ноутбук `.ipynb`.

# зачем 

это надо, если хотите поднять жупитер локально. тут предоставляется веб-интерфейс. 

### что нужно
терминал, питон3 3.10+, пип3

### гайд по установке

1. `python3 -m venv ./venv` - создание виртуальной среды в директории
2. `. venv/bin/activate` - активация виртуальной среды
3. `pip3 install -r requirements.txt` - загрузка базовых библиотек (жупитер, нампай, пандас, матплотлиб)
4. `jupyter notebook` - запуск веб-сервера - откроется браузер.

всё, можно работать. все библиотеки, установленные во время работы с жупитером (например в коде есть `!pip install cowsay`), находятся в виртуальной среде, а не основном питоне.

выключить сервер - `ctrl+C` в терминале 
