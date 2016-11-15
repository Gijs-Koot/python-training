Python training

## Doelgroep

Business consultants met een bèta achtergrond en ervaring met het werken met Excel. Als voorbereiding op de training gaan we uit van een basis, die bijvoorbeeld opgedaan kan worden door het volgen van een instapcursus op Code Academy, of het lezen van de eerste vijf hoofdstukken van de officiële Python Tutorial. De training wordt gevolgd met een eigen laptop, en cursisten wordt aangeraden Anaconda te gebruiken om een volledig toegeruste Python installatie te verkrijgen.

## Leerdoelen

Zelfstandig met data kunnen werken. Bijvoorbeeld
* Werken met een interactief notebook om exploratieve dataanalyse te doen.
* Data verzamelen van het web, vanuit databases en het opslaan van data.
* Het maken van grafieken en andere visualisaties.
* Een script schrijven dat CSV- of Excel-bestanden inleest, daar een berekening op doet en de resultaten wegschrijft naar een ander bestand.

Er is gekozen om met Python aan de slag te gaan vanwege het relatief lage instapniveau en de flexi. Daarnaast is Python een populaire taal voor data-analyse, en zijn er, dankzij een actieve community, externe packages beschikbaar van hoge kwaliteit, die allerlei taken eenvoudig maken. In het bijzonder zal de cursus zich richten op de packages Pandas, Numpy, en het gebruik van het interactieve Jupyter notebook.

## Opzet

De training bestaat uit vier dagdelen van ongeveer 4 uur. Deze blokken worden opgedeeld met twee pauzes, en bestaan voor ongeveer twee derde deel uit centrale uitleg en het beantwoorden van vragen door de trainer, en daarbuiten werken cursisten alleen of in tweetallen aan praktische programmeeropdrachten.

### Dagdeel 1: Basisblok

We beginnen de training met een toets van de basis. In kleine opdrachten wordt gekeken naar de flow van python scripts, de ingebouwde datastructuren en het gebruik van het Jupyter-notebook.

* Introductie en installatie
* Het gebruik van Jupyter-notebook
* Datastructuren
* Control flows

### Dagdeel 2: Werken met Python

Na de eerste kennismaking kijken we naar de functies en mogelijkheden die Python een productieve programmeertaal maken.

* Exceptions and errors
* Iterators, generators and comprehensions
* Builtin functions and the stdlib
* Gebruik van externe packages
* Kennismaking met pandas

### Dagdeel 3: Data Science met Python

In het derde deel van de training gaan we aan de slag met de meest gebruikte tools voor het werken met data in Python. Numpy is hierbij het fundament voor het werken met getallen, Pandas bouwt voort op Numpy en biedt functionaliteit die vergelijkbaar is met die van Excel; een tabelstructuur en eenvoudige visualisatietools.

* Werken met numpy en pandas
* Data omvormen en opslaan
* Visualisaties met Pandas en Seaborn

### Dagdeel 4: Werken met data

Het derde dagdeel van de training richt zich op de buitenwereld. We kijken hoe je data kunt verzamelen van andere websites en databases. Daarnaast gaan we dieper in op het installeren en vinden van packages en het samenwerken met anderen met git en GitHub.

* Python scripts, command-line tools en editors
* Werken met requests, json en sqllite
* Introductie van git, GitHub en de Python community

### Dagdeel 5: Het eerste prototype

Op het laatste dagdeel combineren we de vaardigheden tot een werkend prototype. We verzamelen data van een externe bron, voeren een aantal berekeningen uit en presenteren deze in een dashboard op basis van Bokeh.

* Integratie van eerdere onderdelen
* Het gebruik van Bokeh voor interactieve visualisaties
* Python als webserver

## Outline

## 1 Introduction

* What is Python

    * Comparison with other programming languages
        * Why is Python popular
        * MicroPython
    * How to learn Python?
        * Book
        * Reddit
        * Build things
        * How this course is organized
            * Schedule
            * Assignments
            * Contact
    * Differences between 2.7 en 3.5
        * https://eev.ee/blog/2016/07/31/python-faq-why-should-i-use-python-3/
* Running python
    * Oneliners
    * Scripts
    * The notebook
        * Tab completion and getting help
    * Working directory
    * Reading and writing files
        * http://www.grouplens.org/node/73
* Some basics in Python
    * Assignment and printing
    * Program flows
        * For loops
        * If statements
        * Functie statement
            * Return values
            * Side-effects
    * Globals en locals, assignment and scopes
    * Datatypes and operators
        * bool, list, int, float, dict, tuple, set
        * in, or, any,  =, == and is

## 2. Using Python

* Refreshing and practice with the basics
* More advanced Python usage
    * Exceptions
    * Iterators, lists and generators
        * A closer look at the range functie
    * Comprehensions
* Builtin functions
    * enumerate
    * zip
    * sort & sorted
    * zip
    * map
* `stdlib` highlights
    * https://docs.python.org/3/reference/index.html#reference-index
    * https://docs.python.org/3/library/
    * itertools permutations
    * datetime.datetime
        * Converting timestamps in moviedatabase
        * UserID::MovieID::Rating::Timestamp
    * string
    * regex
* Veelvoorkomende third-party packages en hun functies
    * `import`
    * installing packages
    * requests
    * pandas
    * numpy

### Resources

* Reading and watching
    * https://learnxinyminutes.com/docs/python3/
    * http://stanfordpython.com/#lecture
    * https://www.youtube.com/watch?v=VVbJ4jEoOfU

## 3 Pandas and numpy

* Numpy
    * Example
        * Calculating prices
* What is pandas
    * Reading files
    * Series and Dataframes
* `numpy` and `scipy`
    * http://www.scipy-lectures.org/intro/numpy/index.html
    * https://galeascience.wordpress.com/2016/08/10/top-10-pandas-numpy-and-scipy-functions-on-github/
    * Matrices and arrays
    * Pointwise functions
    * Datatypes
    * Adding and substracting, broadcasting rules
    * Indexing
    * `scipy`
        * `stats`
* Pandas in action
    * Case: RDW
        * Column datatypes
        * `to_numeric` & `to_datetime`
        * Adding, subtracting, and mapping series
        * Column datatypes: str en dt
        * Datetime indices
        * Groupby
        * Apply
* Visualization and exploration
    * Boxplots
    * Scatterplots
    * Shared axes
    * Widgets in Jupyter-notebook with interact

## 4 Working with Python

* Scripts and packages
    * If __name__ == “__main__”
    * Creating submodules
    * Logging
* External data
    * HTML, HTTP en .json
    * Using requests to get data
    * Storing data with pandas and sqllite
* Download and read dataset from https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data.
* Epilogue: What is programming?
    * Language vs. interpreters
    * Processes and files
    * Inside the process; objects, pointers and garbage collection

## Topics

* The Python ecosystem
    * History
    * Prolific users
    * Scipy and related communities
    * PyCon, Scipy, FOSDEM
* Git
    * Werken met git
        * clone, commit, push en pull
    * Github
* Interactive visualizations with Bokeh

## Exercises

* Automatic wordcloud creation
