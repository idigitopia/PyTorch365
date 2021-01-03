# Shpinx

- Sphinx is a documentation generator or a tool that translates a set of plain text source files into various output formats, automatically producing cross-references, indices, etc. 
- reStructuredText (reST) is the default plaintext markup language used by both Docutils and Sphinx. 
- conf.py file controls how Sphinx processes your documents. 
- Sphinx supports docstrings from modules with extension autodoc. This can be activated using conf.py
    - Appropriate paths musth be added to sys.path in conf.py 



## Quick Notes
- Easy install, and quickstart script
- different source and build directory. sourcedir is the source directory and builddir is the directory in which you want to place the built documentation. 
- makefile is already there to help with the build. 
- A domain is  acollection of object types that belong togther. 
- 


## Video Reference 
- [Carol Willing - Practical Sphinx](https://www.youtube.com/watch?v=0ROZRNZkPS8): A quick overview of the tool and how it is a practical tool in the workflow of any project. 

    - Basics: Install it, quickstart script. 
      - Exploring: conf.py (you can execute python code here)
      - make clean, make build, serve 
    - Words: 
      - Add .mt .rst or .ipynb for source suffixes. (any in index file.)
      - pandoc can convert md to rst or rst to md. 
      - Writing tip: Content First, Quality Later.
    - Visuals: 
      - Add images as well with a directive. [image:: filename]
      - you can add code with syntax highlighting. 
  
    - Structure:
      - level of headers
      - captions too
    
    - Workflow:
      - make build, make checklink, Travis CI or github webooks. 
      - automate for UI
      - Iterate, content, tools & Delivery, Feedback. 
  
    - Extensions: 
      - autodoc: use docstring to document the code.
      - autodoc: can pull objects and functions. (napolean converts docstrings)
  

  
## Text Reference