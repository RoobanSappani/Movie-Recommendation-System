# Movie-Recommendation-System
A movie recommendation system built on c++.

Content based recommendation system implemented in C++ with a modified version of the IMDB dataset.
The dataset consisted of various NULL values, corrupted values etc. So we used the cleaned data.

Data structures: Bloom filters for information retrieval, BK trees for checking in o(1), linked list.

Algorithms: Dynamic levenshtein algorithm for movie search suggestion and recommendation, FNV and Murmurhash3 to construct the bloom filters.
