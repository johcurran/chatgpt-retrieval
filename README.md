# chatgpt-retrieval

Simple script to use ChatGPT on your own files.

Here's the [YouTube Video](https://youtu.be/9AXP7tCI9PI).

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own data into `data/data.txt`.

## Example usage
Test reading `data/data.txt` file.
```
> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```

Test reading `data/cat.pdf` file.
```
> python chatgpt.py "what is my cat's name"
Your cat's name is Muffy.
```
## Addtional Note
- `blog LangChain` [link](https://blog.langchain.dev/retrieval/)
- `Python LangChain Docs` [link](https://python.langchain.com/docs/modules/data_connection/)
- `LangChain Docs` [link](https://www.langchain.com/)
- `Vector Embedding Tutorial` [link](https://www.youtube.com/watch?v=yfHHvmaMkcA)
- `freeCodeCamp` [link](https://www.youtube.com/@freecodecamp)
- `LangChain Crash Course` [link](https://www.youtube.com/watch?v=lG7Uxts9SXs)
- `Vector Search RAG Tutorial` [link](https://www.youtube.com/watch?v=JEBDfGqrAUA)
- `What is Retrieval Augmented Generation` [link](https://www.youtube.com/watch?v=T-D1OfcDW1M)

