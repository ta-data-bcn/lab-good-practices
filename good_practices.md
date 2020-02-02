#Discussions over good practices

#variable naming
- always create unambigous variables, even if it means making them longer, in order to always have ONE variable dedicated to each different case. (i.e. r_wikipedia for one requests.get(wikipedia), then result_wiki  etc.). Never reusing generic variable names (request, respond, result...) which may be confusing in long codes

#function naming
- same concept - always create clear function names which tells immediately the purpose of a function.
Extremely important to fill in every function with DocStrings, stating the Input & Output of the function.

#Libraries
- always importing all libraries at once at the beginning of the code (except in specific cases if needed within a function), in order to centralize all imports at the top of the code, and stating which ones will be used during the code
- using conventional naming and abbrevations for libraries when imported (pandas as pd, numpy as np)

#Community conventions
- use conventions over naming of functions (__init__), classes (self) & variables

#Git
- Important to present well ordened and clear Git Repos to allow fellow developers & coders to quickly understand the structure of the Repos and the goals of each folders & files