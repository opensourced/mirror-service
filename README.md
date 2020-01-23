# Opensourced Mirror Service

This is a project that mirrors Git repos into the OpensourcEd GitHub organisation.

## How does it work

Whenever the master branch is updated, a GitLab pipeline runs whcih forms repos
into the OpensourcEd GitHub organisation.

## To Do

- ~~write a gitlab ci file that can fork a repo via the github api~~
- loop through a file of urls to do this (i think i have a bash loop script laying around somewhere)
- add an upstream to the fork
- make an update stage that pulls updates from the upstream
- mirror the mirroring service repo, which should contain one file (txt file) and then people can pull request their repo details