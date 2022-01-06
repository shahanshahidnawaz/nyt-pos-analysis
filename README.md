# nyt-pos-analysis
Analysis of parts of speech between headlines and an article's preview text as both appear on the New York Times print frontpage

This code uses data from 42 several New York Times print front pages from October-December 2021 to ascertain if there are lexical differences between a story's headline and its preview text. I use the NLTK library to determine the frequency of various Parts of Speech in headlines and preview text and find that plural nouns, singular nouns, and singular verbs appear more frequently in headlines than they do in an article's front page preview, at the 95% confidence level.

This result, then, supports the idea that headlines are a unique lexical form likely because they are one of the first elements in a print newspaper a reader interacts with and so their purpose is to capture a reader's attention (while normal text, on the other hand, can afford to be more normal since "information scent" has already been disseminated).