# github_comands

Practiced Commands:

1.git init

2.git add README.md

3.git checkout filename (revert changes)

4.git log/ git log -p-2(the last 2 commits)

5.git diff(comapres the modified files with last commit)/ git diff --stagged(comapres the stagged files with last commit)

6.git add -A

7.git add -u

8.git add .

9.git rm(remove files from directory and stagging)

10.git rm --cached(removes from stagging)

11.code .gitignore

12.git barnch newbranch

13.git checkout new branch

14.git status

15.git commit -m "feat:new feature added"

16.git commit -a -m "feat:new feature added"(to skip stagging step)

17.git remote add origin master

18.git push -u origin master

19.git merge "branchname"

20.git branch

21.git clone "link of repository" filename

22.git restore --stagged(to unstage a file)

23.git branch --merged

24.git branch --no-merged

25.git barnch -d "barnch name" (delete branch)

26.git fetch origin (fetch the newly added branches from hithub) git checkout origin/newbranchname(get all files form the new branch on github)

27.git pull origin master (updates files from github to vs code)

28.git barnch -r (list of all the barnches on vscode)


## BRANCHING STRATEGIES:

1. Trunk Based development:
It has a single truck line/master. Everyone clones the code to their local computer,make changes and push it back to the trunk.
It has no branches and there is no merging.
It is a continuous development process and the easiest among all other stratergies.
It is mostly used to fix bugs and errors.

2. Feature Branching:
In feature branching everyone make a branch of the master to do changes in the code.
After making changes they generate a pull request and than is followed by a merge operation to the master branch to implement them.
It is a short cycle process and has continuous development.
It is also easy to maintain and perform since merging is at only one level.

3. Forking Stratergy:
In this process the repository is forked by the people who want to make changes to the code.
After making changes they make a pull request to the owner, that is accepted through a merge operation.
Here everyone copy the repository and make changes in this way they do not require any permissions.
It is mostly used to contribute in open source projects and is easy to handle.

4. Release Branching:
In this strategy diffrenet branches are generated for different releases of a software, which is then further branched among the
group of people in each release.
It is a multibranching strategy which is difficult to handle, since merging is to be performed at two levels, fisrtly among the
release members than among the releases to the main branch.
It doesn't deliver continuous results, and each process is dependent on the other.
It is a long lasting strategy and difficult to perform and maintain.

5. Git Flow:
In this strategy the master brach has multiple branches, development branch,feature branch and release branch.
Due to multiple branches there and many pull requests and merge operation to be performed.
Git flow is very difficult to maintain and is highly unreasonable.

6. Environmental Branching:
Envrionmental branching is just like git flow with the only diffrence that the branches are based on different types envrionments
like development environment, staging envrionment, integration envrionment.
The branching is than further divided into releases and groups, in this way the pull requests are multipled by the number of branches
and merging becomes a hectic task to perform.
It is most complicated strategy among all other and is highly discouraged one. 

Conventional Commits:
Conventional commits provides as a syntax to write meaningful meaasges with very commit, which makes it easier for us and others to determine
what was been carried out in the future.
Other than that conventional commits generate a automatic changelog and structured commit history so that people can easily contribute in our
project.

Parts of convetional commits:
conventional commits have five parts.

type [optional scope]: description
[optional body]
[optional footer]

1. Type:
It tells the intent of the commit there are different types like.
  a.fix : used for bugfix 
  b.feat: used for features.
 further there are many others like build,style,docs,refactor,test etc.
 
2. Optional Scope:
any addtional info can be added here but it should be inside parenthesis and a noun shall be used.

3. Description:
A short message but use imperative.

4. Optional Body:
It is free form and you can write what changes you have made here.

5. Optional Footer:
It is also optional and a work token can be added along with # or :.









