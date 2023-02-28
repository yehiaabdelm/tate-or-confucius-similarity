# Tate or Confucius
<a href="http://tateorconfucius.com" target="_blank" rel="noopener noreferrer">![tateorconfucius.com](website.png)</a>
Visit <a href="http://tateorconfucius.com" target="_blank" rel="noopener noreferrer">Tate or Confucius</a> to play the quiz.

Because I built this in a weekend filenames are all over the place:
- 39.json: 39 Andrew Tate quotes from twitter
- 539_2022-11-30.json: 539 Andrew Tate quotes from twitter
- confucius.csv: All Confucius quotes
- file.json:
- quotes.json: Final quotes to be used in website
- similarity.csv: 158,593 observations where each observation is a
- tate-or-confucius.ipynb: Notebook used
- tate.csv: All Andrew Tate quotes
- tate_probs.csv: OpenAI codex model log probs

What is NOT in this repo: the code for the website which uses Vanilla JS and serverless functions for quote requests.

# Why
Because I can. No seriously, I felt a striking similarity (pun intended) between Andrew Tate's points and the Confucius quotes I would come across. So I just decided to build it.

# What I Used to Compare Quotes
I used the all-distilroberta-v1 model in the sentence-transformers package to compare the quotes (158,593 comparisons) and I took the quotes that were most similar. All available in the notebook. I also tried out making requests to OpenAI's codex where I gave the model a Tate quote and asked it if it thinks Confucius would have said it. This produced okay results so I just stuck with the first approach.

# References
All original.
