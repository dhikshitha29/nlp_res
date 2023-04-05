#ABSTRACT :
	JOBSY focuses on building a bidirectional resume helper that helps both the recruiters and the applicants to simplify the hiring process.
Starting with how it helps the recruiter , a UI based parser and scorer is built that accepts the resumes from the different users in the pdf format. It then parses the contents of the resume and creates a database based on the information extracted from the resumes. Python libraries namely Genesim, SpaCy and pattern matching are used to extract the similar words, identify the named entities and to return words that matched a specific pattern (e.g. Phone numbers). Given a JD (Job description), resumes are ranked depending upon the scores calculated from bigram and Word2Vec models. Further, the results of the scoring of the resumes are then shown graphically along with the candidate's name and skills that match the JD. Additionally, resume classification is performed on a labeled dataset using two algorithms namely Naive Bayes and BERT . 
Finally, a chatbot is built based on the GPT3 algorithm. This chatbot is employed to generate a cover letter based on the user's responses to the queries posed by the chatbot. Further, both the websites are developed using the Python Streamlit library.


To run : streamlit run app.py
