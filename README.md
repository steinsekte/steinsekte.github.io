# Steinsekte.xyz

Die HTML-Dateien in diesem Verzeichnis sind mit [einem Seitengenerator](https://codekulturbonn.de/webgen/generator.html) erzeugt.

## Installation und Aktualisierung

````
git clone --recursive https://github.com/steinsekte/steinsekte.github.io
cd steinsekte.github.io
python3 -mvenv env
source env/bin/activate
pip install -r webgen/requirements.txt
./webgen/generate.py
````

Einen Webserver zur Entwicklung starten:

````
./webgen/generate.py serve
````
