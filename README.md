Szkolenie Python 101
====================

Niniejsze materiały to dokumentacja i kody źródłowe do szkolenia z
języka Python realizowanego w ramach projektu [Koduj z Klasą][1]
prowadzonego przez Fundację [Centrum Edukacji Obywatelskiej][2].

Pełna dokumentacja szkolenia znajduje się tutaj:

[bit.ly/kzk-py](http://bit.ly/kzk-py)

Modyfikacje i budowa dokumentacji offline
-----------------------------------------

Materiały szkoleniowe są przygotowywane z pomocą oprogramowania [Sphinx w
wersji 1.3][3]. Ponieważ wersja ta nie jest jeszcze opublikowana należy ją 
zainstalować ze źródeł. W tym celu pobieramy archiwum:

    wget -O sphinx-latest.zip https://bitbucket.org/birkenfeld/sphinx/get/default.zip 
    unzip sphinx-latest.zip

Po rozpakowaniu znajdziemy folder podobny do tego `birkenfeld-sphinx-10d9deb02fd5`,
w nim wykonujemy polecenie instalacji Sphinx'a w naszym środowisku Python.

    $ sudo python setup.py install
    $ sudo pip install sphinx_rtd_theme
        
Po instalacji możemy w folderze dokumentacji możemy uruchomić make:
  
    ~/python101/docs$ make html

  [1]: http://www.ceo.org.pl/koduj
  [2]: http://www.ceo.org.pl/
  [3]: http://sphinx-doc.org/latest/
