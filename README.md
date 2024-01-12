# Version Control

 **Version control** is like a system that helps keep track of changes to files and different versions of a project as it evolves. It's super important when many people are working together on software, but it's handy for any project that goes through different versions and changes over time.
 
# The Difference Between Git And Github

 **Git** is the tool you use locally on your computer to manage versions, while **GitHub** is the online platform that stores your Git projects, making it easier for multiple people to collaborate on the same project, track changes, and work together more seamlessly
# 3 Alternatives To Github

 ### GitLab:
  it is known for its all in one approach, where it combines multiple features essential for development, collaboration, and deployment in a single platform.
 ### SourceForge: 
  it is an older platform designed for teamwork and hosting on software projects. It supports various version control systems, including Git, Mercurial, and Subversion. 
 ### RhodeCode:
  is like a secure space for managing computer code, and it's kept secure behind a firewall. It supports various version control systems, including Git, Mercurial, and Subversion.

# The difference Between Git Fetch And Git Pull
 **Git Fetch** retrieves the changes from the remote repository but does not automatically merge or apply them to your working directory. while 
 **Git Pull** fetches the changes from the remote repository and automatically merges them into the current branch.
 
# Git Rebase And Its Command
 **Git Rebase** rewrites commits from one branch onto another, providing a cleaner repo history. Rebasing is an alternative to merging, offering a cleaner history for faster debugging.
 ### Git Rebase Command
  <mark>git rebase -i main</mark>

# Git Cherry-Pick And Its Command
 "cherry-picking" in Git refers to selecting and copying a specific commit from one branch and applying it onto another branch. It's useful when you only want to bring in specific changes or fixes from one branch to another.
  ### Git Cherry-Pick Command
  <mark>git log </mark> or <mark>git log --oneline</mark> to figure out the commit with their abbreviated hashes

  <mark>git cherry-pick 345g434</mark> for a single commit

  <mark>git cherry-pick 345g434 239c782</mark> for a range of commit

  











  


 






