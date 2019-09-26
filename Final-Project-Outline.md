# Hollywood Diversity Report
## An examination of the effects of diversity in casting, directing, writing, and producing in the US film industry's profits and awards

### What Am I Trying to Do?
Hollywood institutions have been saying for years that they value racial and gender minorities. Saying it is one thing. Doing it is another.
Of course, there are some notable success stories. After two years in a row of #OscarsSoWhite, 2019 saw Best Picture nominees for Roma and BlacKkKlansman, with a long-awaited Best Adapted Screenplay win for Spike Lee. Meanwhile, films like Black Panther and Crazy Rich Asians dominated the 2018 box office. The hope is that these films indicate a changing tide and that Hollywood will continue to produce and reward more diverse work. But is that happening?
I plan to investigate the following through data visualizations:
1. For all aspects of the industry, is there actually more diversity, or just the appearance of diversity? If diversity has been increasing, at what rate?
2. How are diversely cast and produced films performing at the box office, especially the Global Box Office (GBO)?
3. Are studios investing in minority filmmakers proportionately to their non-minority counterparts?
4. Do award-granting institutions (the Academy, the HFP, SAG) all recognize minorities at similar rates and with similar proportions?
5. Can box office draws become critical successes and vice versa? Is that more true for minorities than for non-minorities?
6. When it comes to increasing diversity, what side of the film industry has been more successful: the critical darlings or the blockbuster-smashes?

### Call to Action
Increasing diversity is good for its own sake. People should be able to tell their own stories. Audience should be able to see themselves on the screen. Unfortunately, it is rare that this is enough to convince an executive to give millions of dollars to finance a film, especially for films with minority directors and producers.
Evidence, partly from UCLA's annual Hollywood Diversity Report, has shown that films with diverse casts have been performing increasingly well year over year at the GBO, especially relative to non-diverse casts. This should be more of an incentive for executives to finance ambitious and more expensive minority-driven projects.
I assume that not a lot of executives will be reading this report, but they will see the box office reports of people who go to films. My hope is that this project will incentivize movie-goers to send a message to executives with financing capabilities that diverse representations are profitable.

### My Backup Plan
I have not been able to get my hands on the source data for UCLA's Hollywod Diversity Report. While I think there are ways I can tell the same story without that specific data set, it would be nearly impossible to have the level of robustness needed on the scale provided by that report.
So, as a backup plan, I plan to either analyze box office earnings (easily exportable at varying levels of granularity from Box Office Mojo) or Billboard Hot 100 (also easily exportable from Billboard's site) as they compare to award winners. For example, It: Chapter 2 has won the past two weeks at the box office, but it is extremely doubtful that it will be nominated for any awards. Sometimes, though rarely, prestige pictures become box office hits. I'd like to examine this data and see if there are any trends.
As I just mentioned, acquiring the data for box office numbers going back several years is not difficult. Similarly, acquiring the data for Oscar or Grammy nominees is fairly easy. In fact, [the New York Times published an article](/https://www.nytimes.com/interactive/2018/03/03/movies/oscars-best-picture-box-office.html) in 2018 that examined this exact idea, and this article should be easy to scrape data from.
If is not too laborious, I can potentially still include some diversity aspect to this plan, but I will have to do it for directors or lead actors only, as I'll have to build out that portion of the data set myself.

### Sketches

![Median Box Office by Minority Share](/https://user-images.githubusercontent.com/54897462/65654738-c9f18980-dfe7-11e9-804e-25923674e38f.jpg)
I used the same sketch for last week's critique by redesign, but as I used the same data set, I thought I should include it here as well.

### Method and Medium
#### Method
The Hollywood Diversity Report includes data on box office earnings (domestic and GBO), minority cast share percentages, race and gender data for director/producer/writer/DP on every US film released, the Hollywood landscape, the proportion of genres...it really has everything. This report has been published annually since 2011, so I will have access to all of the aforementioned data and more for the past 8 years.

My method will largely follow the outline of the questions I have listed above, namely:
1. *Is Hollywood actually more diverse?* It is easy for anyone to see the minority share in casts, so I hope to examine the minroity share in crew and expose its level of diversity.
2. *What about the GBO?* - Year over year trends show GBO demand growing at a fast rate.  As more global audiences contribute more to the bottom line, Hollywood has been shifting its strategy to appeal to a more diverse audience.
3. *Are studios investing in minorities?* This will go beyond the first question's reporting of minority proportions of cast and crew by associating each project with salary and budget information. Even though more minorities are being hired, the biggest budgets are still reserved for white male directors.
4. *Is it just Oscars so white, or are the Golden Globes so white, too?* Examining prestige is tricky, so I plan to compare different award-granting institutions nominees and award-winners in common categories. If these award-granting institutions have consensus in who they honor, I may also examine the demographic makeup of each of the institutions.
5. *Can box office hits become critical successes and vice versa?* There are numerous individual examples of this, but is it a trend? Are minority directors who have been nominated for Oscars more likely to be "trusted" with big budget projects afterwards?
6. *Who wore it better: the box office or the red carpet?* The data sets here may not be comparable, as there are so much fewer Oscar nominees than wide releases. If I can find a way to make a comparable scale for prestige films and box office successes, I think it will be an interesting insight into who drives the culture, consumers or critics.



#### Medium
I plan to use Shorthand, and I have put some of the information from this Github page in Shorthand to see how the platform functioned. You can see the preview for that page [here](/https://preview.shorthand.com/66xcmpJivtZpmUiL).
