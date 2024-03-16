# Project Name ---- WODDY 
(your agent for education and learning about mew words daily)

# uAgent WordsAPI Integrations Examples 
# Requirements
Our challenge today is to integrate WordsAPI with uAgents.

Woddy is a website which has two user base - !. Learner 2. Teacher
1. *Learner* can search any new word and its all around information about the word like syllable, pronunciation, synonyms, results(parts of speech, types of noun) and examples using that word. It can be randomly generated also.

2. *Teacher* assign daily tasks as a new word to learn along with all the features. the student have to answer it on own first and then match the real solution provided by the agents. This will provide them some daily points.




This repository contains examples of WordsAPI integrations using five agents: ` teacher_agent`, `student_agent` ,`random_word_agent` , `search_word_agent` and  `translate_agent`.

1. `teacher_agent`: This agent assign daily task in form of new words to the students. 

2. `Student_agent`: This agent helps student finding new words daily. This also helps with the pronunciation , syllables, results(part of speech , type of noun and examples) related to the given word.

3. `random_word_agent`: This agent generate randon words which are given as output to the `teacher_agent` (which he can assign) and   the generated word goes into the assigned word of the `Student_agent` .

4. `search_word_agent`: This agent searches any new word of user's choice and provide the informations(pronunciations, syllable , result, synonyms) related to the searched word. 

5. `gemma_agent`: This agent using `hugging_face_API` gives summary and in detail information about the word . 

6. `Translate_agent` : 

## Getting Started 🚀

To use these agents, follow the steps below:

### Step 1: Obtain API Keys 🔑

Before running the agents, you need to obtain the required API keys:
 `hugging_faceAPI` :  
 `rapidAPI` : 

#### WordsAPI

1. Visit the RapidAPI website: https://rapidapi.com/dpventures/api/wordsapi/
2. If you don't have an account, create one by signing up.
3. Once you are logged in, click on test endpoint and register for API on free-tier.
4. Once done you will see X-RapidAPI-Key in header parameter.


### Step 2: Set API Keys and address in agent scripts

1. Fill in the API Keys in the `random_word_agent` and `search_word_agent` scripts.
2. Fill in the API Keys in the `hugging_faceAPI` in the `gemma.py` file.

### Step 3: Run Project

To run the project and its agents:

```bash
cd src
python main.py 
```


#### features


#### Use cases


### Competitiors


### Future Scope


### Limitation


Now you have the agents up and running to perform a learning platform integrations using the provided APIs. Happy integrating! 🎉