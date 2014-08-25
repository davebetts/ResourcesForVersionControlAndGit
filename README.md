Resources For Version Control And Git
================================

## Vocabulary
* VCS = Version Control System
* Git = a VCS (there are others)


## Rationale

From [Ten Simple Rules for Effective Computational Research](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1003506):

> Rule 7: Version Control Everything  
>  
>  Version control systems (VCSs) offer an easy way to store and back up not only the current version of your code that you are working on but also every previous version of the code (in what's known as a repository). This not only saves you from having to keep multiple copies of the same file but also allows you to "roll back" to an older "working" version of the code if things go wrong. VCSs also allow you to share material between multiple machines, operating systems, and more importantly, users in a simple and robust manner. Two of the most popular VCSs are [Subversion](http://subversion.apache.org) and [Git](http://www.github.com), both of which offer many advanced features for managing your code. Cloud storage such as [Dropbox](http://www.dropbox.com) and [SkyDrive](http://www.skydrive.live.com) offer basic file sharing and backup facilities; however, they don't offer the code management features of true VCSs, so the effort put in to learning a VCS is well worth it (see [Text S1](http://www.ploscompbiol.org/article/fetchSingleRepresentation.action?uri=info:doi/10.1371/journal.pcbi.1003506.s001) for guides on getting started with VCSs). While the primary use of version control is to manage the development and distribution of code, many other collaborative endeavours can be stored in a version control repository. In particular, using version control tools while preparing publications can save time and effort, especially when dealing with input from multiple authors. For example, contributions to this manuscript were managed using a VCS.


## Resources for VCS

These resources are mostly agnostic to the system. They describe what *version control* is and generally, how it works.

* [What is VCS?](http://youtu.be/8oRjP8yj2Wo)
  * Very high-level
  * 6-minute screencast; get your headphones on
* [A Visual Guide to Version Control](http://betterexplained.com/articles/a-visual-guide-to-version-control/)
  * High-level visual descriptions of VCS concepts
  * Introduces some vocabulary
  * But visuals are nice
* [Getting Started: About Version Control](http://git-scm.com/book/en/Getting-Started-About-Version-Control)
  * Advantages over no version control
  * Centralized vs distributed
  * Lots of Git how-to's (branching, merging, etc)
* [Centralized Workflow](https://www.atlassian.com/git/workflows#!workflow-centralized)
  * Somewhat detailed description of our workflow model
  * Don't confuse a *centralized workflow* (how we're implementing VCS using Git) with a *centralized VCS* (e.g., Subversion, which is not our VCS)
* [A Review of 7 Common VCS's](http://www.smashingmagazine.com/2008/09/18/the-top-7-open-source-version-control-systems/)
  * Subversion, Git, Mercurial, Bazaar, and more
* [Choosing a Version Control System - A Beginners Tour of the Options](http://www.codeproject.com/Articles/431125/Choosing-a-Version-Control-System-A-Beginners-Tour)
  * Easy reading
  * First-person account of adopting a VCS
  * Introduction of concepts
  
## Resources for Git

These resources are specific to the Git VCS. Some of the stuff here can be generalized to other systems, but don't count on it.

* [A Visual Git Reference](http://marklodato.github.io/visual-git-guide/index-en.html)
  * Gets into the weeds a bit
  * Visually describes each VCS concept as implemented in Git


## Miscellaneous
* [Managing a statistical analysis project guidelines and best practices](http://www.r-statistics.com/2010/09/managing-a-statistical-analysis-project-guidelines-and-best-practices/)
  * Not really about VCS or Git, but too good not to share
