# Learn 0.1
## Git and GitHub

You guys might think why this is named as **Learn 0.1**🧐🧐, the reason we named like that is these are the prerequisites that you should know before starting actial Concepts.
Let's start with the concepts.

### What is Version Control?
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. Some benifits of Version Control are:
- A complete long-term change history of every file. We can have a track of every single commit in our Project.
- Branching and merging. You'll get to know about this later
- Traceability

### What is Git?
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).


### How to install Git?
Before you start using Git, you have to make it available on your computer. Even if it’s already installed, it’s probably a good idea to update to the latest version. You can either install it as a package or via another installer, or download the source code and compile it yourself.

**Installing on Windows:**

As many of you use Windows OS check out this step by step tutorial https://phoenixnap.com/kb/how-to-install-git-windows

**Installing on Linux:** 
```$ sudo dnf install git-all```

**Debian-based distribution:** 
```$ sudo apt install git-all```

**Installing on macOS:**
There are several ways to install Git on a Mac. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.

```$ git --version```

If you don’t have it installed already, it will prompt you to install it.

If you want a more up to date version, you can also install it via a binary installer. A macOS Git installer is maintained and available for download at the Git website, at https://git-scm.com/download/mac.

## What is GitHub?
GitHub, Inc. is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.

## What is the difference between Git and GitHub?
After all, in the world of programming, naming conventions aren’t always intuitive. That’s why it’s worth recognizing the connections and the differences in the similarly named Git and GitHub. Both Git and GitHub give programmers valuable version-control functionality so that they can build ongoing coding projects without being afraid of messing everything up. GitHub just takes things a little bit further than Git, offering more functionality and resources, as well as a place online to store and collaborate on projects. See the below image for a simple understanding on the difference.

![Gitvs_Github-1c-750x321-1](https://user-images.githubusercontent.com/62557178/127492180-d620a81f-447e-48e7-b3e4-7918be0a6e68.jpg)

## Important Terminology
Let's see some terms that we'll use in this training. I know that this is so much, no need to remember this stuff just have a glance. Infact there are alot of termm that I haven't included yet.😅😅
- **@mention:** To notify a person on GitHub by using @ before their username. Users in an organization on GitHub can also be a part of a team that can be mentioned.
-  **base branch:** The branch into which changes are combined when you merge a pull request. When you create a pull request, you can change the base branch from the repository's default branch to another branch if required.
-  **Bio:** The user-generated description found on a profile: Adding a bio to your profile gives more info to the reader about your skills and stuff.
-  **Branch:** This is an important term to remember. A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
-  **clone:** A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
-  **collaborator:** A collaborator is a person with read and write access to a repository who has been invited to contribute by the repository owner.
-  **commit:** A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
-  **fork:** A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.
-  **Git:** Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
-  **GitHub App:** GitHub Apps provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.
-  **merge:** Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
-  **pull request:** Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.
-  **push:** To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
-  **README:** A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.
-  **repository:** A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.




