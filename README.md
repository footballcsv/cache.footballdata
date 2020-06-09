# Mirror - Football-Data

A mirror for the football leagues from 25 seasons back to 1993/94 from Joseph Buchdahl's Football Data website (football-data.co.uk) up and running since 2001 (and updated twice a week).


## What's Joseph Buchdahl's Football Data?

[Joseph Buchdahl](https://twitter.com/12Xpert) has been publishing football data
at the [`football-data.co.uk`](https://www.football-data.co.uk/data.php) website
in the world's most popular tabular data interchange format in text, that is,
comma-separated value (.csv) records for (bulk) download (and offline usage) since 2001 (!).

The main top football leagues include:

- England (`E0`, `E1`, `E2`, `E3` & `EC`) - Premiership & Divs 1, 2, 3 & Conference
- Scotland  (`SC0`, `SC1`, `SC2` & `SC3`) - Premiership & Divs 1, 2 & 3
- Germany (`D1` & `D2`) - Bundesligas 1 & 2
- Italy (`I1` & `I2`) - Serie A & B
- Spain (`SP1` & `SP2`) - La Liga (Primera & Segunda)
- France (`F1` & `F2`) -  Le Championnat & Division 2
- Netherlands (`N1`) - Eredivisie
- Belgium (`B1`) - Pro League
- Portugal (`P1`) - Liga I
- Turkey (`T1`) - Ligi 1
- Greece (`G1`) -  Ethniki Katigoria

And the extra leagues include:

- Argentina (`ARG`) - Primera Division
- Austria (`AUT`) -  Bundesliga
- Brazil (`BRA`) -  Serie A
- China (`CHN`) - Super League
- Denmark (`DNK`) -  Superliga
- Finland (`FIN`) -  Veikkausliiga
- Ireland (`IRL`) - Premier Division
- Japan (`JPN`) -  J-League
- Mexico (`MEX`) -  Liga MX
- Norway (`NOR`) -  Eliteserien
- Poland (`POL`)-  Ekstraklasa
- Romania (`ROU`) -  Liga 1
- Russia (`RUS`) - Premier League
- Sweden (`SWE`) -   Allsvenskan
- Switzerland (`SWZ`) -  Super League
- USA (`USA`) -  Major League Soccer (MLS)


The top football leagues include 25 seasons back to 1993/94
and get at least updated twice weekly
(Sunday nights and Wednesday nights).




## Why Mirror the Datasets?

### What's unchanged / mirrored?

The club names get copied as is incl. typos.


### What's changed?

The league codes (`E0`, `E1`, `D1`, `D2`, ...) get changed to
the football.db "standard" using two letter ISO codes for countries
and if now ISO code exists (e.g. for England, Scotland) than the three letter FIFA codes for countries (e.g. ENG, SCO) get used.

The original football datasets come in two flavors / formats.
The main leagues use season-by-season datafiles.
For example, `E0.csv`, `E1.csv`, `E2.csv`, `E3.csv` & `E4.csv` in the `2019-20`
season directory hold the matches for the English Premiership & Divs 1, 2, 3 & Conference;
`D1.csv` & `D2.csv` for the Bundesligas 1 & 2 and so on.

The extra leagues use an all-seasons-in-one datafile.
For example, `ARG.csv`
holds all seasons of the Argentinian Primera Division;
`AUT.csv` for the Austrian Bundesliga and so on.

The datasets here use the football.csv "standard", that is, one datafile
per season and league. The league code becomes the file name and the season the
directory name e.g. `2019-20/eng.1.csv` or `2019-20/at.1.csv`


Note: The datasets character encoding gets converted from
[Windows-1252 (8-bit)](https://en.wikipedia.org/wiki/Windows-1252) to UTF-8 (Unicode multi-byte).





## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!

