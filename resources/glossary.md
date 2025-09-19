# Glossary

```{tip}
Contributing glossary terms or linking to uses of glossary terms to this page is eligible for community badges
```

:::::::{glossary}

absolute path
:  the path defined from the root of the system

add (new files in a repository)
:  the step that stages/prepares files to be committed to a repository from a local branch

argument
:  input to a command line program

base
: the shared {term}`commit` of a branch

base branch
: the branch that a PR or merg will add changes **into**

bash
:  `bash` or the bourne-again {term}`shell` is a popular interface in UNIX based systems
:  its code originally derived to be fully free an dopen source alternaive to the Bourne shell (`sh`)

bitwise operator
:  an operation that happens on a bit string (sequence of 1s and 0s). They are typically faster than operations on whole integers. 


branch
:  an isolated version of the project in a repository where changes do not impact other changes
:  on github and other hosts [branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) are used to create Pull Requests 
:  implemented with a pointer to a commit, that moves when new commits are added to the current branch

Bourne Shell
:  an early unix shell developed at Bell labs (`sh`)
:  the precursor to `bash`

Compiled Code
:  code that is put through a compiler to turn it into lower level assemlby language before it is executed. must be compiled and re-executed everytime you make a change.

commit 
:  the basic unit of git

commit message
:  the plain language description that is required, entered with the `-m` option on `git commit`

detached head
:  a state of a git repo where the head pointer is set to a commit without a branch also pointing to the commit


directory
:  a collection of files typically created for organizational purposes

divergent
:  git branches that have diverged means that there are different commits that have same parent; there are multipe ways that git could fix this, so you have to tell it what strategy to use

escape
:  (verb) to insert an <wiki:Escape_character>


fixed point number
:  the concept that the decimal point does not move in the number. Cannot represent as wide of a range of values as a floating point number.

flag
: another name for an {term}`option`

floating point number
:  the concept that the decimal can move within the number (ex. scientific notation; you move the decimal based on the exponent on the 10). can represent more numbers than a fixed point number.

fork
:  a related repository, a full copy of the repo

git
:  a version control tool; it's a fully open source and always free tool, that can be hosted by anyone or used without a host, locally only.


GitHub
:  a hosting service for git repositories


.gitignore
:  a file in a git repo that will not add the files that are included in this .gitignore file. Used to prevent files from being unnecessarily committed.


git objects
:  FIXME something (a file, directory) that is used in git; has a hash associated with it


git Plumbing commands
:  low level git commands that allow the user to access the inner workings of git.


git Workflow
:  a recipe or recommendation for how to use Git to accomplish work in a consistent and productive manner


HEAD
:  a file in the .git directory that indicates what is currently:  checked out (think of the current branch)

hidden file
:  a file with a name that starts with `.` that is not visible in default settings for file explorer/finder or with `ls` unless you use  `-a` 

merge
:  putting two branches together so that you can access files in another branch that are not available in yours


merge conflict
:  when two branches to be merged edit the same lines and git cannot automatically merge the changes


mermaid
:  mermaid syntax allows user to create precise, detailed diagrams in markdown files.


hash function
:  the actual function that does the hashing of the input (a key, an object, etc.)


hashing
:  transforming an input of arbitrary length to a unique fixed length output (the output is called a hash; used in hash tables and when git hashes commits). 


integrated development environment
:  also known as an IDE, puts together all of the tools a developer would need to produce code (source code editor, debugger, ability to run code) into one application so that everything can be done in one place. can also have extra features such as showing your file tree and connecting to git and/or github.


interpreted code
:  code that is directly executed from a high level language. more expensive computationally because it cannot be optimized and therefore can be slower.


issue
:  provides the ability to easily track ideas, feedback, tasks, or bugs. branches can be created for specific issues. an issue is open when it is created. pull requests have the ability to close issues. see more in the [docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)


Linker
:  a program that links together the object files and libraries to output an executable file.


option
:  also known as a flag,
:  a parameter to a command line program that change its behavior, different from an argument


path
:  the "location" of a file or folder(directory) in a computer


pointer
:  a variable that stores the address of another variable


pull (changes from a repository)
:  download changes from a remote repository and update the local repository with these changes.


[pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
:  allow other users to review and request changes on branches. after a pull request recieves approval you can merge the changed content to the main branch.


PR
:  short for {term}`pull request`


prompt
:  the text displayed in the terminal before the content that you type
:  in bash, customizable with the environment variable `PS1`, see an example [helper tool](https://bash-prompt-generator.org/)


push (changes to a repository)
:  to put whatever you were working on from your local machine onto a remote copy of the repository in a version control system.

redirect
:  connecting the output of a command to an alternative {term}`stream`
:  syntax `>` for write mode and `>>` for append mode

relative path
:  the path defined **relative** to another file or the current working directory; may start with a name, includes a single file name or may start with `./`


release
:  a distribution of your code, related to a git tag


remote
:  a copy of the repository hosted on a server


repository
:  a project folder with tracking information in it in the form of a .git directory in it


ROM (Read-Only Memory)
:  Memory that only gets read by the CPU and is used for instructions


SHA 1
:  the hashing function that git uses to hash its functions (found to have very serious collisions (two different inputs have same hashes), so a lot of software is switching to SHA 256)

sh
:  abbr. see shell

shell
:  a command line interface; allows for access to an operating system


ssh 
:  allows computers to safely connect to networks (such as when we used an ssh key to clone our github repos)

STDOUT
:  standard output {term}`stream`


STDERR
:  standard error {term}`stream`

stream
:  a flow of data from one location to another in a computer 
:  includes three <wiki:Standard_streams>

templating
:  templating is the idea of changing the input or output of a system. For instance, the Jupyter book, instead of outputting the markdown files as markdown files, displays them as HTML pages (with the contents of the markdown file).


terminal
:  a program that makes shell visible for us and allows for interactions with it


tree objects
:  type of git object in git that helps store multiple files with their hashes (similar to directories in a file system)


yml
:  common file extension for {term}`YAML` files


yaml  
:  a file specification that stores key-value pairs. It is commonly used for configurations and settings.  [main docs](https://yaml.org/)


zsh
:  zsh or z shell is a {term}`shell` that contains new features that break conventions that `bash` adheres to but is faster at some things [see its FAQ](https://zsh.sourceforge.io/FAQ/)
:  a unix shell with a more permissive license (MIT) than `bash` (GPL)
:  a shell that is based on the KornShell (`ksh`) which was based on the Bourne shell initially

::::::::::
