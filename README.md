# SBTProjectTemplate

1. Create new SBT project in IntelliJ
2. Create a new repository on GitHub
	
	echo "# SBTProjectTemplate" >> README.md

3. touch .gitignore
4. Add into git .gitignore string:
### SBT ###
dist/*

target/

lib_managed/

src_managed/

project/boot/

project/plugins/project/

.history

.cache

.lib/

### Scala ###
*.class

*.log

### Idea ###
*.iml

*.ipr

*.iws

.idea
out

### Other ###
tags

.*.swp

.*.swo

5. Add Main.scala
6. git init
7. Check by git status (.idea has to be removed from untracked)
8. git add .
9. git commit -m "Lost commit"
10. git remote add origin https://github.com/cubazis/SBTProjectTemplate.git
11. git remote -v
12. git push origin master