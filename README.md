# GESIS: topic modeling in R

Welcome to the 2020 GESIS workshop on Topic Modeling.
This page will be used to distribute the slides, handouts, and other materials for this course.
All material is free to re-use under the [CC-BY](LICENCE.md) license.

## Preparation

For this workshop, we expect you to have R and RStudio installed, and have basic working experience with R.
If you are new to R, we have several videos and tutorial on our [R course material GitHub page](https://github.com/ccs-amsterdam/r-course-material) to help you get started.
The [Getting started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md) tutorial walks you through the installation, and helps you get some first hands-on experience. 
To become more familiar with R, please first watch the [Fun with R](https://www.youtube.com/watch?v=eYCV8kIsgGs&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=2) and [Intro to R](https://www.youtube.com/watch?v=PVhZD5MINYM&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=1) videos. 

Then, to become more proficient in R yourself, please complete some (or all) of the handouts in the [Data wrangling and visualization in the tidyverse](tidyverse.md) background material.
A strong understanding of the `tidyverse` is not required for this workshop, but completing these tutorials is a good and productive way to become used to working with R and RStudio.
As a bonus, the techniques discussed in these tutorials are among the most useful data science skills (though for text analysis we'll need other techniques, that will be covered in this workshop).

## Daily routine:

We have two three-hour sessions per day. Each session has the following routine:

1. 1 hour: Introductory video (asynchonous)
2. 30 min: Interactive Q&A (plenary zoom) 
3. 1 hour: Supervised practice session (zoom breakout rooms)
4. 30 min: Wrap-up Q&A (plenary zoom) 

Note that due to the asynchronous and practise session components we do not plan coffee breaks, but please make sure to drink plenty of coffee and to snack.

During the practice sessions, you have a choice of:
 - Working on the handouts. These mostly cover the same material as the videos, so if everything is clear you don't need to spend too much time on them
 - Working on your own data. If you have textual data that is relevant to your own research, we recommend (and can help with) using this data to practice the techniques covered in this workshop.
 - Expanding on the handouts. There are many choices that you can make at various steps in the analysis process (e.g., preprocessing, hyperparameters), and it's important to learn how these choices affect your results. Try changing parts of the code to see what happens.


## Schedule and materials
  
### Wednesday
+ **AM session: Quantitative text Analysis with Quanteda**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 10 and 11
    + [Welbers, Atteveldt & Benoit (2017, CMM) Text Analysis using R](http://vanatteveldt.com/p/welbers-text-r.pdf) 
    + [Grimmer & Stewart (2013, PA) Text as Data](http://www.collingwoodresearch.com/uploads/8/3/6/0/8360930)
  + 9:00: Introductory video
    + [Quantitative Text Analysis](https://www.youtube.com/watch?v=O6CGXnxPHok&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=1)
    + [Advanced preprocessing](https://www.youtube.com/watch?v=tQoCjVat6UE&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=2)
    + [Demo: Corpus Statistics](https://www.youtube.com/watch?v=7z7U7ORFWQM&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=3) 
  + 10:00: Plenary session / Q&A
  + 10:30: Supervised practice 
    + [Quantitative Text Analysis](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_3_quanteda.md)
    + [Basic String Handling](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-14-strings.md)
  + 11:30 - 12:00: Plenary session / Q&A
+ **PM session: Dictionary analysis and Sentiment Analysis**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 11 and 12.1
    + [Van Atteveldt, Velden & Boukes (2020), Automatic Sentiment Analysis](http://vanatteveldt.com/wp-content/uploads/atteveldt_sentiment.pdf) *(Under review - please do not distribute)*
  + 13:00: Introductory video
    + [Analysing Text](https://www.youtube.com/watch?v=bHa2CClBYFw&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=4)
    + [Demo: Sentiment Analysis](https://www.youtube.com/watch?v=U0l5GB0i3uU&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=5)
  + 14:00: Plenary session / Q&A
  + 14:30: Supervised practice 
    + [Lexical Sentiment Analysis](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/sentiment_analysis.md)
  + 15:30 - 16:00: Plenary session / Q&A
+ **Additional material**
  + [Video: dealing with textual data](https://www.youtube.com/watch?v=ofOJiuaHV2w&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=8), 
  + [NLP preprocessing in R](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_nlp.md)
  + [Scraping with rvest](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/rvest.md)

### Thursday
+ **AM session: LDA topic modeling**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 12.3
    + [Chang et al. (2009) Reading Tea Leaves: How Humans Interpret Topic Models](https://papers.nips.cc/paper/3700-reading-tea-leaves-how-humans-interpret-topic-models)
  + 9:00: Introductory video
    + [Topic Modeling with LDA](https://www.youtube.com/playlist?list=PLjXODJ_lGN_WtxhPsQ_t0aHtFAcsIh1-8) videos 1-3 (introduction, example, and fitting topic models in R)
  + 10:00: Plenary session / Q&A
  + 10:30: Supervised practice 
    + [LDA topic modeling](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_lda.md)
    + [Creating a topic browser](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_topicbrowser.md)
  + 11:30 - 12:00: Plenary session / Q&A
+ **PM session: Technical details**
  + 13:00: Introductory video
    + [Topic Modeling with LDA](https://www.youtube.com/playlist?list=PLjXODJ_lGN_WtxhPsQ_t0aHtFAcsIh1-8)  videos 4-6 (dimensionality reduction, dirichlet distribution, estimating parameters)
  + 14:00: Plenary session / Q&A
  + 14:30: Supervised practice
      + Play around more with LDA (possibly using your own data)
      + Do some of the following tutorials to get a deeper understanding of LDA.
        + [Gibbs sampling DIY](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/gibbs.R)
        + [Choosing the number of topics](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_LDA_perplexity.md)
        + [Visualize Gibbs iterations](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/gibbs_animate.R)
        + [Understanding the alpha parameter](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/understanding_alpha.md)
        + [Singular value decomposition](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/SVD.md)
    + 15:30 - 16:00: Plenary session / Q&A
  
  
### Friday
+ **AM session: Structural Topic Models (STM)**
  + Preparation / background reading:
    + [Structural Topic Modeling Vignette](https://github.com/bstewart/stm/blob/master/vignettes/stmVignette.pdf?raw=true) (see also [www.structuraltopicmodel.com](http://www.structuraltopicmodel.com))
  + 9:00: Introductory video
    + [Variants of Topic Models](https://www.youtube.com/watch?v=3rqkSqKp85s&list=PLjXODJ_lGN_U02yQyZG5YpBgseVpiS9s2&index=2&t=0s) [Structural Topic Models](https://www.youtube.com/watch?v=37yvQdQw5j8&list=PLjXODJ_lGN_U02yQyZG5YpBgseVpiS9s2&index=2)
  + 10:00: Plenary session / Q&A
  + 10:30: Supervised practice 
    + [STM quick start](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_stm.md)
    + [STM vignette](https://cran.r-project.org/web/packages/stm/vignettes/stmVignette.pdf)
  + 11:30 - 12:00: Plenary session / Q&A
+ **PM session: Supervised Machine learning**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 9 and 12.2
    + [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/), esp. [chapter 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf)
    + [Neural Network Methods in NLP](https://www.amazon.nl/Network-Methods-Natural-Language-Processing/dp/1627052984) (really nice and relatively readable intro to deep learnign)
    + [Foundations of Statistical NLP](https://www.amazon.com/exec/obidos/ASIN/0262133601) (old but still good background)
  + 13:00: Introductory video
    + [Coming soon]
  + 14:00: Plenary session / Q&A
  + 14:30: Supervised practice
    + [Supervised machine learning in R](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_ml.md)
  + 15:30 - 16:00: Plenary session / Q&A
+ **Additional material**
  + [caret vignette](https://cran.r-project.org/web/packages/caret/vignettes/caret.html)
  + [3Blue1Brown video series on neural networks](https://www.3blue1brown.com/neural-networks)


 
 
