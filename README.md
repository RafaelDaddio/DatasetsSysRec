# Datasets for Content-Based Recommender Systems

The datasets here depicted are extensions from original RecSys datasets. These are extended with reviews processed by two Natural Language Processing toolkits, Babelfy [1] and Stanford's CoreNLP [2]. Beyond the ratings file, the datasets have the clean reviews, the Babelfy processed reviews and the CoreNLP processed reviews, all separated in folders. The review are grouped by item, and each file is named after the item's ID in the dataset

The Amazon Datasets were extracted from McAuley's website [3] which are derived from his work [4]. The movies datasets were obtained from MovieLens 100k [5] and HetRec 2011 MovieLens 2k [6], and are enriched with the top 10 user reviews (at the time) from IMDb.

# Information about Datasets:

- Amazon Apps: This dataset was filtered by leaving only users and items with at least 10 interactions. We have filtered out interactions with no user reviews. This results in: 16201 user, 4869 items and 264.048 interactions. If you use this dataset, please cite the original paper[4] and the following: Rafael M. D’Addio, Ronnie S. Marinho, Marcelo G. Manzato, Combining different metadata views for better recommendation accuracy, Information Systems, Volume 83, 2019, Pages 1-12. DOI: https://doi.org/10.1016/j.is.2019.01.008.
 
   Link: https://drive.google.com/file/d/1kXeoU7vgmYrsRQYKYTZFpgITJtEdPmE7/view?usp=sharing

- Amazon Cds and Vinyls: This dataset was filtered by leaving only users and items with at least 15 interactions. We have filtered out interactions with no user reviews. This results in: 5539 user, 6286 items and 220.868 interactions. If you use this dataset, please cite the original paper[4] and the following: Rafael M. D’Addio, Ronnie S. Marinho, Marcelo G. Manzato, Combining different metadata views for better recommendation accuracy, Information Systems, Volume 83, 2019, Pages 1-12. DOI: https://doi.org/10.1016/j.is.2019.01.008.

  Link: https://drive.google.com/file/d/1YMbtXfASmBY2IJu6klVVxWZ1bzLP2EJ5/view?usp=sharing

- MovieLens 100k: This dataset remains the same as the original, enriched with the top ten users reviews from IMDb. Sizes are 943 users and 1682 items, with 100.000 interactions. If you use this dataset, please reference the original dataset [5] and cite the following: Rafael M. D’Addio, Ronnie S. Marinho, Marcelo G. Manzato, Combining different metadata views for better recommendation accuracy, Information Systems, Volume 83, 2019, Pages 1-12. DOI: https://doi.org/10.1016/j.is.2019.01.008.

  Link: https://drive.google.com/file/d/1K-5o2EypVzfClOswhKeAsAZG4O0KLFkF/view?usp=sharing

- Hetrec MovieLens 2011 - 2k: In this dataset, we have mantained only movies from the years of 2000 until 2011 inclusive, resulting in XXX users, 1851 items and XXX interactions. We  enriched it with the top ten users reviews from IMDb. If you use this dataset, please reference the original dataset [6] and cite the following: Rafael M. D’Addio, Ronnie S. Marinho, Marcelo G. Manzato, Combining different metadata views for better recommendation accuracy, Information Systems, Volume 83, 2019, Pages 1-12. DOI: https://doi.org/10.1016/j.is.2019.01.008.

# References

[1] A. Moro, A. Raganato, R. Navigli. . Transactions of the Association for Computational Linguistics (TACL), 2, pp. 231-244, 2014.

[2] Manning, Christopher D., Surdeanu, Mihai, Bauer, John, Finkel, Jenny, Bethard, Steven J., and McClosky, David. 2014. The Stanford CoreNLP Natural Language Processing Toolkit In Proceedings of 52nd Annual Meeting of the Association for Computational Linguistics: System Demonstrations, pp. 55-60.

[3] The Amazon Review Datasets are originally available at: http://jmcauley.ucsd.edu/data/amazon/

[4] Julian McAuley, Christopher Targett, Qinfeng Shi, and Anton van den Hengel. 2015. Image-Based Recommendations on Styles and Substitutes. In Proceedings of the 38th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’15). Association for Computing Machinery, New York, NY, USA, 43–52. 

[5] The MovieLens 100k original dataset is available at: https://grouplens.org/datasets/movielens/100k/

[6] The HetRec 2011 Movielens 2k original dataset is available at: https://grouplens.org/datasets/hetrec-2011/
