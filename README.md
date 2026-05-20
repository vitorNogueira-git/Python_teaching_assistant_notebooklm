INTRODUCTION
A teaching focussed chatbot, made for teaching all sorts of contents about python programming and its interactions with SQL databases. It is made to sound like a university professor, so it can teach from the simplest programming related content, all the way to complex GUI and backend programming with Python.

SOURCE CURATION
From all Links i've used to build this notebook, here will be put some of the most important ones:

https://www.youtube.com/watch?v=nLRL_NcnK-4
https://www.niit.com/india/blog/python-for-data-analytics-a-complete-career-roadmap
https://www.python.org/doc/
https://roadmap.sh/sql/vs-python
https://www.youtube.com/watch?v=mop6g-c5HEY

PROMPT ENGINEERING
As the main intention for the notebook was for it to be an teacher, all instructions and request were all around this subject and bellow are a few instructions and strategic requests:

- 'Você irá se comportar como um tutor/professor, responsável por tirar dúvidas e ensinar sobre programação em Python e tabmém sobre suas possíveis integrações com SQL, baseie-se nas fontes anexadas'
- 'Behaviour: Your goal is to act as a Professional with experience in the area of computer science and programming, especialy in Python and SQL, and all your content will be made focussing on students, people that do not know yet so much about the topics you teach, so seek being linear with your teaching path.'
- 'Give me a brief roadmap for what i should learn in python, considering that im a software engineering student, and i have notion about programming logic but dont know much about any programming language and want to start with python'
- 'give me a thoughout guide about how to integrate SQL on to my python code, considering that im developing a simple data analysis code'

Most of the answers obtained were quite what i've expected at first place, so considering this, there was not so mutch troubleshooting, what I realise is that, because the notebook has this instruction to work as a teacher, it will give you realy detailed answers and content every time, even though sometimes the solution for the question can be a simpler answer. But I do not see this as an erros, I prefer the surplus of information than the lack of it.

The way of correcting it as i saw was to give the agent a feedback on its answer (preferably a detaild feedback for it to learn quicker) and then I rewrote the question being more specific in what I want to learn at that moment.

USAGE GUIDE 
As said previously, this agent is intended to work as a professor, so its main goal is to teach content about Python programming.
Because Python is a language with a vast field of aplication, it would be hard to resume what fields it can be especifically used, so it depends on what is requested to learn about. But the agent have some sources from especific areas such as the integration between Python and SQL as a data analysis inteface, and how to create websites and apps using python by itself with its APIs.
When you open the notebook, you are greeted with a brief introduction of some of the contents it used as sources like analysis of data processing, GUI creation or data manipulation via internal varibles.

MAIN CONCEPTS LEARNT
- Python programming fundamentals:
    - Core Syntax and logic
    - Data Structures
    - Functional Tools
- DataBase Management and SQL:
    - SQL basics
    - Relational Design
    - Advanced Querying
    - Database Objects
    - Optimization and security
- Datascience and Analytics:
    - Datawrangling with Pandas
    - Numerical computing
    - Data visualization
    - Modern analytical engines
- Software Engineering Practices:
    - Objetc oriented programming (OOP)
    - Version control
    - Automated Testing
- Application Development (GUI):
    - Tkinter
    - PyQT
    - Multimedia integration
 
USEFULL PROMPTS
When using an AI such as this notebook, it is aways preferable to go for more direct questions, so here are some examples of prompts that are quite usefull:
 Simplfying and explaining concepts:
 - "What are [concept, e.g., methods] in Python? Explain it like I'm five"
 - "Show me how to use common methods in Python for [data type, e.g., strings]; actually show the code and what you expect as the solution"
 - "Explain [concept] - Summarize or clarify any part of this guide"
    Note: Every time you want to clear up doubts, just make a simple and clear prompt such as : 'Explain the diference between using Tuples and Lists'
 Generating Mock Data:
 - "Generate a python dictionary titled [Title] with [Key] as the key and [Value] as the value; use random values for each and make it [Number] items long"
 - "Generate a dictionary titled [Title]... the keys and data types for values for the dictionary are [Key1: Type1, Key2: Type2]"
 - "Generate more fake data for this list"
 Debuggin and TroubleShooting:
 - [Paste literal error message] : Current AI models are so sofisticated that with just that they can solve the error
 - "Why did I get this error? Explain it to me"

SOURCES USED:

- https://duckdb.org/docs/current/guides/python/jupyter
- https://www.fabioprado.net/2015/05/livros-para-aprender-instrucoes-sql.html
- https://www.python.org/doc/
- https://rodam.ai/precisamos-falar-sobre-o-pandas/
- https://pt.wikipedia.org/wiki/Programa%C3%A7%C3%A3o_defensiva
- https://duckdb.org/docs/current/clients/python/overview
- https://www.youtube.com/watch?v=f_9NBdSAo-g
- https://duckdb.org/docs/current/clients/python/dbapi
- https://www.niit.com/india/blog/python-for-data-analytics-a-complete-career-roadmap
- https://www.youtube.com/watch?v=wUSDVGivd-8
- https://www.youtube.com/watch?v=lrz5pLlyfn0
- https://duckdb.org/docs/current/guides/python/sql_on_pandas
- https://roadmap.sh/sql/vs-python
- https://www.reddit.com/r/dataengineering/comments/1hrn7f3/should_sqlsavvy_data_engineers_learn_pandas_when/
- https://www.youtube.com/watch?v=mop6g-c5HEY
- https://www.reddit.com/r/dataanalytics/comments/1qixwbz/what_should_i_learn_next_after_pandas_any_roadmap/
- https://pandas.pydata.org/docs/reference/api/pandas.read_sql.html
- https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
- https://www.mdpi.com/0718-1876/17/1/9
- https://www.codechef.com/roadmap/data-analysis-using-python
- https://www.youtube.com/watch?v=WXk7yDqsKxs
- https://www.youtube.com/watch?v=nLRL_NcnK-4
- https://hex.tech/blog/query-sql-database-pandas/
- https://duckdb.org/docs/current/guides/python/polars
- https://book.pythontips.com/en/latest/

