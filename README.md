# America (Gold Cup, Copa América)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for national teams in South America
and North/Central America & Caribbean Islands. Events include:

-  Gold Cup / Copa de Oro
-  Copa América


Example:

~~~
### National Teams

arg, Argentina,   ARG, ar
bra, Brazil,      BRA, br
...
~~~

~~~
##################################
# Copa América 2011 Argentina

# Groups

Group A  |  Argentina   Colombia   Bolivia    Costa Rica
Group B  |  Brazil      Paraguay   Venezuela  Ecuador
Group C  |  Uruguay     Chile      Peru       Mexico

# Group A

Matchday 1 / Group A

2011-07-01 21:45   Argentina  -  Bolivia    1-1

Matchday 2 / Group A

2011-07-02 15:30  Colombia  -  Costa Rica    1-0
...
~~~


## Build Your Own `football.db` Copy

To build your own `football.db` copy from the plain text fixtures
use the sportdb command line tool. Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `america` fixtures

    $ git clone git://github.com/openfootball/america.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./america --worldinclude ./world.db

That's it. For more
see the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby).



## Links

### Gold Cup / Copa de Oro

Official Site - [www.goldcup.org](http://www.goldcup.org) or [www.copaoro.org](http://www.copaoro.org)

- every two years 
- 12 teams, 25 matches
    - North American zone   / 3 teams
    - Central American zone / 5 teams
    - Caribbean zone        / 4 teams


Gold Cup / Copa de Oro 2013

- United States, July 7-28, 2013
- 12th edition

Gold Cup / Copa de Oro 2011

- United States, June 5-25, 2011


#### Wikipedia

- [2011_CONCACAF_Gold_Cup](http://en.wikipedia.org/wiki/2011_CONCACAF_Gold_Cup)
- [2013_CONCACAF_Gold_Cup](http://en.wikipedia.org/wiki/2013_CONCACAF_Gold_Cup)


### Copa América

- 12 Teams
    - South America (10 teams)
    - Invitees (2 teams) e.g. Japan, Mexico, Costa Rica, etc.

Copa América 2015

- Chile, July 2015

Copa América 2011

- Argentina, July 1 to July 24, 2011



## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!