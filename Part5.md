# MSDS459-Week-3.-Individual-Assignment-1

Part 5 - Week 2 - Natural Language Processing in Action, Second Edition

For week 2, chapter 11 of this text was assigned.  This chapter covers using tokenization and part of speech labeling to generate understanding of real-world topics than can be stored in a knowledge graph for artificial intelligence systems to utilize.  A knowledge graph is a database where information is stored as the entities and relationships between those entities.  These relationships are referred to as edges while the entities are referred to as nodes (Kejriwal et al., 2021).

Kejriwal et al. (2021) suggests utilizing a knowledge graph to store the core facts you expect a large language model to reference.  The intent of this method is to ground the LLM in a given set of true facts about its main topic area.  This grounding helps to increase the accuracy of the LLM's responses and reduce the chance of hallucinations.  This can be especially helpful when users ask the model to explain its reasoning or where it obtained knowledge from.  Since most LLMs will attempt to answer a clarifying question whether it has the answer or not, successive probing queries without some grounding set of truths tend to result in nonsensical or fabricated information (Kejriwal et al., 2021).  While this could be helpful if asking an LLM to creatively write a story, it’s not a desirable behavior for it to make up responses to queries relating to factual information.

According to Kejriwal et al. (2021), one of the first steps toward information extraction is segmentation.  Segmentation is the act of dividing a long document into cohesive sections about particular topics.  One common approach is segmention based upon sentences.  However, simply splitting a document up at punctuation such as ., ?, and ! can lead to some unexpected results when the text includes quotes or technical data.  The authors of the text recommend either using regular expressions in combination with the split function or utilizing Spacy.  Spacy can be quite a bit heavier but more accurate.  They therefore recommend to use regular expressions or experiment with deactivating a portion of the pipeline for Spacy when working with larger datasets (Kejriwal et al., 2021).

One of the keys to an LLM's deeper understanding of text is Coreference Resolution.  Once text has been segmented and tokenized there are often multiple tokens that refer to the same entity.  Resolving these duplicates and reduce the complexity of a Knowledge Graph and therefore increase an LLM's understanding of the underlying meaning (Kejriwal et al., 2021).

Another pair of keys to an LLM's deeper understanding are dependency parsing and constituency parsing.  Dependency parsing allows a system to diagram sentences of text into their parts of speech and relationships.  This deeper understanding of not just what items are related but in what way allows an LLM to build deeper understanding.  Constituency parsing is the process of identifying sub phrases.  This allows the system to recognize phrases that may represent an entity rather than single words or tokens.


References

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. Knowledge graphs: Fundamentals, techniques, and applications. Cambridge, MA: The MIT Press, 2021.
