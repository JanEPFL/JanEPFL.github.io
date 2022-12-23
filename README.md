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

But should the film industry comply with these demands purely for ethical reasons, or does the film industry benefit from a more diverse cast also from a capitalistical point of view? To investigate whether a more diverse cast attracts a larger audience and thus achieves more financial success, we examine the box office revenue of the films in the ["CMU Movie Summary Corpus"](http://www.cs.cmu.edu/~ark/personas/) dataset. To avoid sparsity of data and to add further interesting features that go beyond the CMU dataset, we also add the ["The Movies Dataset"](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset). As a measure of diversity, we focus mainly on ethnicity, gender, and age. In particular, we are interested in whether moviegoers' acceptance or rejection for movies with a more diverse cast has changed over the last 100 years. Since movies produced in the US have the biggest audience and make by far the most money, we'll restrict our analysis on those movies.

# <black> And why should we care?
## <black> 1) Financial reasons
The movie business is a multi-billion-dollar industry, therefore it would be very beneficial to know what sells and what does not. 

## <black> 2) Societal relevance
Diversity is one of the most controversial topics of our time. However, the discussions about this are mostly based on feelings and subjective impressions. An analysis based on data should lead to a more objective assessment of this contentious subject. And since movies can be seen as a reflection of their time, the results of our analysis could act as an indicator for changes and advancements in society over time.

# <black> This leads us to our research questions...

## <black> Lets talk about money:
In this paragraph we examine general changes regarding the movie industry over time.
The following plot shows that the actual value of 1 US-dollar changed dramatically between 1900 and 2022. Therefore, we have to take inflation into account, to be able to compare the movie box offices across different decades.
![Plot 1](https://user-images.githubusercontent.com/115152807/209177949-5a73702e-4890-4ad2-9b06-ec33899c320f.png)
As we can see in the following two plots, even without inflation, the average movie box office revenue as well as the maximum movie box office increased in the last 100 years. This implies that movies are getting more popular and more successful over time.
{% include box_office_evolution.html %}
![Plot 2](https://user-images.githubusercontent.com/115152807/209178710-2f249046-6815-4067-9520-86217c420ffd.png)
![Plot 3](https://user-images.githubusercontent.com/115152807/209178721-97e6d243-7740-486d-9794-6be34d165d8d.png)
In the subsequent two plots we can also see that the budget of movies also increased over time and that the ascent is even more steep than the ascent of the box office revenue. This implies that the movies are getting more expensive over time and the ratio between budget and revenue is actually slightly decreasing.
![Plot 4](https://user-images.githubusercontent.com/115152807/209180362-2b5e1b7c-1443-4f84-a45d-0ed5a31b3f81.png)
![Plot 5](https://user-images.githubusercontent.com/115152807/209180368-b18c693f-649e-4aca-93e0-88fb5cb4a354.png)
Another interesting question would be how big the share of really sucessful movies is compared to the overall number of movies. The following plot delivers the answer and shows that the vast majority of released movies do not generate a huge amount of box office revenue.
![Plot 6](https://user-images.githubusercontent.com/115152807/209185289-29440889-5ec5-4f8e-807b-8f1717a29388.png)
The number of movie releases increased drastically in the last 100 years as depicted in the following plot. This implies that the movie industry is a growing market.
![Plot 7](https://user-images.githubusercontent.com/115152807/209181308-758de80c-eceb-40a5-b887-de69bc6b4421.png)

##	<black> Which characteristics of movies are correlated with the movie box office revenue?
TODO: Following paragraph needs Update!
As we can see in the plot below, the box office revenue correlates with the budget of the movie. A higher budget tends to lead to a higher gross. We can also see that the public perception of a movie which is getting represented through the TMDB vote counts and vote averages slightly correlates with the box office. This implies that a movie which is getting perceived as a good movie is making more money than a movie which is getting perceived as a bad movie. The runtime on the other hand does not seem to have an influence on the financial success of a movie.
![Plot 8](https://user-images.githubusercontent.com/115152807/209186176-9e28bcdb-5e37-4cae-8b1d-bfe2af0cdea2.png)
The plot below shows that...
![Plot 9](https://user-images.githubusercontent.com/115152807/209186298-721c7829-4484-48cc-b2ba-9a9cdda08207.png)

![male_female_vs_box_office](https://user-images.githubusercontent.com/115152807/209372441-1321b2a3-3d48-427d-b331-fb755aaacad8.png)
![male_female_vs_box_office_regression](https://user-images.githubusercontent.com/115152807/209372442-8876757f-b5e7-431c-bdb9-aa0801d3a798.png)


## <black> How did the distribution of the most popular genres changed over time?
{% include box_office_genre_evolution.html %}

## <black> Lets talk about diversity:
First we have to clarify here, what diversity is. Wikipedia says that "Diversity as seen in sociology and political studies is the degree of differences in identifying features among the members of a purposefully defined group, such as any group differences in racial or ethnic classifications, age, gender, religion, philosophy, physical abilities, socioeconomic background, sexual orientation, gender identity, intelligence, mental health, physical health, genetic attributes, personality, behavior or attractiveness" [1]. In our analysis we focus on racial and ethnic classsifications, gender, and age. 

##	<black> Does ethnical diversity correlate with the box office revenue?
In order to answer this question, we have to clarify how we confine different races and ethnicities. Since we examine only US-american movies, we adapt the racial and ethnical categories of the US census [2].

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

The following plot depicts the distribution of the different ethnicities of the movie characters in our dataset. It is clearly visible that the majority of the characters are white.
{% include ethnicities_evolution.html %}
{% include ethnicities_radar_chart.html %}
![Plot10](https://user-images.githubusercontent.com/115152807/209190539-a0584b66-48ff-43be-89b0-2d11be17eb32.png)
##	<black> Did ethnical diversity in movies change over time?
The next plot shows the distribution of the races of all movie characters for each decade. As we can see, the vast majority of movie characters in every decade is white and the dominance of white characters has its peak in the 1950s. However, since then the share of Asian and especially Black or African American characters has increased. This implies that the cast of movies has become more diverse over time.
![Plot11](https://user-images.githubusercontent.com/115152807/209192030-38489df2-2862-4316-8469-7fa7be316b8e.png)

##	<black> Did the gender ratio of the cast in movies change over time?
The following plot demonstrates the gender distribution of the movie cast for each decade. As we can see, the distribution was nearly even in the 1910s and then changed in favor of a male superiority, which had its peak in the 1970s. Since then the share of female actors in the cast is slightly increasing. However, the distribution in the 2010s is still 2:1 in favor of males.
![Plot12](https://user-images.githubusercontent.com/115152807/209193221-4388528e-38ed-4aa5-a18f-9b0e48a70b19.png)
![Plot13](https://user-images.githubusercontent.com/115152807/209194110-2c4fa8d9-7e0c-41c1-809d-a2a048ac2738.png)

## <black> Did the age distribution of men and women of the cast in movies change over time?
The following plot demonstrates the evolution of the age distribution of movie actors over the decades. As we can see, in the 1940s the group of actors, who were in their 30s was by far the biggest group. Since then,their share decreased steadily over each decade and in the 2010s the age distribution is more equally distributed than ever before. Therefore, we can conclude that in the regard of age, diversity increased over time.
![Plot14](https://user-images.githubusercontent.com/115152807/209194265-a755cada-7575-4883-a730-7680ba750de2.png)

# <black> (Discussion)
-> boundaries of our analysis

# <black> Conclusion
-> summarize our findings

# <black> References
[1] https://en.wikipedia.org/wiki/Diversity_(politics)

[2] https://en.wikipedia.org/wiki/Race_and_ethnicity_in_the_United_States

[3]

# <black> Who did what?
Colin: Exploratory Data Analysis, Data Cleaning, Data Preprocessing, Data Visualization

Matthieu: Machine Learning

Hendrik: Fighting the confounders and implementing statistical tests

Jan: Creating the website and write the datastory
