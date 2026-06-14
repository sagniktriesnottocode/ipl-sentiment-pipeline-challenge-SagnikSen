# ipl-sentiment-pipeline-challenge- SagnikSen

This project is made as the final submission of the SAAI Research Internship. This basic ML Model detects sentiments based on English and Hinglish comments. At scale, this data can provide to be crucial for brand identity creation, Analysing public sentiments, etc.

The approach was simple: create a Model which uses the simplest complexity of vectorizers and classifiers, so that the model can run locally even on a potato PC. We looked at several cases, including:
  1. Widespread use of Hinglish in the tweets
  2. Sarcasm used in the tweets

To address these issues, I first identified 5 vectorizers and 7 classifiers and trained an 80 Row labeled dataset. After eliminating a few combinations, i narrowed it down to 16 different pipelines and trained each pipeline on a 300-row, relatively more diverse, dataset.

The result: Found 7 combinations with a performance score of a perfect 100.
            Found 3 combinations with a final score of more than 99%

However, even the best model has a few problems, mentioned in error analysis.

To run this locally on your pc, download the notebook, run it on jupyter notebook or google colab(best option). Go to the last line of the cell. Type in a sample statement and you should ideally get a sufficing prediction
You can try the demo pickle file too!
