layout: true
class: center, middle
name: pic
background-size: contain

---

layout: true
class: center, top
name: fragment

.title[{{name}}]

---
layout: true
class: center, middle
name: base

.title[{{name}}]

---
name: this is git

.fancy.medium_small[![xkcd git](http://imgs.xkcd.com/comics/git.png)]

???

* TREEEESSS
* whaaaat?
* code version control system
* submitting assignments, group work, grading, etc

---
name: social coding

<iframe src="//giphy.com/embed/3oD3YveOJWdwIAfZ5e" width="600" height="389" frameBorder="0" class="giphy-embed"></iframe>

???
* social coding
* changed the world enabling many mmore people to contribute easily
* github in particular has been instrumental in this


---
name: why git? source version control

<iframe width="660" height="415" src="https://www.youtube.com/embed/cNBtDstOTmA?start=6" frameborder="0" allow="autoplay;" allowfullscreen></iframe>

???
* there were other source version control systems
* git was distributed - all versions of everything live on your computer
* invented by linus torvalds to help work on linux, the thing that basically popularized the open source movement.

---
name: transports

.medium_small[![](img/git_data_transport.png)]

???




---
name: merge conflicts!

```javascript
<<<<<< HEAD
var h = 'hello, world';
======
var h = 'Hi!';
>>>>>> cb1abc6bd98cfc84317f8aa95a7662815417802d
```

1. eeeeek
2. take a deep breath
3. fix the file, make sure it works locally
4. `git add conflicted_file_name`
5. `git commit` # comment is prefilled out OR
6. `git rebase --continue` # if you were rebasing 

???
* is scariest
* but take a deep breath will be fine
* fix the file
* git add the file
* git commit #comment is premade


---
name: git visualization

[https://onlywei.github.io/explain-git-with-d3/](https://onlywei.github.io/explain-git-with-d3/)

???
* used to have a bunch of slides but this is prettier
* lets try some things out here
* git branch - what it looks like
* git pull - what it looks like
* git rebase takes current checked out branch and makes it point to newer
* git merge creates a new merged commit node - messier but also clearer?
* fast forward is nice




---
name: more resources

* [http://www.ndpsoftware.com/git-cheatsheet.html](http://www.ndpsoftware.com/git-cheatsheet.html)
* [https://learngitbranching.js.org](https://learngitbranching.js.org/)

???




---
name: Git Short Assignment!

[http://cs52.me/assignments/sa/git-map](http://cs52.me/assignments/sa/git-map)

???

