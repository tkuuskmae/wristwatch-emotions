# GoEmotions experiment using wristwatch narratives

* This experiment is described in the blog post ["Memories of wristwatches: the emotional measurement"](http://www.mindthemeaning.com/kuukiri-est/2023/8/31/malestusi-kaekelladest-est)
* It compares the results of 5 personal narratives about wristwatches and the official descriptions of these watches from the homepages of the producers
* The experiment uses the Google's ["GoEmotions"](https://blog.research.google/2021/10/goemotions-dataset-for-fine-grained.html) colab
* The hypothesis was that the emotional spectrum should differ between the personal and official stories
* However, the results of the test indicate that the problem might be trickier than initially thought as some of the spectres have perfect match
* As no Google compute credits were used during the experiment, the method was trained with one epoch only
* All the results have been normalized to the second decimal place
* The test data with references is accessible in the ["corpus.txt"](https://github.com/tkuuskmae/wristwatch-emotions/blob/master/corpus.txt)

--------------------

## Results

####Zodiac Sea Wolf

| Personal memory    | Official description |
| -------- | ------- |
| approval: 0.42  | curiosity: 0.42 |
| desire: 0.42 | annoyance: 0.42 |
| disapproval: 0.42 |     |


####Vulcain Cricket

| Personal memory    | Official description |
| -------- | ------- |
| admiration: 0.63  | gratitude: 0.81 |
| curiosity: 0.43 | disgust: 0.63 |
| approval: 0.42 | confusion: 0.58 |

####Tudor Submariner (since traded for a Rolex GMT)

| Personal memory    | Official description |
| -------- | ------- |
| approval: 0.42  | neutral: 0.51 |
| annoyance: 0.42 | annoyance: 0.42 |
| sadness: 0.42 | approval: 0.42 |

####Seiko SKX

| Personal memory    | Official description |
| -------- | ------- |
| neutral: 0.45  | neutral: 0.49 |
| annoyance: 0.42 | annoyance: 0.42 |
| disapproval: 0.49 | disapproval: 0.42 |

####Hamilton Neil

| Personal memory    | Official description |
| -------- | ------- |
| neutral: 0.47  | neutral: 0.47 |
| approval: 0.42 | approval: 0.42 |
| annoyance: 0.42 | annoyance: 0.42 |

