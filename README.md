# Master_thesis
The target audience for this repository is the group of people who are interested in science fiction on the Goodreads website, including readers, research scholars, and people in related fields.

Since the Goodreads website no longer provides an API, and it is impossible to access the full text of book reviews, we developed the following code. The code can be reused, just replace the url of science fiction. If you also want to get metadata and book reviews on the Goodreads website, the get_metadata.ipynb and get_reviews.ipynb in the repository can help you achieve this goal. However, as the web structure of the Goodreads website changes frequently, it is advisable to have some knowledge of web structure to better deal with these changes.

For sentiment analysis of book reviews, we used the book-reviews-sentiment model provided by Pianzola. This sentiment analysis model is based on the RoBERTa model, which is a pre-trained deep learning model. If you want to know more, you can refer to the following link: https://huggingface.co/fpianz/roberta-english-book-reviews-sentiment

We saved the output to a new csv file in the corresponding folder. You can find the corresponding data for each Jupyter Notebook in the zip.
