# Applied Data Science @ Columbia
## Spring 2020
## Project 1: The truth behind the lyrics

<img src="figs/title.png" width="500">

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Spring 2020

+ Projec title: The truth behind the lyrics
+ This project is conducted by Jinxu Xiang

+ Project summary: This report shows the truth behind the lyrics by asking two questions: 
1. Is it true that most of music is positive? 
2. What kind of music is out of the ordinary?

+ To do this, first,I process the raw textual data 'lyrics.RData' saved in 'data' file by cleaning data, removing stopwords and creating a tidy version of texts which is saved in 'output' file. Then,I combine the processed text with artist information 'artists.csv' and saved the joint data in 'output' file. The 'Origin' column of joint data contains the name of city and country (or state in America). So I extracted the names of each reigon and saved it as 'Precessed_country'. Finally, I use shinyapp to help me quickly locate keywords and answer questions using wordcloud and statistical graphs.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
