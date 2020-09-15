# Fake-News-Detection
1. Dataset - We are using the G. McIntire. Fake and Real News Dataset, a quite large dataset and a balanced dataset that contains both fake stories and true news.
2. Stance estimates the relative perspective of two pieces of the text concerning a subject, argument, or issue. The stance calculation python code calculates the similarity score between the title of the articles and the text(body of the article).
Cosine distance is a good similarity measure as it determines the document similarity. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. 
3. The fake news detection system uses the content based information along with the calculated stance values. Our model makes use of BERT embeddings and deep learning algorithms like Recurrent Neural Networks and Convolutional Neural Networks.
