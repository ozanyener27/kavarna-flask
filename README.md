# kavarna-flask

(R8)
Web kavárny vytvořený ve Flasku. Aplikace představuje kavárnu, její nabídku kávy, čaje a sladkosti, otvírací dobu a kontaktní informace.

(R9)
# postup spuštění 

vytvoření prostředí 

python -m venv .venv

# jak jí spustit

První se musí aktivovat virtuální prostředí:

.venv\Scripts\activate.bat

instalace frameworku Flask

pip install Flask

Spuštění aplikace

flask --app index run --debug

Vytvoření requirements.txt

pip freeze

(R10)

# Struktura projektu

kavarna-flask

    contact
        contact.html
    
    index
        index.html

    templates
        base.html
        index.html
        contact.html
    
    .gitgnore

    base.html

    index.py

    README.md