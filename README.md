## Please Upload your code to github daily. 

#### README
* upload your code with clear comment, so that people understand your code.
* create branch for testing code. Don't push experimental code to master (master for release/stable version).
* sync daily

###### Step to git:
`git add <A file> <B file>` adding all the files you have edited on the day to github

`git commit -m "<the command>"` comment on those files, so that people could know what it is

`git push -u origin <the branch you want to push to>` push to the branch (master=release/stable) you want.

###### example
```
git add led.py ledflash.py
git commit -m "adding led and flashing function"
git push -u origin master
```


