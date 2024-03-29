## NotSampo
SberTech hackaton (project optimization)

Team «Мятная стекловата»: our solution #2

Features:
1. Uses ant colony optimization algorithm
3. Supports individual resource calendars
4. Objective functions: time, cost, workers
5. Supports weights for objectives
6. Light, fast and expandable

For testing, the IMOPSE dataset [[link](http://imopse.ii.pwr.wroc.pl/download.html)] was used

### Examples
Target: time

![plot](https://github.com/maximdu/notsampo/blob/main/notsampo/plots/time.png/?raw=true)

Target: wage (cost)

![plot](https://github.com/maximdu/notsampo/blob/main/notsampo/plots/wage.png/?raw=true)

Target: weighted time and cost (time + cost/10^5)

![plot](https://github.com/maximdu/notsampo/blob/main/notsampo/plots/weighted.png/?raw=true)

Literature:
1. Ant colony optimization for resource-constrained project scheduling (2002)
2. Solving software project scheduling problems with ant colony optimization (2013)
