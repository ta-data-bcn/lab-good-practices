# Variables Naming

-lower_case
-snake_typing(we will use "_" between words)
-logic words for variables, each word after a "_" gives a deeper level of detail about the
variable ("level1_level2_level3")
-aim for maximum of 2 words per variable.


# Function Naming

-lower_case
-snake_typing(we will use "_" between words)
-verb + noun structure ("filter_animals")
-aim to have high granularity of functions (if a function can be divided in two, then it should be 2 functions)
-to build a function have a clear knowlodge of the arguments you have available, and what we
expect to return.
-always comment the purpose and basic function of every function we make. if there is a nested
function inside, comment with a quick recap of this second function as well.
-inputs from users should be implemented by defining functions, this way we can add restrains
and control what data type we get.

# Libraries

-import in the first cell of the notebook (separated from other cells)

-Pandas
-Numpy
-BeautifulSoup
-request
-re(regex)
-matplotlib


# Community conventions.

-Plan the project before beginning.(trello or to-do-list)

-standup meetings with teammates at the beggining and end of the day, helps to prioritize and spend time more efficiently on the important barriers for the team. (assign responsible
for each task)
-dont overwrite keywords from python(class for example)
-follow PEP 8[https://www.python.org/dev/peps/pep-0008/]


# Other (git, ...)

-when interacting with API, do it as one of the first cells and avoid running it again.(takes time and might exhaust API access limit)
-data analysts work on different files initially(different tasks/responsabilities)
-file names with the name of the data analyst to differentiate during the project (to be normalized at the final version)
-whenever interacting with a new API read the basic documentation.
-frequent #GIT commits/push (at least once a day, in the afternoon, before the standup meeting) 
-GIT SEQUENCE -> CLONE-WORK-ADD-COMMIT-PULL-PUSH







