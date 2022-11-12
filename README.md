# InvertedIndex
Implemented a simple Inverted Index for document retrieval for the sample dataset collection with calucation for precision and recall value for top #10 ,top #50  and top #100 queries in collection

# For Execution:-

python Inverted_index.py <path_to_dataset> <path_to_query_file> <path_to_relevance_file>

## Precision and Recall scores for queries
----------------------------------------------------------------
#### Top 10 documents in rank list<br>
Query: 1 &nbsp;&nbsp; Pr: 0.0 &nbsp;&nbsp; Re:0.0<br>
Query: 2 &nbsp;&nbsp; Pr: 0.2 &nbsp;&nbsp; Re:0.13333333333333333<br>
Query: 3 &nbsp;&nbsp; Pr: 0.2 &nbsp;&nbsp; Re:0.13333333333333333<br>
Query: 4 &nbsp;&nbsp; Pr: 0.1 &nbsp;&nbsp; Re:0.05555555555555555<br>
Query: 5 &nbsp;&nbsp; Pr: 0.1 &nbsp;&nbsp; Re:0.05263157894736842<br>
Query: 6 &nbsp;&nbsp; Pr: 0.4 &nbsp;&nbsp; Re:0.2222222222222222<br>
Query: 7 &nbsp;&nbsp; Pr: 0.6 &nbsp;&nbsp; Re:0.6666666666666666<br>
Query: 8 &nbsp;&nbsp; Pr: 0.2 &nbsp;&nbsp; Re:0.5<br>
Query: 9 &nbsp;&nbsp; Pr: 0.1 &nbsp;&nbsp; Re:0.125<br>
Query: 10 &nbsp;&nbsp; Pr: 0.2 &nbsp;&nbsp; Re:0.08333333333333333<br>
#### Avg precision: 0.21000000000000002
#### Avg recall: 0.19720760233918128
----------------------------------------------------------------
#### Top 50 documents in rank list
Query: 1 &nbsp;&nbsp; Pr: 0.0 &nbsp;&nbsp; Re:0.0<br> 
Query: 2 &nbsp;&nbsp; Pr: 0.12 &nbsp;&nbsp; Re:0.4<br>
Query: 3 &nbsp;&nbsp; Pr: 0.14 &nbsp;&nbsp; Re:0.4666666666666667<br> 
Query: 4 &nbsp;&nbsp; Pr: 0.06 &nbsp;&nbsp; Re:0.16666666666666666<br>
Query: 5 &nbsp;&nbsp; Pr: 0.14 &nbsp;&nbsp; Re:0.3684210526315789<br>
Query: 6 &nbsp;&nbsp; Pr: 0.14 &nbsp;&nbsp; Re:0.3888888888888889<br>
Query: 7 &nbsp;&nbsp; Pr: 0.16 &nbsp;&nbsp; Re:0.8888888888888888<br>
Query: 8 &nbsp;&nbsp; Pr: 0.06 &nbsp;&nbsp; Re:0.75<br>
Query: 9 &nbsp;&nbsp; Pr: 0.12 &nbsp;&nbsp; Re:0.75<br>
Query: 10 &nbsp;&nbsp; Pr: 0.08 &nbsp;&nbsp; Re:0.16666666666666666<br>
#### Avg precision: 0.10200000000000001
#### Avg recall: 0.4346198830409357
----------------------------------------------------------------
#### Top 100 documents in rank list
Query: 1 &nbsp;&nbsp; Pr: 0.0 &nbsp;&nbsp; Re:0.0<br>
Query: 2 &nbsp;&nbsp; Pr: 0.09 &nbsp;&nbsp; Re:0.6<br>
Query: 3 &nbsp;&nbsp; Pr: 0.09 &nbsp;&nbsp; Re:0.6<br>
Query: 4 &nbsp;&nbsp; Pr: 0.06 &nbsp;&nbsp; Re:0.3333333333333333<br>
Query: 5 &nbsp;&nbsp; Pr: 0.13 &nbsp;&nbsp; Re:0.6842105263157895<br>
Query: 6 &nbsp;&nbsp; Pr: 0.09 &nbsp;&nbsp; Re:0.5<br>
Query: 7 &nbsp;&nbsp; Pr: 0.09 &nbsp;&nbsp; Re:1.0<br>
Query: 8 &nbsp;&nbsp; Pr: 0.03 &nbsp;&nbsp; Re:0.75<br>
Query: 9 &nbsp;&nbsp; Pr: 0.06 &nbsp;&nbsp; Re:0.75<br>
Query: 10 &nbsp;&nbsp; Pr: 0.04 &nbsp;&nbsp; Re:0.16666666666666666<br>
#### Avg precision: 0.068
#### Avg recall: 0.5384210526315789


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
