# America (Gold Cup, Copa America)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for America for national teams. Events include:

-  Gold Cup
-  Copa America


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

# -- Groups

Group A  |  Argentina   Colombia   Bolivia    Costa Rica
Group B  |  Brazil      Paraguay   Venezuela  Ecuador
Group C  |  Uruguay     Chile      Peru       Mexico

# -- Group A

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

TBD


## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!