# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|title|str|subreddit_scrape.csv, subreddit_scrape_2.csv, modeling.csv|title text of subreddit post|
|body|str|subreddit_scrape.csv, subreddit_scrape_2.csv, modeling.csv|body text of subreddit post|
|text|str|modeling.csv|column of combined subreddit post title and body text|
|score|int|subreddit_scrape.csv, subreddit_scrape_2.csv|post score, based on sum of upvotes and downvotes on reddit|
|comms_num|int|subreddit_scrape.csv, subreddit_scrape_2.csv|number of comments on subreddit post|
|created|datetime|subreddit_scrape.csv, subreddit_scrape_2.csv, modeling.csv|date and time post created on reddit|
|body_word_count|int|fdf_train_clean.csv, df_test_clean.csv|number of words in body of subreddit post|
|body_character_length|int|modeling.csv, additional_data.csv|number of characters in body of subreddit post|
|title_character_length|int|modeling.csv, additional_data.csv|number of characters in title of subreddit post|
|title_upper_case_ratio|float|modeling.csv, additional_data.csv|ratio of upper case characters to total number of characters in subreddit post|
|subreddit|str/int|subreddit_scrape.csv, subreddit_scrape_2.csv, modeling.csv, additional_data.csv, y_train.csv, y_test.csv|the class to be predicted; 0 for Unpopular Opinion and 1 for Change My View when one-hot encoded|
