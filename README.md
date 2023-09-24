# Unlocking the Pragmatics of Emoji: Evaluation of the Integration of Pragmatic Markers for Sarcasm detection


Emojis have become an integral element of online communications, serving as a powerful, under-utilised resource for enhancing pragmatic understanding in NLP. Previous works have highlighted their 
potential for improvement of more complex tasks such as the identification of figurative literary 
devices including sarcasm due to their role in conveying tone within text. However present state-of-the-art does not include the consideration of emoji or adequately address sarcastic markers such as 
sentiment incongruence.

This work aims to integrate these concepts to generate more robust solutions for sarcasm detection 
leveraging enhanced pragmatic features from both emoji and text tokens. This was achieved by 
establishing methodologies for sentiment feature extraction from emojis and a depth statistical 
evaluation of the features which characterise sarcastic text on Twitter. Current convention for 
generation of training data which implements weak-labelling using hashtags or keywords was 
evaluated against a human-annotated baseline; postulated validity concerns were verified where 
statistical evaluation found the content features deviated significantly from the baseline, highlighting 
potential validity concerns for many prominent works on the topic to date. Organic labelled sarcastic 
tweets containing emojis were crowd sourced by means of a survey to ensure valid outcomes for the 
sarcasm detection model. Given an established importance of both semantic and sentiment 
information, a novel sentiment-aware attention mechanism was constructed to enhance pattern 
recognition, balancing core features of sarcastic text: sentiment incongruence and context.

This work establishes a framework for emoji feature extraction; a key roadblock cited in literature for 
their use in NLP tasks. The proposed sarcasm detection pipeline successfully facilitates the task using 
a GRU neural network with sentiment-aware attention, at an accuracy of 73% and promising 
indications regarding model robustness as part of a framework which is easily scalable for the inclusion 
of any future emojis released. Both enhanced sentiment information to supplement context in 
addition to consideration of the emoji were found to improve outcomes for the task.
