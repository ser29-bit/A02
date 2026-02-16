# A02

__Part 1__

This is a tutorial on how to create a repository on GitHub using the website.

First, you need to go to GitHub.com. There, you can either sign up for an account or log in using your account. To sign up, you need an email or a connection to a Google or Apple Account. 

After logging in or creating your account, you should be met with your GitHub Dashboard. There, you should see a section to the left-hand side of your screen that says “Create your first project” with two buttons below that state “Create repository” and “Import repository”. For this tutorial, you would want to click “Create repository”. If the “Create your first project” section is not present, you can click the “+” button to the top right-hand side of your screen and select “New repository”.

After selecting the button, you should be redirected to a screen titled “Create a new repository”. There you will see two sections, “General” and “Configuration”. You will also see several text fields and drop down menus that require you to fill them out. 

Under “General”, the first menu is the “Owner” menu, which we will leave alone for now. Then, you are required to give your repository a name. Below that is an optional description of your repository.

The next section, “Configuration” first requires you to choose the visibility of your repository, Public or Private. If you want anyone on the internet to be able to see your repository, you should select public. However, if you want only those you choose to be able to see your repository, you should select private. For both the public and private options you are able to choose who can commit to the repository, or essentially edit files.

After selecting your visibility, the next three options are optional. The first is whether you would want to add a “README” file, which allows for longer written descriptions of what is being done in your repository. The next option is whether you want to add a “.gitignore” file, which you will likely not need now, but essentially when you actually begin to write code and save it in your repository, it tells Git what files you do not want saved every time you commit. Then, you will see the option to add a license to your repository which essentially explains to other people who may use your code what they can and cannot do with it.

After you make the necessary selections and specifications, you can click the “Create repository” button at the bottom right-hand side of the screen. Congrats, you have made a repository using GitHub!

---

__Part 2__
- **Branch**: A branch is essentially a separate but parallel version of a repository that can be edited and eventually committed without impacting the master branch. Branches can be merged together and with the master branch.
- **Clone**: A clone is a local copy of a repository that can be edited on your device using the tool of your choosing (e.g. VSCode). The clone is connected to your remote repository via Git, any changes or updates you want synced to the remote repository are managed via Git.
- **Commit**: A commit is essentially a save point in a repository, where any updates or changes are saved to a repository. A single file or whole repository can be committed. The version of the repository when the commit was made can be accessed later on.
- **Fetch**: To fetch means to bring changes from a remote repository to the current branch you are working on without actually saving them to your branch. Essentially, it allows you to see what changes were made before merging them.
- **GIT**: Git is a free and open-source software that allows programmers to manage their code  and when using remote repositories, allows programmers to collaborate in an organized manner.
- **Github**: GitHub is a platform that allows programmers to host remote repositories, collaborate, and share their code.
- **Merge**: Merging means combining branches of a repository, specifically combining another branch with the current branch you are working on. 
- **Merge Conflict**: A merge conflict often occurs in collaborative work, when there is a conflict between two branches that may cause issues in the code, such as certain file being deleted in one branch while another edits that same file. Merge conflicts often need to be fixed manually.
- **Push**: To push something means to send committed changes made in your local repository to the remote repository,
- **Pull**: To pull something means to grab or fetch changes made in the remote repository and merge them with your current branch.
- **Remote**: A remote refers to either a remote repository or remote branch that is hosted elsewhere besides one’s local device, often on a server like GitHub. Remote repositories or branches allow for collaboration and are synced with local clones on collaborators’ devices.
- **Repository**: A repository is essentially where all of a programming project’s files are stored when using Git, and it contains both project files and the revision histories of those files. Repositories can be local or remote and can be publicly accessible or private.

---

__Resources__
- https://git-scm.com/docs/gitglossary
- https://docs.github.com/en/get-started/learning-about-github/github-glossary
- https://docs.github.com/en/get-started/start-your-journey/about-github-and-git 
- https://www.geeksforgeeks.org/git/what-is-a-git-repository/
- https://github.com/orgs/community/discussions/22286 
- https://www.geeksforgeeks.org/git/git-introduction/
- https://about.gitlab.com/blog/git-pull-vs-git-fetch-whats-the-difference/
