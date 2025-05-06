
## Overview

I thought it'd be fun to poke around with [the 2025 Yorkshire 3 peaks results data](https://www.sportident.co.uk/results/ThreePeaksFellRace/2025/ThreePeaksFellRace/) to visualise my own race and to see how well/ poorly I paced myself between checkpoints...

After making a copy of the data, fiddling with it to turn it into a nice CSV format and then creating a simple plot in google sheets, I realised it'd be pretty neat if I could deploy an interactive version of this so that other people could visualise this data too.

With some perseverance and some help from [cemms1](https://github.com/cemms1) I came up with this.

At the moment it's set-up to only visualise the 2025 data, but give it any other year's data in the same CSV format and it should quite easily cope with that too.

Another potential improvement could be to ask SPORTident permission to plug directly into the API that serves this data, but that feels unnecessary right now.



## Dev
If you want to play around with this locally, run your favourite http server in the root directory e.g.
```
python3 -m http.server 8000
```
