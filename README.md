<h1 align="center"> Hello, it's me, Valentino! I'm an average <a href="https://github.com/kottans">Kottans</a>  enjoyer. :sunglasses: <height="32"/></h1>
<br>
<p align="center">
   <img src="https://github.com/Chotogde/kottans-frontend/blob/d5abf74c9dede107ab1db87ac4dcdfd5efe2eb6a/meme_img/giphy.gif" alt="gif"/>
</p>
<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?size=30&duration=3800&color=FF585D&center=true&vCenter=true&width=700&height=60&lines=%E2%80%9CTime+spent+with+cats+is+never+wasted.%E2%80%9D+" alt="Typing SVG" /></a>
</p>

***

# #Kottans Front-End

### This repository is to track and share my progress on [Front-End Course](https://github.com/kottans/frontend) from [Kottans](https://github.com/kottans) 🇺🇦

***

<details>
<summary><h3> :pushpin:Before we started:pushpin: </h4></summary>
    
#### In this section i want to publish some useful links, what we need to get started, some briefly info for my future self or for someone who will find it useful.
 
#### Links:
:link: [Kottans Front-End main page repo](https://github.com/kottans/frontend) | :link: [Kottans FAQ](https://github.com/kottans/frontend/blob/2022_UA/faq.md) | :link: [Contents](https://github.com/kottans/frontend/blob/2022_UA/contents.md)
  <br>
:link: [GIT](https://git-scm.com/)
  <br>
:link: [Visual Studio Code](https://code.visualstudio.com/)
  <br>
:link: [Oracle VirtualBox](https://www.virtualbox.org/)
  <br>
:link: [Ubuntu](https://ubuntu.com/)
  <br>
:link: [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github) | :link:[Communicate using Markdown](https://github.com/skills/communicate-using-markdown)
  <br>
 
  <details>
<summary><h3> GIT/GitHub </h4></summary>
    
:link:[Generating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) | :link:[Adding a new SSH key to your GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) | :link:[Testing your SSH connection](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)
    
##### You can access and write data in repositories on GitHub.com using SSH (Secure Shell Protocol).When you connect via SSH, you authenticate using a private key file on your local machine. When you set up SSH, you will need to generate a new private SSH key and add it to the SSH agent. You must also add the public SSH key to your account on GitHub before you use the key to authenticate.
<br>
Before you start you need to install Git Bash if you're using Windows
https://git-scm.com/
<br>
    
#### :white_medium_square:Generating a new SSH key
    
<br>

##### You can generate a new SSH key on your local machine. After you generate the key, you can add the key to your account on GitHub.com to enable authentication for Git operations over SSH.
<br>
Paste the text below, substituting in your GitHub email address:
<br>
    
```
    
$ ssh-keygen -t ed25519 -C "your_email@example.com"
    
```
When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.
At the prompt, type a secure passphrase.
    
![SHH1](readme_img/shh1.jpg)

#### :white_medium_square:Adding a new SSH key to your account    
<br>
After you generate an SSH key pair, you must add the public key to GitHub.com to enable SSH access for your account.
You can locate the hidden .ssh folder, open the file in your favorite text editor, and copy it to your clipboard.
<br>
Then on GitHub you need to add SSH key:
<br>
    
__Settings__ > __SSH and GPG keys__ > __New SSH key__ or __Add SSH key__

#### :white_medium_square:Testing your SSH connection
After you've set up your SSH key and added it to your account on GitHub.com, you can test your connection.
    
```
    $ ssh -T git@github.com
```
You may see a warning like this:

```
> The authenticity of host 'github.com (IP ADDRESS)' can't be established.
> RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
> Are you sure you want to continue connecting (yes/no)?
```
    
 ![SHH2](readme_img/ssh2.jpg)
    
   </details>
 
<!-- :link: []() -->
___
 
#### #How I structure the content:
 
  #### I'll answer questions in the end of every section.
1. _What's was new to me:_
1. _Thing that amazed me:_
1. _Thing that i going to use in the future:_
 
  #### I'll add screenshots with progress.
 
  #### I'll add an unformatted summary (just some notes for myself).
 
  ___
 
### #My progress
<details>
    <summary><h5>:white_check_mark:General</h5></summary>
    
- [x] 0. Git Basics
- [ ] 1. Linux CLI and Networking
- [ ] 2. VCS (hello gitty), GitHub and Collaboration
</details>
 
<details>
    <summary><h5>Front-End Basics</h5></summary>
    
- [ ] 3. Intro to HTML & CSS
- [ ] 4. Responsive Web Design
- [ ] 5. HTML & CSS Practice
- [ ] 6. JavaScript Basics
- [ ] 7. Document Object Model - practice
 </details>
 
 </details>
 
***
<p align="center">
   <img src="meme_img/purr.png" alt="meow"/>
</p>

***
<!-------------------------------Stage0------------------------------------->

# #Stage 0
<!-------------------------------General------------------------------------>

<details>
<summary><h2> General </h2></summary>
<!-------------------------------Git Basics--------------------------------->
  
<details>
<summary><h3> 0. Git Basics </h3></summary>
    
  :link:[Tasks](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-intro.md)
   
   Useful links: :link:[Лекція по Git від Олексія Руденка]() | :link:[Git за 30 хвилин](https://codeguida.com/post/453) | :link:[Submit A Pull Request](https://learntocodetogether.com/create-your-first-pull-request/)
   
## 1. Introduction to Git and GitHub   
1. _What's was new to me:_
   
     VCS, GIT, branches
1. _Thing that amazed me:_
   
     Track file state (**modified**, **staged** or **committed**);
  - File tracked by Git, will first be modified when we change it in any way. 
  - Then it becomes staged when we mark those changes for tracking.
  - And finally it will get committed when we store those changes in the VCS;
   Merging.
3. _Thing that i going to use in the future:_
   
   `git init`, `git clone`, `git add`, `git commit -a -m`, `git checkout -b new branch`, `git merge`. 
   
  <details>
 <summary><h4> Screenshots </h4></summary>
    
  ![coursera1](readme_img/General/0.1._coursera1.jpg)
  ![coursera2](readme_img/General/0.1._coursera2.jpg)
    
  </details>
      
  <details>
 <summary><h4> Notes </h4></summary>
      
   _Tracked_ files are part of the snapshots, while _untracked_ files aren't a part of snapshots yet.
Each track file can be in one of three main states: ___modified___, ___staged___ or ___committed___.

`~$ git init`       [create a new git repository]
     
`~$ git clone`      [clone existing git repository]
```     
~$ git add        [add file to staging area]
         flags to git add:
               -p [to review changes before adding them]
```   
`~$ git status`   [info about current working tree and pending changes]
```     
~$ git commit   [to get commited]  
         flags to git commit: 
            -m ‘add comment’
     -a [shortcut to stage any changes to tracked files and commit them in one step]
```
`~$ git config -l` 
```     
~$ git log [check the history of the commits]
    flags to git log:
     -p     [ using this flag gives us the patch that was created]
    --stat  [which files were changed and how many lines were added or removed]
      -2    [any number, limits output to this parameters]
```
`~$ git rm` [remove files from your repository]
     
`~$ git mv` [rename files in your repository]

`~$ git checkout` [reverts changes to modified files before they are staged]
     
`~$ git reset`    [reverts changes(unstage) to staged files ]

`~$ git commit --amend` [ to overwrite the previous commit]
     
`~$ git revert`         [ it creates a commit that contains the inverse of all the changes made in the bad commit in order to cancel them out ]

`~$ git checkout <branch>`      [Switches to a branch]
     
`~$ git checkout -b new branch` [to create a new branch and to switch to it]

__Merging__ is the term that Git uses for combining branch data and history together.

`~$ git merge` [take the independent snapshots and history of one Git branch, and tangle them into another]
     
`~$ git merge --abort` [this will stop the merge and reset the files in your working tree back to the previous commit before the merge ever happened]

`~$ git log --graph --oneline` [--graph for seeing the commits as a graph, and --oneline to only see one line per commit]

`.gitignore` [file that contains list of file that need to be ignored in repo] 

     
  <details>
 <summary><h4> more </h4></summary>
  
```
 diff
    
diff is used to find differences between two files. On its own, it’s a bit hard to use; instead, use it with diff -u to find lines which differ in two files:
~$ diff -u menu1.txt menu2.txt
    
Patch
    
Patch is useful for applying file differences. See the below example, which compares two files. The comparison is saved as a .diff file, which is then patched to the original file!
~$ diff -u menu1.txt menu2.txt > menu.diff
~$ patch menu1.txt < menu.diff
                              
Using GIT

The area outside the git directory is the working tree.
The working tree is the current version of your project.
You can think of it like a workbench or a sandbox where you perform all the modifications you want to your file. This working tree will contain all the files that are currently tracked by Git and any new files that we haven't yet added to the list of track files.

~$ git init        [create a new git repository]
~$ git clone       [clone existing git repository]
~$ git add         [add file to staging area] 
    flags to git add:
      -p [to review changes before adding them]


To make Git track our file, we'll add it to the project using the git add command. With that added our file to the staging area (index).The staging area which is also known as the index is a file maintained by Git that contains all of the information about what files and changes are going to go into your next commit.

~$ git status     [info about current working tree and pending changes]  
~$ git commit     [to get commited]
      flags to git commit: 
         -m ‘add comment’
         -a [shortcut to stage any changes to tracked files and commit them in one step]

~$ git config -l 
~$ git log    [check the history of the commits]
    flags to git log:
           -p [ using this flag gives us the patch that was created]
       --stat [which files were changed and how many lines were added or removed]
           -2 [any number, limits output to this parameters]
                              
Tracked files are part of the snapshots, while untracked files aren't a part of snapshots yet.
Each track file can be in one of three main states: modified, staged or committed.

File tracked by Git, will first be modified when we change it in any way. 
Then it becomes staged when we mark those changes for tracking.
And finally it will get committed when we store those changes in the VCS.


Advanced Git interactions 

Git uses the HEAD alias to represent the currently checked out snapshot of your project.
Think of HEAD as a pointer to the current branch.

~$ git show “commit ID” [display the information about the commit and the associated patch]
~$ git diff [ same as diff -u]
git diff shows only unstaged changes by default
    flags to git diff : 
      --staged [to see the changes that are staged but not committed]

~$ git rm [remove files from your repository]
~$ git mv [rename files in your repository]

.gitignore [file that contains list of file that need to be ignored in repo] 

Undoing Changes Before Committing

~$ git checkout [reverts changes to modified files before they are staged]
~$ git reset    [reverts changes(unstage) to staged files ]

~$ git commit --amend [ to overwrite the previous commit]
~$ git revert         [ it creates a commit that contains the inverse of all the changes made in the bad commit in order to cancel them out ]

Branching and Merging

The default branch that Git creates for you when a new repository initialized is called master.

~$ git branch [ list, create, delete, and manipulate branches. Running git branch by itself will show you a list of all the branches in your repository ]
    flags to git branch:
          -d [delete branch]
~$ git checkout <branch> [Switches to a branch]

~$ git checkout -b new branch [to create a new branch and to switch to it]
  
Merging is the term that Git uses for combining branch data and history together.

~$ git merge [take the independent snapshots and history of one Git branch, and tangle them into another]
~$ git merge --abort [this will stop the merge and reset the files in your working tree back to the previous commit before the merge ever happened]

~$ git log --graph --oneline [--graph for seeing the commits as a graph, and --oneline to only see one line per commit]

```
  </details>
    
  </details>
  
 
  
<!------------------------------- learngitbranching.js.org  --------------------------------->
   
## 2. learngitbranching.js.org   
1. _What's was new to me:_
                              
 `git switch` - more logical for me than `git checkout` (verbally closer)
                              
 `git fetch` , `git pull` , `git push` 
                              
1. _Thing that amazed me:_
                              
 `git pull` = `git fetch` + `git merge`
                              
1. _Thing that i going to use in the future:_
                              
`git switch` , `git rebase` , `git fetch` , `git pull` , `git push`
    
  <details>
 <summary><h4> Screenshots </h4></summary>

 ![LearnGitBranching_Main](readme_img/General/0.2._LearnGitBranching_Main.jpg)
 ![LearnGitBranching_Remote](readme_img/General/0.2._LearnGitBranching_Remote.jpg)

  </details>
      
  <details>
 <summary><h4> Notes </h4></summary>
     
`~$ git rebase` [Rebasing essentially takes a set of commits, "copies" them, and plops them down somewhere else.]
     
   to **fetch** data from a remote repository - the command for this is conveniently named `git fetch`
     
   `git pull` is essentially shorthand for a *git fetch* followed by a *merge* of whatever branch was just fetched.
     
   `git push` is responsible for uploading your changes to a specified remote and updating that remote to incorporate your new commits. Once git push completes, all your friends can then download your work from the remote
     
   `git pull --rebase` is shorthand for a fetch and a rebase
     
  <details>
 <summary><h4> more </h4></summary>
 
![LearnGitBranching_more](readme_img/General/0.2._LearnGitBranching_more.jpg)
     
  </details>
    
  </details>
    
<!-------------------------------  PR Kottans/mock-repo        --------------------------------->
     
***
     
  <details>
<summary><h3> PR mock-repo </h3></summary>

 ## 6. PR Kottans/mock-repo

 
   </details>

***
     
<!-------------------------------          --------------------------------->
     
     
  </details>
<!-------------------------------          --------------------------------->
     
  <details>
<summary><h3> 1. Linux CLI and Networking </h4></summary>
   </details>
 
  <details>
<summary><h3> 2. VCS (hello gitty), GitHub and Collaboration </h4></summary>
   </details>
 
</details>

<details>
<summary><h2> Front-End Basics </h2></summary>
</details>
