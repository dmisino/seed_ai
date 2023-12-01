# seed_ai
Using language models to generate, execute and improve code in an iterative evolutionary loop

## Idea

"Seed AI" as a concept is a hypothetical form of artificial intelligence capable of recursive self-improvement. Starting from a relatively simple level, it redesigns itself to become more intelligent, with the process continuing exponentially.

So, I'm not building that. I did however want to explore what I could achieve by hooking up current language models to a system that can generate, execute, evaluate and improve code in an iterative loop, given some goal. 

There are many key functionalities required for this. Some of them I have an idea how they could work. Others will require some experimentation. My initial attempt will be to create a system that requires only a broad goal as input, with the rest filled in by AI, including things such as:

- Specific goal driven outputs
- Testing and evaluation criteria
- Evolutionary parameters to adjust for each generation

And so forth. As I encounter technical realities that require me to narrow the scope or rethink my overall concept, I will adjust as necessary. 

I have limited time available, so don't expect anything significant quickly. I will update this page as I make progress.

## Clone the repository

```console
git clone https://github.com/dmisino/seed_ai.git
cd seed_ai
```

## Installation and setup

To run this project, you'll need Python installed on your machine. You can install it from [python.org](https://www.python.org/downloads/).

## OpenAI API

This project uses the [OpenAI API](https://platform.openai.com/). You will need to get an API key, and to add that to a .env file you create within the project directory. This project includes a .env-sample file, which you can rename to .env, and then add your API key there. 

Alternately you can set the API key in your environment:

```console
rem Windows
set OPENAI_API_KEY=<your api key>

rem Unix or Mac
export OPENAI_API_KEY=<your api key>
```

## Usage
 
 ```console
python main.py
 ```
