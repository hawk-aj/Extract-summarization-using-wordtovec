# Extract Summarization
The program generates an extract summary of the given text by converting each sentence of the given text to vectors using a pretrained wordtovec model (representing each word as a 100 dimensional vector). The sentence similarity scores are then found using cosine similarity metric, after which pagerank algorithm is used to get importace ranking of the sentences. A summary with the first n(is set to 10 in the code) number of lines is generated at the end.

The gui was created using tkinter and presents a basic layout with two textboxes one for input and the other for presenting the summarized output.

*links and notes*

the pretrained glove word vector models 
http://nlp.stanford.edu/data/glove.6B.zip

word to vec explanation
https://www.youtube.com/watch?v=ERibwqs9p38&t=502s
