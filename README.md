# big-five-data
Big five personality trait averages for 307,313 people from different countries. Averages were calculated by myself as per the official guidelines from the  [International Personality Item Pool(IPIP)](https://ipip.ori.org/) from raw data provided to the 300 item IPIP-NEO-300 questionnaire which is the most accurate public domain personality test available.

This repository contains:

 - SQLite database with the average big five trait scores from all participants.
 - CSV file of those average big five trait scores.
 - CSV scoring key used to map participants answer to the relevant traits score.

### Data Legend

**case_id:** Unique id of the person the results belong to

**country:** Where the person is from

**age:** Age of the person

**sex:** Biological sex of the person. 1=male, 2=female

Rest of the columns are their average scores from 0 to 1 for each of their big five personality traits: Agreeableness, Extraversion, Openness(Openness to experience), Conscientiousness, Neuroticism

[Read more about what these traits mean here](https://en.wikipedia.org/wiki/Big_Five_personality_traits#Descriptions_of_the_particular_personality_traits)

### Sample Data

**case\_id**|**country**|**age**|**sex**|**agreeable\_average**|**extraversion\_average**|**openness\_average**|**conscientiousness\_average**|**neuroticism\_average**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
1|South Afri|24|1|0.753333333333333|0.496666666666667|0.803333333333333|0.886666666666667|0.426666666666667
3|UK|24|2|0.733333333333333|0.68|0.786666666666667|0.746666666666667|0.59
4|USA|36|2|0.88|0.77|0.86|0.896666666666667|0.296666666666667
5|UK|19|1|0.69|0.616666666666667|0.716666666666667|0.636666666666667|0.563333333333333
6|UK|17|1|0.6|0.713333333333333|0.646666666666667|0.633333333333333|0.513333333333333
7|USA|17|1|0.603333333333333|0.586666666666667|0.653333333333333|0.596666666666667|0.623333333333333
8|USA|28|2|0.81|0.68|0.87|0.76|0.51
9|Denmark|28|2|0.796666666666667|0.596666666666667|0.87|0.646666666666667|0.456666666666667
10|USA|18|1|0.61|0.706666666666667|0.886666666666667|0.59|0.656666666666667
11|Singapore|17|1|0.84|0.483333333333333|0.543333333333333|0.723333333333333|0.65
12|Sweden|17|2|0.66|0.726666666666667|0.74|0.68|0.58
13|India|21|1|0.823333333333333|0.866666666666667|0.813333333333333|0.976666666666667|0.27
14|USA|55|2|0.8|0.683333333333333|0.72|0.666666666666667|0.706666666666667
15|USA|48|2|0.78|0.613333333333333|0.713333333333333|0.833333333333333|0.683333333333333

If you appreciate valuable public datasets such as these, please share this repository and consider a donation to the [IPIP Foundation](https://ipip.ori.org/newWilling_to_Help.htm)

### Sources
[IPIP-NEO Data Repository](https://osf.io/tbmh5/)
[International Personality Item Pool](https://ipip.ori.org/)