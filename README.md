### Data Source (raw): [https://nijianmo.github.io/amazon/index.html](https://nijianmo.github.io/amazon/index.html)
<br>

### **<ins>Libraries</ins>**

* Pandas
* itertools
* NLTK (Natural Language Toolkit)
    * Punkt
    * Stopwords
    * Vader_lexicon
    * Word_tokenize
    * Bigrams
    * Sentiment
        * Vader
            * SentimentIntensityAnalyzer
    * corpus
        * Stopwords
    * probability
        * FreqDist
* Seaborn
* Matplotlib
    * Pyplot
* NetworkX
    * Drawing
        * Nx_pydot
            * Graphviz_layout
* WordCloud
* plotly
    * Express
    * io

<br>

### **<ins>Dataset</ins>**
1) **Raw Review Data**

 | **Variables** | **Data Types** | **Desciption** |
 | --------- | ---------- | ---------- |
 | overall | int | rating score (1-5) |
 | verified | bool | verify account (True/False) |
 | reviewTime | object | review's posting timestamp |
 | reviewerID | object | ID of reviewer |
 | asin | object | Amazon Standard ID Number |
 | reviewerName | object | name of reviewer |
 | reviewText | object | individual opinions on each product |
 | summary | object | short review |
 | unixReviewTime | int | timestamp in seconds since 1970 (unix time) |
 | vote | object | helpful votes of the review |
 | style | object | Product dictionary, e.g. Format, Hardcover |
 | image | object | images that customers post after they have received the product |

2) **Metadata**
   
 | **Variables** | **Data Types** | **Desciption** |
 | --------- | ---------- | ---------- |
 | category | object | list of categories the product belongs to |
 | tech1 | object | the first technical detail table of the product |
 | description | object | product description |
 | fit | object | product fit |
 | title | object | product name |
 | also_buy | object | the product name that customers also purchase |
 | tech2 | object | the second technical detail table of the product |
 | brand | object | brand name |
 | feature | object | bullet-point format features of the product |
 | rank | object | product rank |
 | also_view | object | the product name that customers also view |
 | main_cat | object | main category |
 | similar_item | object | products similar to the ones purchased |
 | date | object | product posting date |
 | price | object | product price |
 | asin | object | Amazon Standard ID Number |
 | imageURL | object | url of the product image |
 | imageURLHighRes | object | url of the high resolution product image |
 | details | object | product detail |

