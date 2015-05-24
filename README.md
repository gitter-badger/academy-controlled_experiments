Chaordic Academy: Controlled Experiments
=========

[![Join the chat at https://gitter.im/chaordic/academy-controlled_experiments](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/chaordic/academy-controlled_experiments?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Coleção de scripts para o Módulo 'Estatística para Experimentos Controlados' da Academia Chaordic

Requirements Ubuntu
----

sudo apt-get -y install python-numpy python-scipy python-matplotlib ipython



Requirements OS X
----
sudo easy_install pip

sudo pip install numpy scipy matplotlib ipython


Requirements Windows
----

It might be easier to download a Scientific Python Distribution


http://www.scipy.org/install.html#scientific-python-distributions

Web Example Requirements
------------------------

The sole requirement for the web example to work is for it to run behind a apache web server so we can parse
the access log.

The log __must__ have the following configuration in order for the `parse-log.py` script to work properly:

```
LogFormat "%h %l %u %t \"%r\" %>s %b %{amazing-ab-group}C %{amazing-userid}C" common
```

This restriction can be easily lifted by refactoring the regular expression presented in that file.
