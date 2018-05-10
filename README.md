# NICAR lightning talks analysis

By [Christine Zhang](https://twitter.com/christinezhang)

I wrote a post for Source about the lightning talks at the annual NICAR (National Institute for Computer-Assisted Reporting, aka "data journalism") [conference](https://ire.org/conferences/nicar18/). The lightning talks session consists of 10 five-minute talks, back-to-back. The talks are submitted and voted on by conference attendees, providing a window into how the conference has evolved over time.

To investigate this topic, I collected and analyzed all the data from the NICAR lightning talks between 2010--the first year that they were held--and 2018.

This GitHub houses the cleaned data in `lightningtalks_clean.csv` and the analysis code, written in R, in the Jupyter notebook `analysis.ipynb`. I have also included the code I used to scrape the html of the past NICAR lightning talks submission sites in `processing/get_data.ipynb`, though some columns have been added to the cleaned version.

Here are the columns in `lightningtalks_clean.csv`:

| column        | description           | 
| ------------- | -------------| 
| `year`     | year of conference | 
| `title`      | talk title      | 
| `speaker`     | speaker who pitched to the site | 
| `copresented`      | was there a co-presenter? 1 = yes  |
| `copresenter`      | name of co-presenter, if yes | 
| `org`     | organizational affiliation of speaker at the time of the talk      |
| `nonmale`     | gender identity of speaker; 1 = nonmale      |
| `location`     | location of speaker at the time of the talk      |
| `international`     | was the speaker from outside of the U.S.? 1 = yes      |
| `description`     | talk description      |
| `votes`     | number of votes the talk received      |
| `top_10`     | was the talk selected to be presented at NICAR (usually this mean it was in the top 10)? 1 = yes      |
| `gave_talk`     | did the speaker give the tak at NICAR (some years had last-minute changes)? 1 = yes      |




