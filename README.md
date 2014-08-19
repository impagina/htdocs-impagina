# htdocs-impagina

the impagina.org website

# Content

- Contributors manual
- Projects specification
  - specific repository with each project entry
  - use gists or issues for each project to allow comments (link to automatically create an issue for each project?)
  - create a client for the mantis api to show all the tickets with a specific tag
- Planet
- Contributors manual
- irc log
- blog

## The projects specification

- a specific repository for the projects specifications.
- each specification is one directory (or one file?)
- the module on impagina.org pulls the list of the specifications
- comments are done on github issues
  - pull the comment through the github API and show them on the page
  - have a link for adding the issue / go to the issue and make comments
- contributions to the specification are made through fork / branch / pull request or by incorporation of the comments by an "admin"
- show a list of mantis ticket related to the specification (probably by getting from the API by tag)

open questions:
- how to tag the specification and make them easier to search / filter?
- cache the list?
