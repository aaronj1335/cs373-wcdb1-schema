this is where we're going to try and get consensus on a shared schema for our
world crisis data.

the file is `WorldCrisis.xsd.xml`, and it's based on [vineet's original
proposal](https://d1b10bmlvqabco.cloudfront.net/attach/hh9t8ndchdb5gl/hbxyznmgwj11l4/hik2a4h35fx2/WorldCrises.xsd.xml).

please start by implementing your `WorldCrisis.xml` file and validating against
this schema:

```
$ xmllint --noout -schema WorldCrises.xsd.xml MyWorldCrisisFile.xml
```

this is meant to be something that anyone can edit as you're implementing your
info. if you've got updates, let me know your github handle and i'll add you
as a collaborator for the repo, so you can just push directly to it.

if you think you've got a change that will break backwards compatibility, try
submitting a pull request, and that will give us the chance to get consensus.
