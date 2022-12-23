<style>
black { color: black }
</style>
# <black> Let's play a little game! 
## <black> Try to find matching pairs of the nominees for the acting academy award of 2016!
  <title>Memory Game</title>
  <link rel="stylesheet" href="styles.css">
  <section class="memory-game">
    <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0000_Layer-2.png" alt="M1" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0001_Layer-3.png" alt="M2" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0002_Layer-4.png" alt="M3" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0003_Layer-5.png" alt="M4" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0004_Layer-6.png" alt="M5" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0010_Layer-12.png" alt="M6" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0011_Layer-13.png" alt="M7" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0012_Layer-14.png" alt="M8" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0013_Layer-15.png" alt="M9" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="male">
      <img class="front-face" src="img/oscar-nominees_0014_Layer-16.png" alt="M10" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0005_Layer-7.png" alt="F1" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0006_Layer-8.png" alt="F2" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0007_Layer-9.png" alt="F3" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0008_Layer-10.png" alt="F4" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0009_Layer-11.png" alt="F5" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0015_Layer-17.png" alt="F6" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0016_Layer-18.png" alt="F7" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0017_Layer-19.png" alt="F8" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0018_Layer-20.png" alt="F9" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>  <div class="memory-card" data-framework="female">
      <img class="front-face" src="img/oscar-nominees_0019_Layer-21.png" alt="F10" />
      <img class="back-face" src="img/dlab.svg" alt="dlab" />
    </div>
  </section>
  <script src="scripts.js"></script>

# <black> Why was this so easy?

## <black> Because all the nominees for the acting academy award of 2016 were white.


