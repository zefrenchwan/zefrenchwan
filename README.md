# Who are you ? 

* A french developer, old enough to know about java, young enough to not know about cobol
* I work as a data engineer, usually in Java, Golang or Python. I worked a lot in banks and adtech companies.
* My personal interests are networks science, python, golang, NLP

# What projects do you work on ?

|   Name   |   Topic  |   Status |   Lang |
|---    |:-:    |:-:    |:-:    |
| Nodz | Graphs | Done | Golang |
| Patterns | Graphs with time dependencies | Prod ready | Golang |
| Monocle | webscraper and content analysis | Done | Python |

* [Nodz](https://github.com/zefrenchwan/nodz) I like graphs, and I wanted to build a basic lib to experiment some graphs structures and random graphs. For instance, what happens when, given a graph and a node id, graph structure allows to directly point at it ? Easy, right ? This is a central structure graph. For peers graphs, it is not always the case, you usually start with a node (not the one you want) and you try and walkthrough to find the node you want. Big difference. Random graphs and percolation, the other part of the code, is quite fascinating. 
* [Patterns](https://github.com/zefrenchwan/patterns) This api is a full project to deal with time and graphs. Create a person, for instance born in 2000 and still alive. Now, look for people in 1998, you should not see this data. Dealing with time logic and graphs is useful, but developers may not want to code it. Good news, it is done in there. This project has many features and some concepts, deal with examples first (start reading tests). 
* [Monocle](https://github.com/zefrenchwan/monocle) sumups a website by isolating its named entities. Assume you have a website and you do contextual advertising (not user based, but content based). You may want to find what it is about and classify its content. For instance, this website is about sports or video games. Then, you scrap this website and you apply a NLP model to find named entities, main words, etc. This code is the part before data science, it reads the content and apply NLP preprocessing. Might help osint community too. Usage is CLI based, nothing fancy. 


# May I use your code ? 

Public code is so far under MIT licence. 
In a nutshell, it means "yes" and "just mention that base code came from here and me". Not a huge price. 
I hope that my code and related work help you somehow. 
