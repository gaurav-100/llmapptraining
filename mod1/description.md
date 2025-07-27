This folder contains pre-requisites for basic LLM Chatbot.

# Generative AI for Beginners
This talks about basics of what Gen AI is, the development of how it came onto being.
It talks about how llm works breifly.

# [1hr Talk] Intro to Large Language Models
- This video contains information on LLMs.
- How it is trained? What stages are there and how it is done (Pretraining, Finetuning)
- Scaling laws of LLMs
- How LLM OS (ecosystem) kind of looks?
- Importance of context windows
- How LLMs work? It's interaction with other tools
- Glimpse of RAGs
- 2 system of way of thinking of LLMs

## LLM Security
- Jailbreak of models 
    = Directly asking questions like how to make napalm won't work. But if context is provided in a roundabout
    way it provides the solution.
    GPT is fooled due to ROLEPLAY.
    = There are many types of jailbreak attacks
    = Another example is asking data in base encoding rather than full english.
- Prompt Injection attack
- Data poisioning / Backdoor attacks (Sleeper agent attack)
....and many more attacks

# Exploring and comparing different LLMs
This part contains following information:
- Different types of LLMs in the current landscape
- Testing, iterating, and comparing different models
- How to deploy LLM

## Different types of LLMs
- They can have multiple categorisation based on,

    - architecture
    - training data
    - usecase

- Understanding these differences will help select the right model for the scenario, and understand how to test, iterate, and improve performance.

## Text, audio, video, and image generation
- Audio and speech recognition: Whisper type models
- Image generation: DALL-E and Midjourney are two very well-known choices
- Text generation: GPT3.5 to GPT4
- Multi-modality: To handle multiple types of data in input and output with models like gpt-4 turbo with vision or gpt-4o which are capable to combine natural language processing to visual understanding, enabling interactions through multi-modal interfaces

- Selecting a model means you get some basic capabilities, that might not be enough however. Often you have company specific data that you somehow need to tell the LLM about. There are a few different choices on how to approach that, more on that in the upcoming sections.

## Foundation Models versus LLMs
The term Foundation Model as an AI model should follow some criteria, such as,
- They are trained using **unsupervised learning** or **self-supervised learning**, meaning they are trained on unlabelled multi-modal data, and they do not require human annotation or labelling of data for their training purpose.
- They are very large models, based on very deep neural networks trained on billion of parameters
- They are normally intended to serve as a `foundation` for other models, meaning they can be used as a starting point for other models to be built on top of, which can be done by fine tuning.

![FMs and other categories](./.../images/foundation_models.png)