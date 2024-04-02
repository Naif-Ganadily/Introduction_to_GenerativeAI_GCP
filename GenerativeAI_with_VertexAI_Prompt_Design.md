## What you will learn:

### How to get started with prompt engineering with the Vertex AI SDK:
- Best practices
- Zero-, one- and few-shot prompting

### How to explore some text generation use cases with the Vertex AI SDK:
- Ideation
- Q&A
- Text classification
- Text extraction
- Text summarization


#### How to reduce hallucinations? 
There is one possible method called the Determine Appropriate Response (DARE) prompt, which cleverly uses the LLM itself to decide whether it should answer a question based on what its mission is.


#### Choosing between zero-shot, one-shot, few-shot prompting methods
Which prompt technique to use will solely depends on your goal. The zero-shot prompts are more open-ended and can give you creative answers, while one-shot and few-shot prompts teach the model how to behave so you can get more predictable answers that are consistent with the examples provided.

The Main Notebook:
[Link to the Notebook for the Lab on Introduction to prompt design](intro_prompt_design.ipynb)

Notebook Examples with different methods:
- There seems to be a problem with the modules/ libraries I assume they are not upto date and due to the lab 1 hour and 30 minutes to complete I did not have the time to fix it: TODO [Link to the Notebook for chain of thought](generativeai_with_vertexai_prompt_design\chain_of_thought_react.ipynb) 
- This one is straightforward showcasing how LLMs in this sense PaLM can generate new ideas [Link to the Notebook called ideation](generativeai_with_vertexai_prompt_design\ideation.ipynb) 
- This one is a interesting one on the open domain and closed domain Q&A applications where using your own closed domain data is important for use-cases [Link to the Notebook on question_answering](generativeai_with_vertexai_prompt_design\question_answering.ipynb) 
- This one is pretty much all the types of classification you can think of Generative AI can classify them with ease [Link to the Notebook on text_classification](generativeai_with_vertexai_prompt_design\text_classification.ipynb) 
- Extremely well in extracting all types of text extractions (Straightforward) [Link to the Notebook on text_extraction](generativeai_with_vertexai_prompt_design\text_extraction.ipynb) 
- This one is extremely important due to the metric they introduce called "ROUGE" The measures count the number of overlapping units such as n-gram, word sequences, and word pairs between the computer-generated summary to be evaluated and the ideal summaries created by humans. [Link to the Notebook on text_summarization](generativeai_with_vertexai_prompt_design\text_summarization.ipynb) 
