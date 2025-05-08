# AI-optimized art museum labels at Galleria Sabauda, Turin Royal Museums

This experiment examines how Large Language Models (LLMs) can be applied to optimize art museum labels to meet specific cultural accessibility needs and ministerial guidelines and best practices in matters of exhibit texts redaction. The paper  illustrates the first results of an experiment on optimizing the current labels of the Flemish section of the Galleria Sabauda in Turin. 
The study tests three state-of-art- LLMs, GPT4.o mini, Claude 3.7 and DeepSeek V-3, according to three different few-shot prompting techniques and provides an evaluation grid is to assess the performance of LLMs in this rewriting task considering both content optimization and readability and formatting aspects.

In this repository you can find:
* current original labels displayed in the Flemish section of Galleria Sabauda.
* prompts: all prompts employed for each artwork's label optimization with 3 techniques employed - 0-shot prompting, 1-shot prompting and 1-annotated shot prompting. Moreover, in this folder you can fin also the two human-optimized examples employed for few-shot techniques.
* all tests results: a  csv table with all models'answers for each optimization of artworks' labels correlated with prompt, model, technique used and datetime.
* a folder on Evalutation phase with evaluation grid template, instruction to evaluate, all evaluations and analysis of results


## Case-study
This case-study concerns the interpreative labels of the following artworks preserved in the Flemish section of Galleria Sabauda.
* Peter Paul Rubens, Susanna and the Elders, 1628.
* Peter Paul Rubens, Hercules in the Garden of the Hesperides, post 1638.
* Peter Paul Rubens, Deianira Tempted by Fury 
* Antoon Van Dyck, The Children of Charles I of England, 1635.
* Antoon Van Dyck, Equestrian Portrait of Prince Thomas of Savoy-Carignano, 1634.


