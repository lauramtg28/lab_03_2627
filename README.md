# Lab 3

## Reproducible Quarto

There is some data analysis and commentary in `bond.R`. The first task is to
**convert this to Quarto**.

### Task 1

- [x] Create a Quarto file to hold the new analysis.
- [x] Copy across the analysis. (**Then push to GitHub**)
- [x] Make sure the R code runs. (**Then push to GitHub**)
- [x] Convert comments to Markdown. (**Then push to GitHub**)
- [x] Replace constants with inline code chunks. (**Then push to GitHub**)
    - Remember the inline `` `r ` `` syntax!

## Git for Collaboration

### Task 2: Collaborating

Pair up with someone next to you.

- [ ] Choose one of you (Person A) to add a peer (Person B) as a collaborator to this repo (which you forked at the start of the lab).
    - To do this, Person A goes to the repo in `GitHub`, then adds B's GitHub Username in (**Settings → Collaborators**) so you can both push.
    - Person B will receive an invite by email.
- [ ] Person B should then **clone Person A's** repo, and complete the below in that repo.

### Task 2a: Breaking Things

Now deliberately create a merge conflict.

- [ ] Both of you change the **same lines** of the analysis, but differently.
    - e.g. you both add a plot of `Martinis` against `US_Adj`, but with
      different colours / titles / options.
- [ ] One of you **commits and pushes**.
- [ ] The other **commits**, then tries to **push** — it will be rejected.

### Task 2b: Oh No!

- [ ] Try a `git pull` — you might get a *merge conflict*.
- [ ] Fix the merge conflict, then **commit and push**.
- [ ] Make sure your peer **pulls** the fixed version.
- [ ] Swap roles and do it again!

### Task 2c: Swap (Stretch)

- [ ] Try it again, but this time swap roles.