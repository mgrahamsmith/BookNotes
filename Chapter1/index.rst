Chapter 1
=========

Prerequisites
-------------

Installation Notes and Links

- Firefox (already installed)
  
- Geckodriver_

  - Download .tar
  - Copy to /usr/local/bin
  - Extract: `tar -xf`
  - delete .tar file
  - executable now on path with `/usr/local/bin`

- Virtualenv_ setup

  - Install python3.8-venv package
    `apt-get install python3-venv`
  - Tutorial_ notes
  - cd <folder-name>
  - python3.8 -m venv virtualenv
  - Activate virtualenv: `source virtualenv/bin/activate`
  - Deactivate: `deactivate`

- Django_ and Selenium_ Tutorial_ steps

  ..  code-block:: bash
		     
    (virtualenv) $ pip install "django<1.12" "selenium<4"
    Collecting django==1.11.16
      Using cached Django-1.11.16-py2.py3-none-any.whl
    Collecting selenium
      Using cached selenium-3.14.1-py2.py3-none-any.whl
    Installing collected packages: django, selenium
    Successfully installed django-1.11.16 selenium-3.14.1

  
    
Quotes
------
    Do nothing until you have a test!

.. _Geckodriver: https://github.com/mozilla/geckodriver/releases
.. _Tutorial: https://www.obeythetestinggoat.com/book/pre-requisite-installations.html
.. _virtualenv: 