# <black> So what is this about?
After in 2015 all 20 oscar acting nominations were awarded to white people, the [#OscarsSoWhite](https://mobile.twitter.com/search?q=%23oscarssowhite) hastag, criticising the lack of diversity and calling for changes in the film industry, went viral.

![Tweet_oscarssowhite](https://user-images.githubusercontent.com/115152807/209368526-95eb7624-c291-4f71-8cb0-948f5b1615ec.png)

But should the film industry comply with these demands purely for ethical reasons, or does the film industry benefit from a more diverse cast also from a capitalistic point of view? To investigate whether a more diverse cast attracts a larger audience and thus achieves more financial success, we examine the box office revenue of the films in the ["CMU Movie Summary Corpus"](http://www.cs.cmu.edu/~ark/personas/) dataset. To avoid sparsity of data and to add further interesting features that go beyond the CMU dataset, we also add the ["The Movies Dataset"](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset). As a measure of diversity, we focus mainly on ethnicity, gender, and age. In particular, we are interested in whether moviegoers' acceptance or rejection for movies with a more diverse cast has changed over the last 100 years. Since movies produced in the US have the biggest audience and make by far the most money, we'll restrict our analysis to those movies.

# <black> And why should we care?
## <black> 1) Financial reasons
The movie business is a multi-billion-dollar industry, therefore it would be very beneficial to know what sells and what does not. 

## <black> 2) Societal relevance
Diversity is one of the most controversial topics of our time. However, the discussions about this are mostly based on feelings and subjective impressions. An analysis based on data should lead to a more objective assessment of this contentious subject. And since movies can be seen as a reflection of their time, the results of our analysis could act as an indicator for changes and advancements in society over time.

# <black> This leads us to our research questions...

## <black> Let's talk about money:
In this paragraph we examine general changes regarding the movie industry over time.
The following plot shows that the actual value of 1 US-dollar changed dramatically between 1900 and 2022. Therefore, we have to take inflation into account, to be able to compare the movie box offices across different decades.
  
![Plot 1](https://user-images.githubusercontent.com/115152807/209177949-5a73702e-4890-4ad2-9b06-ec33899c320f.png)

With the inflation adjusted box office revenue shown in the next plot, it can be seen that the rise of revenue over time is not as significant as it initially seems.
  
{% include box_office_evolution.html %}

In the subsequent plots, we can also see that the budget of movies has increased over time. Compared to the box office revenue, we can see that the budget is increasing faster, which implies that the ratio between budget and revenue is actually slightly decreasing.
  
![average_budget](https://user-images.githubusercontent.com/115152807/209404178-87e0dcbd-6517-439a-9780-43892b49c910.png)
  
![maximum_budget](https://user-images.githubusercontent.com/115152807/209404176-677afa79-6d02-4d19-b009-960e62af5620.png)

Another interesting question would be how big the share of really sucessful movies is compared to the overall number of movies. The following plot delivers the answer and shows that the vast majority of released movies do not generate a huge amount of box office revenue.
  
![box_office_distribution](https://user-images.githubusercontent.com/115152807/209185289-29440889-5ec5-4f8e-807b-8f1717a29388.png)
  
The number of movie releases increased drastically in the last 100 years as depicted in the following plot. This implies that the movie industry is a growing market.
  
![number_of_movies](https://user-images.githubusercontent.com/115152807/209181308-758de80c-eceb-40a5-b887-de69bc6b4421.png)

##	<black> Which characteristics of movies are correlated with the movie box office revenue?

It seems logical that the box office revenue is correlated with many characteristics of movies. The most obvious one, would be the influence of the movie budget on the box office revenue. Indeed, while not directly related, the budget influences other characteristics of movies such as more sophisticated visuals and more famous cast, which usually leads to more popular movies. A higher budget tends to lead to a higher gross. We can also see that the public perception of a movie which is getting represented through the TMDB vote counts and vote averages slightly correlates with the box office. A movie which is getting perceived as a good movie is making more money than a movie which is getting perceived as a bad movie.
 
As we can see in the plots below, other variables like gender, actor ethnicities etc. seem to have an influence on the box office revenue as well, which we will explore in more detail in the rest of this datastory.
  
![16 plots](https://user-images.githubusercontent.com/115152807/209405126-55eea8d0-5e93-4aea-9c37-47318969b296.png)

Another important movie characteristic is the genre. Over the decades the distribution of the most popular genres changed.
  
{% include box_office_genre_evolution.html %}

## <black> Let's talk about diversity:
First we have to clarify here, what diversity is. Wikipedia says that "Diversity as seen in sociology and political studies is the degree of differences in identifying features among the members of a purposefully defined group, such as any group differences in racial or ethnic classifications, age, gender, religion, philosophy, physical abilities, socioeconomic background, sexual orientation, gender identity, intelligence, mental health, physical health, genetic attributes, personality, behavior or attractiveness" [1]. In our analysis we focus on racial and ethnic classsifications, gender, and age. 

##	<black> Does ethnical diversity correlate with the box office revenue?
In order to answer this question, we have to clarify first how we confine different races and ethnicities. Since we examine only US-american movies, we adapt the racial and ethnical categories of the US census [2].

Following this definition, there exist the six following racial categories: 

  1) White

  2) Black or African American

  3) Asian

  4) American Indian or Alaska Native

  5) Native Hawaiian or Other Pacific Islander

  6) Other (e.g Aboriginal or Indigenous Australian)

For ethnicities, there exist the following two categories:

  1) Hispanic or Latino

  2) Not Hispanic or Latino

To avoid sparsity of data, we neglect the differentiation between the different ethnicities (Hispanic or Latino and Not Hispanic or Latino). At this point, we would like to mention that throughout this datastory we use the term "ethnicity" instead of the US-american term "race".
 
##	<black> Did ethnical diversity in movies change over time?
  
The following plots depict the distribution of the different ethnicities of the movie characters for the most successful movies from each decade in our dataset. In this case, the most successful movies are defined as the ten movies with the highest box office revenue in the decade. As we can see, the vast majority of movie characters in every decade is white, and the dominance of white characters has its peak in the 1950s. To get more insights about the distribution of minorities, you can click in the subsequent plot on the white_ratio label to hide it. Then it is clearly visible that the second most represented racial group is Black or African American. Since the 1970s, there appears to be an increase of the diversity among the minorities.
  
{% include ethnicities_evolution.html %}

The previous plot gave us an insight about ethnical diversity importance among the top movies of each decade, but what we really want to know is whether increasing diversity will lead to a box office revenue increase. We can show this with the following plot, showing ethnical diversity against box office revenue. The regression lines show that, while minor, an increased white people ratio will lead to a decrease in box office revenue while an increased black african american ratio will lead to an increase in box office revenue. From the lack of representation of the other ethnical minorities, it is harder to make a statement about their influence on the box office revenue.

![ethnicity_vs_box_office_regression](https://user-images.githubusercontent.com/115152807/209410661-2f5e1742-0821-4ad9-bbef-626d15d2f465.png)

##	<black> Did the gender ratio of the cast in movies change over time?
The following plot demonstrates the gender distribution of the movie cast for each decade. As we can see, the distribution was nearly even in the 1910s and then changed in favor of a male superiority, which had its peak in the 1970s. Since then the share of female actors in the cast is slightly increasing. However, the distribution in the 2010s is still 2:1 in favor of males.
    
![gender ratio evolution](https://user-images.githubusercontent.com/115152807/209194110-2c4fa8d9-7e0c-41c1-809d-a2a048ac2738.png)

 ### But what about the influence of the gender ratios on revenue? 
Talking about the most successful movies, it appears that male dominated casts tend to generate slightly more box office revenue compared to female dominated casts. The regression plot below illustrates this fact.
  
![male_female_vs_box_office_regression](https://user-images.githubusercontent.com/115152807/209401566-6783d01a-8fa6-453d-91d9-372bbb6e409c.png)
  
It is interesting to note that although this visualization shows a clear trend, other statistical visualizations such as the following paired test contradict these findings, and shows that while it was significantly worse to have a higher female ratio before the 1950s, it has since become significantly positive in order to generate higher earnings to have a higher female ratio after 2010.
For this reason, we must always be careful when presenting findings that look significant at first glance.
  
![female_ratios_differece](https://user-images.githubusercontent.com/115152807/209411333-20d3aa7a-da00-4f64-8a1a-d6a53c8fe431.png)
  
## <black> Did the age distribution of actors in movies change over time?
The following plot demonstrates the evolution of the age distribution of movie actors over the decades. As we can see, in the early 1900s, it seems actors were mostly young early adopters. The mean of actors then steadily increase with time, as if the same group of actors grew together. New young actors joining in may be the reason that the mean increase is not quite linear. Since the 1960, the age distribution has stopped going up and seems to have stabilized. Therefore, we can conclude that in the regard of age, diversity increased over time.
  
{% include age_evolution.html %}
  
# <black> Discussion
Although we showed some trends indicating that diversity may sometimes be beneficial, there are any more confounders influencing box office revenue. Below, we present a causal diagram we believe represents a good part of these confounders. In general, the movie studio and its budget have a big influence on the main elements that directly influence box office revenue.
  
![causal_diagram](https://user-images.githubusercontent.com/115152807/209399951-5634558c-3fd9-4aac-8331-5db2c97ae6bf.png)

# <black> Conclusion
Does diversity pay off? 
We would say yes, especially in more recent times where people have become more aware of the importance of diversity in a more general way. Diversity in the context of ethnicities and age seems to be improving. However, there are still further improvements to be made, especially in the context of diverse gender representation. 

# <black> Now try it out yourself!
[Play around with different movie characteristics and see how they affect the box office!](https://matt989253-ada-2022-project-b0b-machine-learning-website-tjfnoq.streamlit.app/)
  
# <black> References
[1] [https://en.wikipedia.org/wiki/Diversity_(politics)](https://en.wikipedia.org/wiki/Diversity_(politics))

[2] [https://en.wikipedia.org/wiki/Race_and_ethnicity_in_the_United_States](https://en.wikipedia.org/wiki/Race_and_ethnicity_in_the_United_States)

# <black> Roll the Credits!
Written and directed by b0bEast (Colin Pelletier, Matthieu Burguburu, Jan Henke, Hendrik Schillinger)
  
Produced as part of the course [Applied Data Analysis (CS-401)](https://dlab.epfl.ch/teaching/fall2022/cs401/) at EPFL in Fall 2022
  
The script can be found [here](https://github.com/epfl-ada/ada-2022-project-b0beast)
