# Read 02
# Introduction to Git
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers working together to develope a source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).


### Some basic git commands:

** tells us whats going on **
1. git status

** To add a single file **
2. git add <file>

** To add everything at once **
3. git add -A

** viewing branches **
4. git branch or git branch --list

** Deletes branch **
5. git branch -d <branch-name>

6. Git clone
Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.

There are a couple of ways to download the source code, but mostly I prefer the clone with https way:

git clone <https://name-of-the-repository-link>
For example, if we want to download a project from Github, all we need to do is click on the green button (clone or download), copy the URL in the box and paste it after the git clone command that I've shown right above.
