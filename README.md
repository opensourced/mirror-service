# Opensourced Mirror Service

This is a project that mirrors Git repos into the OpensourcEd GitHub organisation.

## How does it work

Whenever the master branch is updated, a GitLab pipeline runs whcih forms repos
into the OpensourcEd GitHub organisation.

## How to contribute

You can add your open-source project added to the OpensourcEd github group. In 
order to do this, your repo must be:

1.  Available publicly on GitHub
2.  Have an open source licence 

To add your repo:

1.  Fork this repo
2.  Update repositories.txt with the user/repo combination on a new line
3.  Submit a pull request
4.  If accepted, your repo will be forked and updated every day

## To Do

- ~~write a gitlab ci file that can fork a repo via the github api~~
- ~~loop through a file of urls to do this (i think i have a bash loop script laying around somewhere)~~
- add an upstream to the fork
- make an update stage that pulls updates from the upstream
- ~~mirror the mirroring service repo, which should contain one file (txt file) and then people can pull request their repo details~~
- Support other VCS providers