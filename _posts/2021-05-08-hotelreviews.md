---
layout: post
title: Hotel Reviews
description: Text mining hotel reviews with NLTK in Python and tidytext in R.
image:
---


## Text Mining

### Summary
Can text mining hotel reviews give insight to what guests are saying about their experience?

In the travel industry, most hotel reservations are being booked online directly by the customer. Electronic word of mouth has been a prominent role in a customer’s decision on which hotel they should stay with. Hotel businesses are looking to online reviews to understand their customers’ desires and experiences with hotel stays to identify their areas of opportunities. Managers often seek a way to look at textual comments to know exactly what the guests are saying.

When looking at a corpus of reviews from different hotels across the United States, are there common themes that guests associate with a positive experience as well as thoughts that would lead to a negative experience? Are there words that associate together more than others to gain even further awareness? Do guests tend to have more positive reviews than negative, and do they say more with one vs. the other? These insights can be used to understand the hotel industry as a whole and where the focus should be to deliver a 5-star experience. Text mining using natural language processing can be used to extract words and themes to find positive and negative trends amongst numerous reviews. Managers can use this information for marketing, planning, and internal training.


### Tools
* R
* Python
* NLTK
* tidytext
* sklearn
* Pandas
* numpy
* Matplotlib
* igraph



### Project Preview

#### Exploratory Data Analysis
California had the most reviews in the corpus.

![Top States](/assets/images/reviews_top_states.jpg)

Average word and character count for positive and negative reviews:

|      | **Positive** | **Negative**|
|**Word Count** | 43 words | 64 words|
|**Character Count** | 239 characters | 339 characters |

#### Word Clouds
Word clouds of positive and negative reviews. The more the term occurred in the reviews, the larger the word appears.

![Positive Word Cloud](/assets/images/pos_word_cloud.jpg)
![Positive Word Cloud](/assets/images/neg_word_cloud.jpg)

#### BiGrams
BiGrams were created to find further insight to pairs of words that occurred frequently.

![Positive BiGrams](/assets/images/pos_bigrams.jpg)

![Negative BiGrams](/assets/images/neg_bigrams.jpg)

#### Word Networks

### The Complete Project
<section id="Repository">
	<div class="inner">
    <ul class="actions fit small">
      <li><a href="https://github.com/Torreylee1028/Hotel-Reviews" target="_blank" class="button small">View Repository</a></li>
    </ul>
	</div>
</section>
