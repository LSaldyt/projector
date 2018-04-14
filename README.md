# Projector

### Setup

Install python(3.x) and the requests library.  
`pip install --user requests`

### Usage

Tag your github projects with "[category:$NAME]" in the description, where $NAME is some bin that the project fits into.  
For example, my artificial intelligence projects are tagged "[category:ai]" and my clones are "[category:clones]".  
Then use the following to clone all projects into appropriate bins:

`./projector $USERNAME`: Clone all projects into a tree: `~/projects/$NAME`, where name is the category (as above) of the project.

Following the above example, my tree would look like:
```
projects/
  ai/
    ai-project-1
    ai-project-2
  clones/
    clone-1
    clone-2
```
