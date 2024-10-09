## Part-1 : Individual Repository
- Login to github
- Create a repository with README.md
- Create README.md (if not yet created)
- Do some changes to README.md
- Create hello.c (or hello.py)
- Make some changes to hello.c/hello.py
- View the history 
- Add some more files, make changes (min 5 commits)
- Create a branch, say MS1
- Switch to main branch
- One more commit on main branch
- Switch to MS1 branch
- Do a commit to MS1 branch
- Check difference between the branches
- Open code spaces
- Try these commands
```
gcc hello.c
./a.out
python3 hello.py
```

## Group work 
- Create a private repo, say `simple-project`
- Add other members as collobarators
- Create following files one each from team member
  - simple.c
  - sum.c
  - sqr.c
  - myutils.h
  - Makefile
- Check the history , commits from different members
- In codespace, try these commands
```
gcc simple.c   # error
gcc sum.c       # error
gcc sqr.c         # error
```

### How to build:-
```
gcc simple.c -c   # compile only, generates simple.o
gcc sum.c -c
gcc sqr.c -c
gcc simple.o sum.o sqr.o -o all.out
(or)
make clean
make
```
