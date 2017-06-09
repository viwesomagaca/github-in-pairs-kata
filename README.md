# GitHub in pairs Kata

Pair with another coder and do this GitHub kata. This kata will teach you a workflow that allows two or more coders to work together on a shared GitHub repository. There are other workflows like `git flow` which use feature branching, but you will start not be using feature branches in the Kata. This kata will prepare you for using `git flow`.

**Do this:**

* One coder **fork** this repository
* Add the other coder as a collaborator to this **forked repository**
* Both coders clone the **forked repository** to their machines

## Do this one user after the other

`Coder 2` waits until `Coder 1` is done, then start working. `Coder 1` then waits for `Coder 2` and so forth.

### Coder 1:

* Add a html file called `index.html`
* Commit to Git and push to GitHub

### Coder 2

* Pull from GitHub using : `git pull`
* Add `main.css` and link it to `index.html`
* Commit to Git and push to GitHub

### Coder 1

* Pull from GitHub using : `git pull`
* Add a background color to web page in `main.css`
* Commit to Git and push to GitHub

### Coder 2

* Pull from GitHub using : `git pull`
* Add a file called `main.js`
* Link it to `index.html`
* Commit to Git and push to GitHub

### Coder 1

* Pull from GitHub using : `git pull`
* Add a div to index.html with a className of `theMessage`
* Style `theMessage` div to height of `5em` and a with of `10em` and a different color to your pages color.

## Now both at the same time

`Coder 1` should not wait for `Coder 2` and vica-versa!

### Coder 2

Create a new div in `index.html` with a message of `This is a new div` with a class of `messageTwo`. Style `messageTwo` with a unique background color in `main.css`. Commit and push to GitHub once done.

### Coder 1

Create a new div in `index.html` with a message of `This is another div!` with a class of `messageThree`. Style `messageThree` with a unique background color in `main.css`. Commit and push to GitHub once done.

### Coder 1 & Coder 2

**Conflict time!**

* Why did this happen?
* How can you prevent this?
* How can you resolve it?

## Review time

* What did you learn?
* What did realise?
* What questions do you have now?

