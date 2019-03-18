# MovieReviewRater

1. Number of Occurrence: The first test is an extension to the keyword algorithm we were asked to write. I tried to improve it by checking the number of occurrence of the keywords. I also recognize that if number of occurrence was checked in order to find keywords, the algorithm would have been better. Also, because pronouns, conjunctions and connectives come up a lot, it is important to disregard them (like articles) for this algorithm to work properly.

2. Length of review: I found out that “thrilling!” gets a much lesser score than “this is movie is very thrilling”, just because of the word-count in the review. So, to improve this, I added the second test to check the length of review, and if it is just one word, I increase the weight of its score.

3. Capitalization: If only the first letter is capital, it is a proper noun, and not very useful in judging if it a good or bad review, so I tried to lower the weight of its score. However, if all of the letters are capitalized, then the sentiment of the review is stronger than if it were not capitalized. For example, “AMAZING” has more positive sentiment than “amazing”, so I tried to increase the weight of words with all letters capitalized. However, this addition to the algorithm did not work well, and I cannot find my logic error. I would really appreciate it if you could let me know where my error is!


