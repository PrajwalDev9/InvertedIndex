# InvertedIndex
Implemented a simple Inverted Index for document retrieval for the sample dataset collection with calucation for precision and recall value for top #10 ,top #50  and top #100 queries in collection

# For Execution:-

python Inverted_index.py <path_to_dataset> <path_to_query_file> <path_to_relevance_file>

Top 10 documents in rank list
Query: 1 Pr: 0.0 Re:0.0
Query: 2 Pr: 0.2 Re:0.13333333333333333
Query: 3 Pr: 0.2 Re:0.13333333333333333
Query: 4 Pr: 0.1 Re:0.05555555555555555
Query: 5 Pr: 0.1 Re:0.05263157894736842
Query: 6 Pr: 0.4 Re:0.2222222222222222
Query: 7 Pr: 0.6 Re:0.6666666666666666
Query: 8 Pr: 0.2 Re:0.5
Query: 9 Pr: 0.1 Re:0.125
Query: 10 Pr: 0.2 Re:0.08333333333333333
Avg precision: 0.21000000000000002
Avg recall: 0.19720760233918128
----------------------------------------------------------------
Top 50 documents in rank list
Query: 1 Pr: 0.0 Re:0.0 
Query: 2 Pr: 0.12 Re:0.4
Query: 3 Pr: 0.14 Re:0.4666666666666667 
Query: 4 Pr: 0.06 Re:0.16666666666666666
Query: 5 Pr: 0.14 Re:0.3684210526315789
Query: 6 Pr: 0.14 Re:0.3888888888888889
Query: 7 Pr: 0.16 Re:0.8888888888888888
Query: 8 Pr: 0.06 Re:0.75
Query: 9 Pr: 0.12 Re:0.75
Query: 10 Pr: 0.08 Re:0.16666666666666666
Avg precision: 0.10200000000000001
Avg recall: 0.4346198830409357
----------------------------------------------------------------
Top 100 documents in rank list
Query: 1 Pr: 0.0 Re:0.0
Query: 2 Pr: 0.09 Re:0.6
Query: 3 Pr: 0.09 Re:0.6
Query: 4 Pr: 0.06 Re:0.3333333333333333
Query: 5 Pr: 0.13 Re:0.6842105263157895
Query: 6 Pr: 0.09 Re:0.5
Query: 7 Pr: 0.09 Re:1.0
Query: 8 Pr: 0.03 Re:0.75
Query: 9 Pr: 0.06 Re:0.75
Query: 10 Pr: 0.04 Re:0.16666666666666666
Avg precision: 0.068
Avg recall: 0.5384210526315789
----------------------------------------------------------------




# List of Functionalities Implemented for Inverted Index Code:-
1. tokenize_and_remove_punctuations

2. get_stopwords

3. parse_data

4. remove_stop_words

5. read_data

6. calculate_tf

7. get_vocabulary

8. stem_words

9. preprocess_data

10. calculate_idf

11. calculate_tfidf

12. preprocecss_queries

13. calculate_tfidf_queries

14. generate_inverted_index

15. get_relevance

16. find_precision_recall
