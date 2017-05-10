Sueldos - sysarmy - 2017
==============================

Analisis de los datos relevados por sysarmy en enero de 2017

https://sysarmy.com.ar/blog/2017/02/resultados-de-la-encuesta-salarial-enero-2017/

  
Estructura
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`

Instalacion
------------

Crear un virtualenv con python 3 e instalar los requisitos:

     $ virtualenv venv -ppython3
     $ source venv/bin/activate
     (venv) $ pip install -r requirements.txt

Bajar los datos curados

     (venv) $ http -d https://docs.google.com/spreadsheets/d/14lPxK03doSVttCPwLmmafDuRuYRjNO4Bk2a781VK0oo/export\?format\=csv\&id\=14lPxK03doSVttCPwLmmafDuRuYRjNO4Bk2a781VK0oo\&gid\=689338915 -o data/interim/sueldos.csv


Ahora pueden ejecutar `jupyter notebook`.


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
