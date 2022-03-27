# Simple Flask App

- W projekcie wykorzystamy virtual environment, dla utworzenia hermetycznego środowisko dla aplikacji:

  ```
  # tworzymy hermetyczne środowisko dla bibliotek aplikacji w pythonie:
  $ python -m venv .venv

  # aktywowanie hermetycznego środowiska
  $ source .venv/Scripts/activate
  $ pip install -r requirements.txt

  # zobacz
  $ pip list
  ```

- Uruchamianie applikacji w terminalu pycharm:

  ```
  # jako zwykły program
  $ set FLASK_APP=main.py
  $ python main.py

  ```

- Kontynuując pracę z projektem, aktywowanie hermetycznego środowiska dla aplikacji py:

  ```
  # deaktywacja
  $ deactivate
  ```

  ```
  ...

  # aktywacja 
  $ source .venv/bin/activate
  ```