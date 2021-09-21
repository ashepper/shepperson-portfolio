# Visualizing Abortion Data
On December 1, 2021, the [Supreme Court will hear a case](https://www.nytimes.com/2021/05/17/us/politics/supreme-court-roe-wade.html) challenging <i>Roe v. Wade</i>. With a pregnant person’s right to bodily autonomy on the line, it is vital that we are able to effectively communicate the long term effects of <i>Roe v. Wade</i> and abortion access in the United States. This means being able to gather and represent data in a way that is clear, intuitive, and appealing to the broader public. 

The graphic below, found in [this article from](https://www.economist.com/graphic-detail/2017/01/18/the-abortion-rate-in-america-falls-to-its-lowest-level-since-roe-v-wade) <i>The Economist</i>, attempts to depict the change in abortion rates over time in the United States after <i>Roe v. Wade</i>. We will walk through what is and is not working about this visualization, and create a version that more accurately and honestly depicts abortion trends in the United States after the 1973 landmark decision.
![image](/economist_snip.png)

## Critiquing the Visualization
### Overall Observations
This visualization aims to depict trends in abortion rates over time among US women. The authors try to contextualize the abortion data by including information such as simultaneous birth rates and indicating key events that might affect abortion rates.

Based on the article and what is included in the visual, it seems that the creators are a little lost in what the purpose of the visualization is. Depending on their goal, some of the information included could be seen as extraneous. The article discusses many possible causes of the declines in abortion rate in recent years, but makes no definitive statement as to why this may be occurring. 

Some of the potential causes discussed in the article are less easily visualized than others. For example, one possible cause for a decreasing birth rate discussed is simply a decreasing rate of unwanted pregnancies. This could be influenced by a variety of factors including education levels of women, increased usage of contraceptives, among others reasons. It would be very difficult to display all of the potential contributing factors on this one visual. This is likely one of the reasons this simpler version that only displays some key events was used. 

That said, it could make more sense to instead have the focus of the graph be to visualize abortion rates in relation to total pregnancies. This is attempted by the author by including the birth rate trends in the graph. However, the way that the birth rate is represented is misleading. Because there are different scales for two overlaid line graphs representing birth and abortion rates, at times it looks as if the birth rate is below the aboriton rate. This insinuates that women are having more abortions than they are giving birth, which is false.

This confusion could be resolved if the abortion rate was represented as a part of a whole. This would help the reader understand visually if abortion rates are rising because pregnancy rates are rising, or if it is due to some other factor.
The way it stands the visualization is not easy to understand at first glance, though with time it is interpretable. The main point of confusion on the graph are the two Y-axis with different scales. Putting birth rate and abortion rate on the same scale would increase the interpretability of the graph by leaps and bounds.

In terms of aesthetics, I would say that this visualization is currently about average. The colors seem arbitrary but at the same time are not necessarily distracting. The palette is appropriately limited. Because the intended focus of the visualization is the abortion rate, it may make more sense to have this line be a bright color like the blue used for birth rate, and birth rate represented in gray. If the focus of the graph is to see the trends in relation to when key legislation/court cases occurred, I support having the dates of these events in red to draw attention to these time periods.

Overall, I do not think that the visualization is particularly inspiring. There are some key moments that stick out and may cause discussion . For example, the noted steep drop in birth rate after abortion laws liberalised in 15 states in (1969? Or is it 1970? It is hard to tell from the labeling!), as well as the increase in abortion rate. Even with these pieces of information visualized, displaying the information in a clearer way and with a fuller picture would be beneficial to the audience.

### Audience
The intended audience is readers of The Economist; these are likely educated (male) readers. The title of the article suggests that it is targeted towards people who have an interest in abortion, and the purpose is to help them understand if and why it may be increasing or decreasing in frequency.

The visualization does communicate valuable information: the birth and abortion rates among women age 15-44 in the United States. However, the information takes some time to interpret. Readers must look at not just two but 3 axes in order to interpret the data. Only a reader with patience would be able to interpret the visualization.

Similarly, it is hard to tell from the graph what the larger intent of the visualization is. Readers can see from the visualization  that birth rates and aboriton rates are declining, but it is hard to visualize the bigger picture. The graph makes an attempt to get at this “bigger picture” by including the dates of some key policy and societal changes, but it does not include all of them. Simply displaying the abortion rate and birth rate as a part of a larger pregnancy rate could provide a fuller picture of the trends that are occurring without swaying the reader into thinking certain events or policies have more impact than others, simply because others are not represented.

## Wireframing a Solution
### Version 1:
My first attempt at visualizing the data  was an area chart. I felt that displaying the number of abortions as a proportion of total pregnancies was critical in understanding the data on a deeper level. It was also a good way to have all the data on the same axes, remedying one of the main flaws of the original visual.

![image](/abort_wire1.png)

### Version 2:
In version 2, I went for a simple line graph. While the numbers no longer reflected proportions, I thought maybe this version would be preferable to those who aren’t as familiar with area charts or think they are confusing. The line chart is familiar with most populations (I felt), and would perhaps be more easily interpretable. I wanted to retain the “total pregnancies” as a benchmark, so kept that on the same axis.

![image](/abort_wire2.png)

### Version 3:
I made version 3 after the first round of feedback that I received. The  person interpreting my first graph was confused about the format of an area chart, and what the number on the y-axis represented. They also found the simple line chart confusing, and thought that the “total pregnancies” line was additional information that had not been included in the first version. This third version was my attempt at making the area chart clearer with more direct titles and switching the order of live birth, abortion, and fetal loss for births (the largest proportion) to be on top.

![image](/abort_wire3.png)


## User Testing
After a full round of feedback on all three versions, no one told me exactly what I wanted to hear! According to the “users,” there were confusing parts about each of the visualizations; though the third version remained the most popular. Some people suggested that a line graph might be more effective. Area charts are not intuitive to those who do not look at graphs on a regular basis (in my sample size of 4)!

### Gordon’s feedback:
##### Version 1:
<b> Can you tell me what you think this is?</b> <i>A graph depicting results of pregnancy in US women </i>
<b>Can you describe to me what this is telling you?</b> <i>More fetus losses than live births. Fetus line is all the way up at the top. Live birth section is largest but does not have highest numbers so thats confusing. Am I reading lines or width of the shape? </i>
<b>Is there anything you find surprising or confusing?</b> <i> I don’t belive there are no abortions before 1970</i>
<b>Who do you think is the intended audience for this?</b> <i>No idea. People who want to know about birth. If you’re worried about your own baby not this graph, you wouldn’t care about abortion. People who want to make a case about aboriton maybe?</i>
<b>Is there anything you would change or do differently?</b> <i>Change how the data is presented. Make it clear what the numbers actually are. Should i read the width or the number on the axis? Put higher percentage one on top. </i>

##### Version 2:
<b> Can you tell me what you think this is?</b> <i>This is the same thing but better presented</i>
<b> Is there anything you find surprising or confusing? </b> <i> I learned something new! Out of 1000 women only 100 are pregnant. For some reason you included line for total pregnancies. The total pregnancies line is different information than live birth, aboriton, fetal loss so I don’t understand why its there. If rate per 1000 women how is there always 100 pregnancies. Why is it per 1000 women why isn’t it just per 100 pregnancies. Then you wouldn’t need the line. There are three categories that are all part of the total.</i>
<b>Is there anything you would change or do differently?</b> <i>Put rate out of per 100 pregnancies and get rid of total pregnancies line</i>

### Amy's Feedback
##### Version 3:
<b>Can you tell me what you think this is?</b> <i> An area chart of what happens after women become pregnant in the US.</i> <b>Can you describe to me what this is telling you?</b> <i> Based on the title, it's telling me that abortion rates have declined over time.</i> <b>Is there anything you find surprising or confusing?</b> <i>The scale of the stacked area. </i> <b>Is there anything you would change or do differently?</b> <i>Overall it's pretty clear in terms of visualizing the trend! and the colors are cute. Honestly i wouldnt mind just seeing them as trendlines instead -- i think it would feel a little more intuitive. </i>

### Rihanna's Feedback
##### Version 3:
<b>Can you tell me what you think this is?</b> <i> Is the reported portion reported abortions? Legal aboritons? Estimated aboritons? Spike is around roe v wade butfrom what I see of this graph it doesn’t show that probably a lot more abortions were happening that we dont know about. </i> <b> Can you describe to me what this is telling you? </b> <i> Abortions have decreased in proportion as pregnancies have decreased. Its showing me correlation not causation though, which is ok. </i> <b> Is there anything you find surprising or confusing? </b> <i> No. </i> <b> Is there anything you would change or do differently? </b> <i>Gender inclusive language. </i>

### Grace's Feedback
##### Version 3:
<b> Can you tell me what you think this is? </b> <i> Rates of women having aboritons vs live birth or fetal loss form 1970-today. </i> <b> Is there anything you find surprising or confusing? </b> <i> Not really, the colors are a little confusing. </i> <b> Who do you think is the intended audience for this? </b> <i> Voters. </i>

## The Solution
Taking the feedback I received, I made two final representations of the data. Both have clear titles indicating that we are examining aboritons post <i>Roe v. Wade</i>, and mark <i>Roe v. Wade</i> on the visualization, mimicking the tactic used in the Economist.

<div class="flourish-embed flourish-chart" data-src="visualisation/7313442"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The first version is a stacked area chart. Because we are looking at aboritons, abortions are highlighted in blue, with live births and fetal losses indicated in gray. This draws the reader in to look at aboritons as a part of a larger whole, while still focusing on abortions. Overall, I think that this format is confusing for people who are not familiar with this type of graphic, mostly because the y-axis does not align with the proportion each category is representing. For those familiar with this type of graph, I believe this would be a good alternative to the chart used by the Economist.

<div class="flourish-embed flourish-chart" data-src="visualisation/7313688"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

In a more general setting with a wide audience, I would use this line graph. I transformed the data to show the number of abortions per 1000 births. This retains the ability to show aboriton as a part of a larger whole without using the area chart, which seems to be more confusing for some audiences. Sometimes, the simplest is best!
