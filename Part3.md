# MSDS459-Week-3.-Individual-Assignment-1

Part 3 - Week 3 - Knowledge Graphs

For week 3, we went back one chapter in the textbook to chapter four.  Chapter four in the textbook introduces the concept of Information Extraction and covers Named Entity Recognition (NER). According to Nlpblogs (2025), named entity recognition is the tagging and extraction process of entities from data contained within text.

According to Kejriwal et al. (2021), early versions of NER were typically constructed with rules based algorithms.  Systems have since improved and become less manual.  Most approaches rely on a similar pipeline approach to preprocessing information into information the system can understand.  The processes include steps like sentence fragmentation, tokenization, tagging, embedding, and classification (Kejriwal et al., 2021).

Key to this process are the concepts of tokenization and syntactic analysis.  Tokenization is the process of separating out words or groups of words in the text into identifiable and more repeatable entities referred to as tokens.  While tokenization seeks to parse entities within the text, syntactic analysis is the process of identifying the relationships between these entities.  One such approach is linguistic tagging.  This process tags words according to their part of speech and relationship to the rest of the sentence to garner meaning Kejriwal et al. (2021).

While original approaches to NER were manually constructed algorithms, more sophisticated approaches have since been developed.  These can be supervised, semi-supervised, or unsupervised.  As the names imply, these are increasing levels of autonomy on the part of the NER system.  Often the most sophisticated supervised approaches require large volumes of training data to understand entities in the text and their relationships to one another.  While semi-supervised approaches require less upfront training data, the often require the user to intervene periodically to tag entities or provide additional increments of training data.  While unsupervised may work a given task without direction, the model has often been pre-trained on other data.  These approaches often employ deep learning approaches such as neural networks (Kejriwal et al., 2021).

One type of neural network often employed is referred to as a recurrent neural network or RNN.  An RNN will loop repeatedly over a set of training data to develop a model that can be applied to subsequent data.  Each loop utilizes various layers to process the data such as Long Short-Term Memory or LSTM.  As each loop occurs, it passes a message or learning on to the next one.  The system therefore learns over the repeated loops (Kejriwal et al., 2021).


References

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. Knowledge graphs: Fundamentals, techniques, and applications. Cambridge, MA: The MIT Press, 2021.

Nlpblogs. “Beginner’s Guide: Named Entity Recognition (NER) (Part 2).” Medium, February 10, 2025. https://python.plainenglish.io/beginners-guide-named-entity-recognition-ner-part-2-181b5432602f.
