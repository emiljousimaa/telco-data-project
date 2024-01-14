# telco-data-project
Tämä repositorio sisältää Telco-Datatiedeprojektiin liittyvät tiedostot

Ohjeet, miten tiedoston pystyy itse suorittamaan olettaen, että käytössä on VS Code, johon on Python asennettuna.

Avaa komentorivi, navigoi kansioon, jossa tiedostot ovat ja luo uusi virtuaaliympäristö:

cd path/to/your/project
python -m venv venv _(jälkimmäisen 'venv'-tilalla voi olla oma nimi virtuaaliympäristölle)_

Aktivoi virtuaaliympäristö

Windows: .\venv\Scripts\activate
Linux/macOS: source venv/bin/activate

Asenna Jupyter:

pip install jupyter

Asenna tarvittavat laajennukset:

pip install -r requirements.txt
