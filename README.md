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


## References
1. Gayon, J. (2009). *Philosophy of Biology: An Historico-Critical Characterization*. In A. Brenner & J. Gayon (Eds.), *French Studies in the Philosophy of Science: Contemporary Research in France* (pp. 201-212). Springer Netherlands. [DOI](https://doi.org/10.1007/978-1-4020-9368-5_9)  
   <cite>https://doi.org/10.1007/978-1-4020-9368-5_9</cite>

2. Grootendorst, M. (2022, March 11). *BERTopic: Neural Topic Modeling with a Class-Based TF-IDF Procedure*. arXiv. [DOI](https://doi.org/10.48550/arXiv.2203.05794)  
   <cite>https://doi.org/10.48550/arXiv.2203.05794</cite>

3. Malaterre, C., Chartier, J.-F., & Pulizzotto, D. (2019). *What Is This Thing Called Philosophy of Science? A Computational Topic-Modeling Perspective, 1934–2015*. HOPOS: The Journal of the International Society for the History of Philosophy of Science, 9(2), 215-249. [DOI](https://doi.org/10.1086/704372)  
   <cite>https://doi.org/10.1086/704372</cite>

4. Pradeu, T. (2017). *Thirty Years of Biology & Philosophy: Philosophy of Which Biology?* Biology & Philosophy, 32(2), 149-167. [DOI](https://doi.org/10.1007/s10539-016-9558-7)  
   <cite>https://doi.org/10.1007/s10539-016-9558-7</cite>

