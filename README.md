# soccerstats

`soccer_stats` is an R package which implements common statistics observed in
analyses of soccer players, teams, and organizations.

The package is explicitly designed to support learning about soccer data
analysis and includes references to external sources, careful code documenation,
and example data and vignettes.

### WORK IN PROGRESS

This package is a side-project of a very busy student. It will take a while to 
get built. If you are interested in the work, feel free to let me know 
(encouragement feels nice!) but please be patient. I make no guarantees as to
when the package will be usable.

**Currently Reviewing**

* http://11tegen11.net/
* http://www.soccerbythenumbers.com/
* https://jameswgrayson.wordpress.com/
* http://statsbomb.com/

### Target Statistics

#### Team

* Total Shots Rate (TSR):
    http://11tegen11.net/2012/12/01/introducing-the-relative-shots-rate/
* Relative Shots Rate (RSR): Same resource.
* Shooting Percentage, Save Percentage, PDO:
    http://11tegen11.net/2012/05/04/winning-matches-is-it-luck-or-skill/

#### Player

* Shots per 90, Shots per goal, Percent on target, Expected Goals (xG), 
    Difference from expected goals (dG), Shooting Goals Added (SGA), Expected 
    goals given on-target-or-not (xGOT), Keep Goals Added (KGA), Shot map:
    http://www.optasportspro.com/en/about/optapro-blog/posts/2012/blog-assessing-the-performance-of-premier-league-goalscorers.aspx
* Types of attempts and types of shot:
    http://11tegen11.net/2011/07/13/a-chance-is-a-chance-is-a-chance/


### Target Data

* Will primarily aim to draw what I need from this awesome-looking API:
    http://api.football-data.org/index

### Other Resources

* Pre-calculated ELO ratings (for comparing against those produced in the 
    package): http://clubelo.com/
* General listing of useful soccer data resources (several of which will be
    drawn on here): http://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/
* 11tegen11 reference list: http://11tegen11.net/landmark-articles/