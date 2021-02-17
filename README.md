# Bias in US News Media

Summary:  US news media coverage by volume sees liberal sites capturing a slight majority of the traffic levels.  However, conservative US news media coverage appears to be more likely to incorporate biased or partisan coverage than its liberal counterparts – possibly as a reaction or counterbalance to the volume disadvantage.

I’ll describe an approach I took to examine this question.  I thought it might be useful to look at perceived political bias in US News-media coverage, and see how that aligns with national political ideology.  Charts and graphs are included in this Git repo, but also available [here]( https://imgur.com/gallery/SzXjLN8).   

The short, dirty answer is that news-media consumption in the US sees about:  
54.0% - volume of traffic / consumption captured by liberal leaning sources / outlets  
46.0% - volume of traffic / consumption captured by conservative leaning sources / outlets  

Compare this ratio to the [2020 popular vote split](https://en.wikipedia.org/wiki/2020_United_States_presidential_election) of 52.2% Democrate / 47.8% Republican as well as the [2016 popular vote split](https://www.google.com/search?q=2016+popular+vote&oq=2016+popular+vote&aqs=chrome..69i57j0l7.3719j0j4&sourceid=chrome&ie=UTF-8) 51.1% Democrat and 48.9% Republican (48/46 counting “other” votes).  Consider [2020 pre-election polling numbers](https://projects.fivethirtyeight.com/polls/president-general/national/).  These obviously varied from week to week, but frequently hovered around a 50% Democrat / 42% Republican split.  That 8 to 9% Democrat edge aligns closer to the measured 54 / 46 measured bias.  These vote totals and polling figures seem to imply that the average news-media experience falls pretty close in line with our national ideological balance, but that a slight "liberal bias" might still exist.

My personal opinion is that news-media takes a lot of heat.  They’re a great scapegoat.  But I feel that at the end of the day – their coverage and the narratives they drive go hand-in-hand with what their customers want to hear, and what their correlated politicians want to say.  I think they’re largely a mirror of public sentiment, and less frequently a driver.  

# Methodology and other details...

The segments where I gathered both traffic volume as well as bias measures include data from US News websites, Cable TV News, and News Radio.  Segments that used estimates include: Network TV, Local TV, Social Media, and Other (print, podcasts, local radio, etc.)  [Pew Research]( https://www.journalism.org/2020/07/30/americans-who-mainly-get-their-news-on-social-media-are-less-engaged-less-knowledgeable/) and [RAND](https://www.rand.org/pubs/research_reports/RR4212.html) estimate that Websites, Cable TV, and Radio capture 49% of US news-media consumption, with the other segments capturing the remaining 51%.   

Separating the numbers from estimated vs. measured, we see:  
56% liberal, 44% conservative: measured segments (Online, CableTV, Radio)  
52% liberal, 48% conservative: estimated segments (NetworkTV, LocalTV, Social Media, Other)  

The 56 / 44 split in overall traffic to liberal vs. conservative sources is an aggregated, weighted average total.  Drilling down one level further into the 56/44 split (the more accurate measured data), we see the results for individual segments as follows:  
70% liberal, 30% conservative:  Internet news consumed by volume of traffic  
54% liberal, 46% conservative: Cable TV news consumed by volume of watchers  
37% liberal, 63% conservative: Radio news consumed by volume of listeners  

Purely by volume, we see that liberal news media dominates online traffic, and holds a majority of Cable TV traffic.  Conservative news media dominates radio traffic.  

Also, while volume of traffic to liberal vs conservative sources is important – bias is not simply a left / right binary.  Not all bias is created equal.  Not all liberal sites are the same.  Not all conservative reporting is the same.  Some bias is very subtle and mild.  Some is blatant.  So, I collected and referenced a second measure which scored the extent or prevalence of partisan bias.  Using a scale of 0 to 100, with unbiased coverage sitting at 0, and extreme bias sitting at 100 – the short, dirty answer for bias is:  
22.0 – average bias score for liberal sites  
48.5 – average bias score for conservative sites  

Additionally, the breakdown for the bias scores is as follows:  
23.0 – average bias score for liberal radio  
21.2 – average bias score for liberal online sites  
64.0 – average bias score for conservative radio  
36.3 – average bias score for conservative online sites  

Meaning, conservative sources, on average, present more pronounced partisan bias in their coverage than liberal sites.

# How did I calculate bias scores?

The bias scores were aggregated from several online sources, as much as possible.  Meaning – in almost every case the bias score is NOT my personal assessment of bias (a handful of radio programs were not listed in the sourced bias measures and were the only sites with any manual entries).  Also, these bias scores were only readily available for online news-sites and radio.  Meaning cable TV was not scored (other than a binary liberal / conservative label).

But yes, that means I used mainstream-media sources…. to evaluate bias in mainstream-media.  Commence placement of tinfoil hats.  I don’t claim these bias scores are perfect.  However, I do feel that the binary liberal vs conservative categorization was fairly accurate and consistent.  Also, I only used a simple left / right label.  I didn’t create a third “center” label, or other “far-left” or “far-right” labels.

Some of the labelling was easy.  I expect there would be nearly unanimous consensus from the public that FoxNews and Breitbart are conservative while the NYTimes and HuffPost are liberal.  The more centrist sites tended to be more difficult to assess.  For this project, some of the slightly-leaning conservative sites include WSJ, TheHill, Forbes, and Reuters.  And some of the slightly-leaning liberal sites include Bloomberg, Business Insider, and the AP (Associated Press).

Supporting the claim that labelling conservative vs liberal was consistent and accurate – 231 of the 238 sites assessed had unanimous consensus on their liberal or conservative label.  Only 7 sites had some level of disagreement.  Additionally, the median standard deviation of the bias scores was 8.1.  Meaning, the majority of the bias scores across the various scoring sources (which ranged from -100 to 100) sat somewhat tightly grouped, which also positively reflects on consistency.

While the binary liberal / conservative label is fairly consistent and accurate – the subjective value of the bias score is much more debatable.  From 0 to 100, should FoxNews be rated 10 bias?  20? 50? 100?  This might sound like an entirely subjective and unanswerable question.  However, while it may be difficult to settle immediately on an absolute score – it’s a bit more manageable to compare two sources to be each and agree on their relative bias position.  Is the AP more liberal biased than HuffingtonPost?  Most would say HuffPo is more liberal biased.  Is WSJ more conservative biased than Breitbart?  Most would say Breitbart is more conservative biased.  Proceeding in this manner, bias-charting organizations can make reasonably consistent, relative placement of news-media outlets.

My personal opinion is that the rating services available online inflate conservative outlet bias scores somewhat, versus their comparable liberal sites.  Meaning, the conservative bias scores themselves are skewed (biased!)  But again, while I think it’s fair to be skeptical of the scores themselves – the liberal vs conservative distinction seems to be fairly accurate and consistent.  In the end, regardless of the subjective and imperfect nature of the scores, I felt they added some useful insight.  So I went ahead and presented the collected bias scores.

Finally, while Cable TV news-media programs weren’t individually scored for bias, they were labelled liberal or conservative based on which network carried them.  All CableTV news programs from FoxNews and Fox Business News were labelled conservative, while all programs from CNN, MSNBC, and CNBC were labelled liberal.

# What news-media sources did I include?

News media sourcing is an ever-changing landscape.  However, most publications list 7 standard news-media sources, including:  Cable TV, Network TV, Local TV, Internet Sites, News Radio, Social Media, and Other (including print, podcasts).  Of these 7, I was able to capture data for 3 of them (Cable TV, Internet, Radio).  Pew research estimates that these 3 capture 49% of US news-media consumption.  So the good news is my results above capture half the total news-media market!  The bad news is my directly measured results above miss half the news-media market…

All data collected is listed as CSV files in this Github.  Online news media sources include 238 of the top US news-media sites.  Radio sources were a bit more challenging to dig up comprehensive (and free!) listeners data, but I did find data on the top 26 national news-radio shows.  Cable TV includes the 4 cable stations that include news coverage: CNN, CNBC, MSBNC, FOX.  From these channels – data was collected for the top 72 shows.

Of the segments that were not directly evaluated, I used demographic data of viewers / readers, captured by Gallup, which includes political ideology.  This assumes that the content presented from these segments matches the ideological preferences of the viewers.  Obviously, a big assumption.  However, without direct access to additional data, I’m limited to relying on estimates.  I do feel these estimates are reasonably accurate, as LocalTV, NetworkTV, and Print all to poll well regarding trust levels and unbiased coverage.  Each of these segments showed a nearly exact 50/50 split in bias levels.  

Another question to consider is what news-media sources should be included (and more specifically – which should be excluded.)  The major journalism sites like FoxNews, CNN, New York Times, etc. are easy to categorize as news-media.  Others are more problematic like Late Night TV, SNL, Youtube, etc.  Even movies and sports include some elements of political expression and bias.  However, I restricted my definition somewhat tightly to only include sources that were primarily dedicated to journalism of political and national news reporting (as well as the Radio and TV talk-shows that primarily discussed those topics.)

Additionally, for this project, I restricted my sources geographically to primarily US News dedicated sites. For TV and Radio, this was relatively simple. For online news sites, this was a bit less clear-cut, and a few of the major European sites were included – bbc.com, Reuters, theguardian.com, and dailymail.co, as they cover a significant amount of US news, as well as US readership.

And one last consideration.  I used Gallup poll numbers that list which sources Americans go to, to get their news.  If an adult lists “online and cable TV” as their typical and frequent news sources – my volume numbers effectively assume equal news consumption from each source.  However, consumption habits vary.  Can you compare a 3 hour daily Rush Limbaugh power-listener to a 30 minute NPR-news commuter to a 10 minute online FoxNews browser to a Google News reader that rarely clicks articles but scans titles for hours?  Clearly, the news experience can vary significantly, and the amount of bias exposure can’t be perfectly captured solely by looking at volume measures and bias scores.

# Sources

Website traffic pulled from SimilarWeb from May 2020:  
https://www.similarweb.com

CableTV traffic pulled from Adweek Nielsen ratings from May 2020:     
https://www.adweek.com/tvnewser/q2-2020-cable-news-show-ranker/446758/

Radio listeners traffic pulled from Nielsen and Talkers 2019:  
http://www.talkers.com/top-talk-audiences/  
https://today.yougov.com/ratings/media/popularity/radio-programs-podcasts/all  


Bias scoring sources:  
Bias1 = https://www.adfontesmedia.com/interactive-media-bias-chart/  
Bias2 = https://MediaBiasFactCheck.com  
Bias3 = https://www.allsides.com/media-bias/media-bias-ratings  
Bias4 = https://www.journalism.org/2014/10/21/political-polarization-media-habits/  
Bias5 = manual entry  

Polling sources:  
https://www.journalism.org/2020/07/30/americans-who-mainly-get-their-news-on-social-media-are-less-engaged-less-knowledgeable/  
https://www.rand.org/pubs/research_reports/RR4212.html  
https://news.gallup.com/poll/275792/remained-center-right-ideologically-2019.aspx  

Other useful articles giving additional insight into media bias in the US.  
https://www.mediamatters.org/facebook/study-facebook-still-not-censoring-conservatives  
https://www.mediamatters.org/facebook/study-analysis-top-facebook-pages-covering-american-political-news  
https://en.wikipedia.org/wiki/Media_bias_in_the_United_States  
https://www.pewresearch.org/fact-tank/2019/09/11/key-findings-about-the-online-news-landscape-in-america/  
https://advances.sciencemag.org/content/6/14/eaay9344  
https://www.oxfordbibliographies.com/view/document/obo-9780199756841/obo-9780199756841-0111.xml#obo-9780199756841-0111-div2-0001  
