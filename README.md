# Harvard Droid: "Digital Repository of Open Interesting Data"

![Droid logo](droid-logo.png)

**Building Harvard University's first open data portal.**

## About Droid

We (Harvard's CTO, Harvard's Chief Digital Officer, the former Deputy CTO of the United States, the Berkman Center, and Harvard College students, among others) are creating an open platform where Harvard students and researchers can discover data about the University such as course catalogs, energy consumption, and library holdings.

We're going to find, store, and publish exciting data sets about Harvard and build a technical platform that'll help visitors find and use this data at a click. We're looking for data lovers and hackers from around the University -- especially undergraduates -- to make this a reality.

## Past Work

There has been a large movement toward open data in government (e.g. [Data.gov](http://data.gov)) and in other universities (e.g. [Yale's Open Data Access Project](http://yoda.yale.edu/)). The Harvard administration has been working on an open data portal of our own for nearly two years, and by finally bringing together all the necessary people (faculty leaders and undergraduate builders and researchers) we are finally making this a reality.

## Leadership

* Jim Waldo, CTO, Harvard University
* Perry Hewitt, Chief Digital Officer, Harvard University
* Nick Sinai, former United States Deputy CTO

## Getting Started

**To get involved, join the discussion at [Issues](https://github.com/Harvard-Open-Data-Project/droid/issues) or learn more at the [Wiki](https://github.com/Harvard-Open-Data-Project/droid/wiki).**

Harvard students: interested in working with us? **[Sign up for the team!](https://groups.google.com/forum/#!forum/harvardopendata)**

Grab a copy of the repository with:

```
$ git clone https://github.com/Harvard-Open-Data-Project/droid.git
```

## Next Steps

* Finding interesting, accessible data sets around harvard.edu
* Working out open licensing for the data
* Determining which technology to use to store and catalog the data
* Building a frontend and backend for the data portal

## Possible Data Sets

* Q scores
* Course catalog
* Shuttle tracker
* Dining hall menus
* Demographics from the FAS Registrar
* Endowment
* Library search
* Harvard art museum collections
* Building plans for Allston
* Authentication
* [DASH research repository](http://dash.harvard.edu/)

## Development

### Getting started

To run the app locally, you'll first need to set up your development environment. 

Begin by [installing Node.js](https://nodejs.org/).

Clone this repository and `cd` into that folder.

Install the Node.js modules required to build the app:

```
npm install -g gulp bower
```

Install the other modules this app requires:

```
npm install
bower install
```

Once you're all set up, start your local server:

```
gulp
```

Then open up [localhost:3000](http://localhost:3000/) in your browser.

### Contributing

Feel free to make a pull request with new features or bug fixes. Fork this repo, make some changes, and submit your pull request.


