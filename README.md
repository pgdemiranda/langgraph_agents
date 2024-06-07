01: ReAct: Reasoning and Acting in Language Models (paper de 2023)

O LLM pensa no que fazer e depois qual ação realizar. E esse padrão vai se repetindo.

Até certo ponto ele é bem manual, e daí vamos automatizar com Regex.

Tudo é construído utilizando apenas uma API que chama o LLM e um pouquinho de código em Python.

ReAct, which stands for Reasoning and Acting in Language Models, is a framework proposed by researchers to enhance the capabilities of language models (LMs) by incorporating reasoning and decision-making processes. Traditional language models, such as those based on neural networks like GPT (Generative Pre-trained Transformer), excel at generating coherent and contextually relevant text but often lack the ability to perform complex reasoning tasks or make decisions based on the generated content.

The ReAct framework aims to address this limitation by introducing mechanisms for:

    Reasoning: Enabling language models to perform logical reasoning and inferential processes, allowing them to understand and generate text with more structured and coherent reasoning.
    Acting: Empowering language models to take actions based on the generated content, allowing them to interact with environments or systems, make decisions, and perform tasks beyond text generation.

By integrating reasoning and acting capabilities into language models, ReAct seeks to push the boundaries of what LMs can accomplish, potentially leading to more versatile and intelligent AI systems capable of engaging in more sophisticated interactions and problem-solving tasks.

It's worth noting that ReAct is a research framework, and its implementation and effectiveness may vary depending on the specific language model architecture and the tasks it's applied to.

https://til.simonwillison.net/llms/python-react-pattern


### Models Used:
OpenAI:
 - gpt-3.5, gpt-4o
 - tavily search tool