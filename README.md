# WIPOB
This project is called "What is Philosophy of Biology" (WIPOP). Is is part of my master's thesis in philosophy of science. In this master, one of my goal was to investigate the thematic diversity of philosophy of biology. Given that it is often the case that philosophy of biology of biology discribes itself as on a continuum with biology, I wanted to know if the thematics of the two endeavors matched, at least partially. 

Some previous results, notably Gayon (2009), Pradeu (2017) and Malaterre et al. (2021) looked at the thematic diversity of philosophy of biology through one main journal : _Biology and Philosophy_. Gayon and Pradeu classified manually all the articles. The categories in which they fall have been built iteratively. Malaterre leveraged well-known topic modeling algorithm _Latent Dirichilet Allocation_ (LDA). Howerver, given that Gayon and Pradeu results methodology attribute a unique theme per article and Malaterre with LDA tells us the probability to find a topic in a document which have many of them, the two analysis are hard to compare. 

Thus me decided to use a state of the art topic modeling algorithm : BERTopic (Grootendorst, 2022). With it, we were able to attribute a single theme by article, thus making our analysis comparable with the one of Pradeu, himself extending the previous work of Gayon. Moreover, we looked at the four major journals in philosophy of biology : 
| Journal                                                                 | Articles | References |
|-------------------------------------------------------------------------|----------|------------|
| BIOLOGY AND PHILOSOPHY                                                  | 1273     | 63647      |
| STUDIES IN HISTORY AND PHILOSOPHY OF SCIENCE PART C :STUDIES IN HISTORY AND PHILOSOPHY OF BIOLOGICAL AND BIOMEDICAL SCIENCES | 959      | 57651      |
| HISTORY AND PHILOSOPHY OF THE LIFE SCIENCES                             | 892      | 35108      |
| BIOLOGICAL THEORY                                                       | 607      | 34460      |

