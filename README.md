[Track it like Beckham-Project](https://www.uni-bamberg.de/mobi/leistungen/studium/archiv/project-2014-track-it-like-beckham/)
============

The project was conducted in the holidays of the summer semester 2014 at the University of Bamberg.
The tasks were taken partly from [ACM DEBS 2013](http://www.orgs.ttu.edu/debs2013/index.php?goto=cfchallengedetails) and must been solved with [Odysseus](http://www.uni-oldenburg.de/informatik/is/forschung/projekte/odysseus/). The match source file must be downloaded from the DEBS page and then the file path must be set as `DATAFILENAME` in the [source file](/src/TILB/source.qry).

### Setup

Follow the instructions from the [Odysseus Doku](http://odysseus.offis.uni-oldenburg.de:8090/display/ODYSSEUS/How+to+install+Odysseus) and import this project.
Afterwards you can load and execute the developed queries. 

### Repository Structure

    |- Project folder
    |- source.qry: defines all sources which can be used
    |- *.qry: query files which solve specific problems
    |- *.prt: dashboard parts using [self developed visualizers](https://github.com/philippneugebauer/odysseus_dashboard_plugin)
    |-- data: includes all the data files except the 4GB soccergame data file

### License

[MIT](/LICENSE)

### Developer

Philipp Neugebauer
