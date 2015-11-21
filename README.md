# AllStat

This is a database, containing data from Swedish top flight football league, Allsvenskan, from its inaugural season, 1924/25, up until today. 

The database contains the following data points:

* leaguename – the name of the league, and the season it was played.
* matchdate – the date the fixture was played.
* matchday – the round the fixture was played in. In the first years the fixtures weren't as organized, as they are today. This leads to it being a puzzle which games belong to what round. You will find the same team playing more than one game in a single round. If you can lay this puzzle better than I, you are most welcome to make corrections.
* hometeam – the team who were the hosts, although games played at a neutral venue are not indicated.
* awayteam – the visiting team.
* homescore – the number of goals scored by the home team.
* awayscore – the number of goals scored by the visiting team.
* attendance – official spectators, as reported at the time. This reporting has changed throughout the years; first counting only paid entrance fees, not including free tickets etc, now indicating actual number of people watching the game.

**Note:** There are a couple of anomalies, you should be aware of, if you want to correctly generate league tables:

* In the game between IFK Göteborg and Sandvikens IF on August 24th 1930, Göteborg didn’t fulfill its duties, and Sandviken were decided winners. The score, though, is 0–0, but Sandviken won and Göteborg lost. The distribution of points, from this game are thus: Sandvikens IF 2, IFK Göteborg 0.
* The game between Hammarby IF and Djurgårdens IF on August 28th 2006, was abandoned, and Djurgården were decided winners. Hammarby got a three point deduction. The distribution of points, from this game are thus: Djurgårdens IF 3, Hammarby IF -3.