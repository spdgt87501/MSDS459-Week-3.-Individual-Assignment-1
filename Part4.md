# MSDS459-Week-3.-Individual-Assignment-1

Part 4 - Week 1 - Natural Language Processing in Action, Second Edition

For week 1, chapter 10 of this text was assigned.  This chapter provided an overview of utilizing Large Language Models (LLM) in a more effective manner.  According to Howard et al. (2025) the goal of this review was to achieve intelligent use of such systems rather than just appearing intelligent.

These models may appear intelligent due to their seemingly well-reasoned answers but what they are actually doing is using probabilities to generate the next token in a sequence.  While general large language models can be applied to specialized content, fine tuning and experimentation are often required to produce higher quality responses.  While LLMs often answer basic questions accurately, more complex questions requiring reasoning can cause them to provide erroneous answers.  It’s also possible push many of these models into what are called hallucinations where the model provides nonsensical and toxic answers (Howard et al., 2025).

According to Howard et al. (2025), there are four popular approaches to reducing the frequency with which an LLM would provide nonsensical or toxic responses.  The first of these methods is called Scaling.  Scaling simply refers to making the model larger by feeding it more information.  There is some debate as to the effectiveness of this methodology.  Companies such as Google and Open AI have trained their models on extremely large amounts of data utilizing trillions of parameters.  Such models require an inordinate amount of processing power to compile with diminishing returns (Howard et al., 2025).

The second method is called Guardrails.  This method entails monitoring resulting answers from the model to find hallucinations or toxic responses (Howard et al., 2025).  Howard et al. (2025) cautions against asking the LLM itself to judge its own responses for appropriateness.  The authors also cover another option called guardrails AI.  However, this option simply augments the prompt being sent to the LLM rather than filtering the output.  Dhinakaran (2023), provides an overview of guardrails AI works in greater detail.  Guardrails essentiallty provides a wrapper around LLM API calls utilizing the RAIL specification.  This allows each prompt to the LLM to be expanded upon or self filtered by the LLM itself based on criteria set by the programer.  For example, it could be set to ask the LLM if the SQL code it provided as a response to a prompt was valid and then ask it to try again based on the response.  In this case it wouldn't provide a response to the end user until the LLM had self-verified that the code was valid.  Due to this being essentially the LLM judging its own responses, Howard et al. (2025) instead recommends using a system like Spacy Matcher.  

Third is Grounding.  This process uses facts to augment an LLM's understanding.  This can entail tagging information from some sources as more reliable than others so that the model knows what data to trust (Howard et al., 2025).  The final method suggested by Howard et al. (2025) is Retrieval.  This method entails utilizing a traditional internet search engine to locate web pages that can be utilized in generating the LLM's responses (Howard et al., 2025).


References

Dhinakaran, Aparna. “Safeguarding Llms with Guardrails.” Medium, August 30, 2024. https://medium.com/data-science/safeguarding-llms-with-guardrails-4f5d9f57cff2. 

Howard, Cole, Maria Dyshel, Hobson Lane, and Hannes Hapke. Natural language processing in action, Second edition. Manning Publications, 2025. 
