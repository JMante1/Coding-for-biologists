# Coding-for-biologists
Coding resources for biologists who are learning to code
# Resources
## Python
 - It is good to have an idea of these basic things before diving in and then learning the rest on the fly (I like starting with codeacademy https://www.codecademy.com/learn/learn-python):
   - Sets, lists, dictionaries, strings, numbers, if statements, for statements, print statements. Additionally, you might want to know about pandas dataframes and numpy arrays.
 - Choosing an IDE for python: https://www.programiz.com/python-programming/ide (personally I use spyder as part of anaconda but am slowly switching to VSCode as it allows flexibility of coding language)
 - Know how to define a function (https://www.geeksforgeeks.org/functions-in-python/)
 - Useful packages:
   - Pandas
   - Os
   - Flask
   - Requests
 - Virtual environments:
   - Python general: https://docs.python.org/3/tutorial/venv.html
   - Anaconda venv: https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/
 - Useful sites for questions:
   - Python docs: https://docs.python.org/3/
   - Geeks for Geeks (one of my favourites):  https://www.geeksforgeeks.org/
   - Tutorialspoint: https://www.tutorialspoint.com/python/index.htm
   - W3 School: https://www.w3schools.com/python/default.asp
   - https://www.programiz.com/python-programming
   - A very good website but not all content is free: https://realpython.com/
   - https://www.datacamp.com/community/tutorials
   - For documentation of particular packages it is good to try and search here: https://readthedocs.org/
   - Stack overflow (good for specific difficult solutions not great for coding as there are some very hacky answers): https://stackoverflow.com/
   - Search engines are your friend
 - Visualisation resources (when you need to ‘see’ data you are working with):
   - https://python-graph-gallery.com/
   - https://datavizcatalogue.com/index.html
   - Good packages: matplotlib and plotly
## Synbiohub Plugins
 - Synbiohub plugin template(this is rather outdated, I would use the visualisation test plugin or the submit test plugin as an example to build off of): https://github.com/SynbioHub/plugin-template
 - Example of a submit plugin:
   - https://github.com/SynBioHub/Plugin-Submit-Test
 - Example of a visualisation plugin:
   - python: https://github.com/SynBioHub/Plugin-Visual-Test
   - Javascript: https://github.com/SynBioHub/Plugin-Visual-Test-js additionally this example serves a file: https://github.com/SynBioHub/Plugin-Visual-Serve-Test-js
 - Synbiohub plugin documentation: https://synbiohub.github.io/api-docs/?python#plugins
 - Plugin Paper: https://pubs.acs.org/doi/10.1021/acssynbio.0c00056
## Coding Etiquette
 - Make code modular
   - As a rule of thumb if you are repeating an action more than once it should be a function
   - If data might come in from a different source sometimes then break apart the source specific code from the source independent code (i.e. separate preprocessing and processing)
   - If it would be a separate paragraph in a ‘story’ it should be a separate function
 - Use sensible variable names
   - Use ‘_’ to separate words
   - Indicate the data type in your variable
   - Consider conventions
   - Beware capitalisation (python is case sensitive)
   - Beware plurals (it is very easy to add/forget an s)
 - Comment extensively (whilst too many comments can be problematic for now err on the side of too many)
   - Whilst commenting completely can be left for later do comment at least minimally throughout
   - An example of the extent of commenting that would be good is here: https://gist.github.com/syrte/592a062c562cd2a98a83#file-arcs-py
   - A good guide regarding comments: https://realpython.com/python-comments-guide/
   - Consider docstrings too
 - If it seems unwieldy step back
   - If it seems that it takes a ridiculous number of steps or is a common problem take a step back
   - It might be that there is already a library that does what you want
   - If might be that there is a completely different and more elegant way of implementing what you want
   - Try and start simply and build up the functionality. Additionally, for loops try repeating it once or twice instead of jumping in to 50 runs immediately.
 - Don’t hard code
   - To make code as transferable as possible don’t hard code
   - Use os.getcwd() and os.path.join() to prevent writing code that is linked to your particular file system (also better for safety when you publish the code)
   - Define variables instead e.g. number_of_repeats rather than putting in 10 right away
   - The same goes for strings you might want to use
 - Testing!
   - Test as you go along as much as possible
   - Consider weird ‘edge cases’ that might cause issues with the program
## Software Development
 - Github: it is very useful to create an account here and then create a project. You can link it to a file directory using github desktop to back up any code you write
 - Postman: allows you to test APIs (such as the plugin) that you are developing (https://www.postman.com/)
## Internet and APIs
 - Good very simple explanation of how the internet works: https://www.youtube.com/watch?v=oM9yAA09wdc
 - Good explanation of APIs best practices: https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design
## Organisation
 - For papers use zotero: https://www.zotero.org/
 - For documents use google docs
## Academic Writing
 - Phrase bank (ways to phrase things in academic writing): http://www.phrasebank.manchester.ac.uk/
 - List of many writing resources: http://writingspaces.org/essays
 - Overleaf is a useful way to write academic articles as many journals have templates for it: https://www.overleaf.com/
