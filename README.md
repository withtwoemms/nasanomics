# nasa-economics
code challenge for integrating data from two different APIs

---
### Instructions:
* hit [data.nasa.gov](https://data.nasa.gov/view/ak9y-cwf9) and [beta.data.worldbank.org](http://data.worldbank.org/indicator/IP.JRN.ARTC.SC/countries?display=default)
    - *do not* download any datasets
* only look at data from 2008 - 2010
* use the data to answer the questions
    - use other APIs if necessary
    - answers should be in the following format:

> Q: How many records are in the dataset? 
> A: 45,716

* ignore irrelevant data
* use Python 3 and any libraries you feel are of use

---
### Usage:
* clone the repo
* run `make venv` (to create the virtualenv)
* activate the virtual env (e.g. `source venv/bin/activate`)
* run `make install`
* run `make dev-server`
    - be sure you have a redis instance up and running (e.g. `$ redis-server`)
    - `make shell` to sandbox ideas
    - travelling to the `/questions` endpoint will show all questions
    - travelling to the `/answers/<year>` will show pertinent data
